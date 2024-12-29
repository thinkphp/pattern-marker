# HTML Pattern Marker

A C program that adds HTML mark tags around specified patterns in HTML documents. The program searches for a given pattern and wraps it with `<mark></mark>` tags for highlighting purposes.

## Features

- Search and highlight specific text patterns in HTML files
- Preserve original document structure
- Create a new marked file without modifying the original
- Handle large files with buffered reading
- Proper memory management and error handling

## Installation

```bash
git clone https://github.com/yourusername/html-pattern-marker.git
cd html-pattern-marker
gcc -o html_marker main.c
```

## Usage

```bash
./html_marker <input_file.html> <pattern>
```

Example:
```bash
./html_marker example.html "important"
```

This will create a new file named `marked_example.html` with all occurrences of "important" wrapped in `<mark>` tags.

## Input/Output Example

Input HTML:
```html
<p>This is an important paragraph.</p>
```

Output HTML:
```html
<p>This is an <mark>important</mark> paragraph.</p>
```

## Requirements

- GCC compiler
- Standard C libraries

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
