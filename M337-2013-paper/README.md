## M337 2013 exam solutions

These are the source files for the solutions to the M337 (Complex
Analysis) exam from 10.06.2013.

It is all written in LaTeX with texlive/2012 under Linux. It should
work under other operating systems such as windows and Mac, or you may
need to tweek it.

The main file is `m337-2013-1.tex`, and there is a separate file for each
question, these are named `m337-2013-1qXX.tex`, e.g. `m337-2013-1q01.tex`.
The diagrams are created using Tikz and are in separate files,
e.g. `m337-2013-1q02a1.tex`.

To generate the PDF document use the command

	pdflatex m337-2013-1.tex

The plot of the hyperbola in Q7b is created with Tikz and gnuplot,
depending on your setup you may need to used following command, to enable
the gnuplot command to be executed.

	pdflatex --shell-escape m337-2013-1.tex

Enjoy!

Fred Youhanaie
