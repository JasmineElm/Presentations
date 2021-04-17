# Simple presentations in Pandoc

This is the presentations version of [reports](https://github.com/JasmineElm/reports) repository.

It intends to make writing presentations easier, by using simple markdown, standard templates, and some sensible Pandoc defaults.


## Making a presentation

+ Write the presentation in [the code directory](code/)
  + use one or more `*.md` files.
+ Add references to [references.bib](code/references.bib)
+ Add images to [figures](code/figures)
+ update the [meta.yaml](code/config/meta.yaml)
+ invoke the script with the desired output

## Rendering

```text 
Simplifies building presentations in html, PowerPoint and pdf

Usage:
  ./build [BUILD OPTIONS]

Build Options:
  -h | --help   Show this screen.
  -p | --pdf    build pdf
  -x | --pptx   build PowerPoint
  -w | --html   build html (using slidy.js)
  -c | --clean  clear the output directory
  -s | --silent remove any logs created
```

## Suggested third party apps

+ [vale-cli](https://github.com/errata-ai/vale) will call out bad grammar.
+ [prettier](https://prettier.io/) can help automatically fix linting issues
