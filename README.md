Chartam
===============

## Description
Presents a template for scientific papers and it is about an efficient implementation of binary decision diagrams. This template is structured as follows:

```
├── alphadin.bst
├── appendix
│   ├── appendix.tex
│   └── img
│       └── ...
├── content
│   ├── section1.tex
│   ├── ...
├── img
│   ├── ...
├── main.bib
├── main.tex
├── ...
└── settings
    ├── abbreviations
    │   ├── abbreviations.tex
    │   └── nomencl.ist
    ├── abstract.tex
    ├── commands.tex
    ├── conclusion.tex
    ├── cover.tex
    ├── hyphenation.tex
    ├── introduction.tex
    ├── locking.tex
    └── statutory_declaration.tex
```

The file *main.tex* is the main file and includes all other files. Furthermore, it regulates the formatting etc. The contents of the main chapters are located in the folder *content*. The images used in it are in the folder *img*. All sources are entered in the file *main.bib*. A reference to this is made in the respective chapters. Further structures such as the preface or definitions of commands can be found in the folder *settings*. Among other things, the cover can also be designed there. Meta information can be entered into the file *appendix.tex*. Related images are placed in the folder *appendix/img*. If abbreviations are made, they must be defined in the file *abbreviations.tex*. Afterwards, the command `makeindex main.nlo -s nomencl.ist -o main.nls` must be entered to update it. The use of tables, pictures, quotations etc. are shown in the respective main contents and are supported by comments.

## Prerequisites

+ [LaTeX](https://www.latex-project.org)
+ Editor like [TeXstudio](https://www.texstudio.org) for better handling with *LaTeX*

## Usage
At first, clone or download this project. At this moment, you are able to edit the TeX files and compile it to PDF. For more comfort, use the program *TeXstudio* and open the file *main.tex*. Press *\<F5\>* to create and view the PDF.

## More information
Read more about *LaTeX* at [LaTeX Project](http://latex-project.org/guides/).
