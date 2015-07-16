# per2012-paper

This repository contains the LaTeX source code and additional resources for a tool paper that was accepted for
publication in the ACM SIGMETRICS Performance Evaluation Review. The source code of the tool paper uses the LaTeX style
files provided by the editors of the journal and a wide variety of other packages that are normally standard with a
modern LaTeX distribution such a TeXLive 2015.

You are invited to use this repository as a means for learning more about preparing papers in the field of performance
evaluation and as a way to investigate the results and writing in our paper. If you find this example useful, could I
trouble you to star this repository and then acknowledge it in your own research efforts? If you would like to learn
more about my research program, then you can checkout my
[gkapfham/research-bibliography](https://github.com/gkapfham/research-bibliography).

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/per2012-paper.git
```

Then, if you want to compile the paper to a PDF, you should type the following commands.

```shell
cd per2012-paper
cd paper
pdflatex java_remote_primitives_compare.tex
bibtex java_remote_primitives_compare.aux
pdflatex java_remote_primitives_compare.tex
```

Please note that this has been tested on an Ubuntu 15.04 workstation running a very recent version of LaTeX that was
manually installed using the TeXLive installer.  It is also worth noting that you can also compile the paper using other
LaTeX development tools, such as `latexmk`.  If you are unable to compile the paper with your development tools and your
execution environment, then please open a new issue and I will attempt to resolve your concerns.
