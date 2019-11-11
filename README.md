## Documon - a universal online-documentation renderer

## Why do you reinvent another wheel?

Many tools can convert non-HTML format files to online HTML documentation, but they usually only support one format converting, such as markdown in GitBook.

The goal of Documon is to convert files in various formats to online HTML documentation.

## Why not Pandoc?

[Pandoc] (https://pandoc.org/) is an amazing tool, but its main purpose is to convert file formats, not to generate documentation.

## Requirements

* PHP 7.2+ with pcntl extension
* Node.js 12.0+ with yarn

## Usage

Create config file and generate the templates:

```bash
documon init
```




## License

MIT
