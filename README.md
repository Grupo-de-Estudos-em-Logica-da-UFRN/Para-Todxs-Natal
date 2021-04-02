# Para Todxs: Natal

![Book Cover](http://forallx.openlogicproject.org/forallxyyc.png)

## Description

_forall x: Calgary_ is a full-featured textbook on formal logic. It covers key
notions of logic such as consequence and validity of arguments, the
syntax of truth-functional propositional logic TFL and truth-table
semantics, the syntax of first-order (predicate) logic FOL with
identity (first-order interpretations), translating (formalizing)
English in TFL and FOL, and Fitch-style natural deduction proof
systems for both TFL and FOL. It also deals with some advanced topics
such as truth-functional completeness. Exercises with solutions are
available. It is provided in PDF (for screen reading, printing, and a
special version for dyslexics) and in LaTeX source code. A proof
editor/checker for the proof system used is available at
[proofs.openlogicproject.org](http://proofs.openlogicproject.org/).

[Download](#download) links below.

## Credits and License

_forall x: Calgary_ is based on [_forall x:
Cambridge_](http://people.ds.cam.ac.uk/tecb2/forallx.shtml), by [Tim
Button](http://nottub.com/) used under a [CC
BY 4.0](https://creativecommons.org/licenses/by/4.0/) license, which
is based in turn on [_forall x_](https://www.fecundity.com/logic/), by
[P.D. Magnus](https://www.fecundity.com/job/) used under a [CC BY
4.0](https://creativecommons.org/licenses/by/3.0/) license, and was
remixed, revised, & expanded by [Aaron
Thomas-Bolduc](https://phil.ucalgary.ca/profiles/aaron-thomas-bolduc)
& [Richard Zach](http://richardzach.org/).  It includes additional
material from _forall x_ by P.D. Magnus and
[_Metatheory_](http://people.ds.cam.ac.uk/tecb2/metatheory.shtml) by
Tim Button, both used under a [CC BY
4.0](https://creativecommons.org/licenses/by/4.0/) license, from
[_forall x: Lorain County
Remix_](https://github.com/rob-helpy-chalk/openintroduction), by
[Cathal Woods](https://sites.google.com/site/cathalwoods/) and
J. Robert Loftis, used with permission, and \href{http://www.rtrueman.com/uploads/7/0/3/2/70324387/modal_logic_primer.pdf}{\emph{A Modal Logic Primer}} by \href{http://www.rtrueman.com/}{Robert Trueman}, used with permission.

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

The LaTeX source code for this work is available on GitHub at [github.com/rzach/forallx-yyc](https://github.com/rzach/forallx-yyc).

## Download

You can download PDFs of the files here:

  - [`forallxyyc.pdf`](http://forallx.openlogicproject.org/forallxyyc.pdf) (in color, for screen reading)
  - [`forallxyyc-print.pdf`](http://forallx.openlogicproject.org/forallxyyc-print.pdf) (b/w, for printing on Quarto stock)
  - [`forallxyyc-letter.pdf`](http://forallx.openlogicproject.org/forallxyyc-letter.pdf) (b/w, for printing on regular letter-size paper)
  - [`forallxyyc-accessible.pdf`](http://forallx.openlogicproject.org/forallxyyc-accessible.pdf) (an accessible version for dyslexics)
  - [`forallxsol.pdf`](http://forallx.openlogicproject.org/solutions/forallxsol.pdf) (solutions booklet)

Note that these files change whenevery the source files are
changed. So if you use the text in a course, better to download the
PDFs and make them available to students directly, than to link here.

## Buy a Printed Copy

If you'd like to purchase a nice paperback copy, you can do so on
Amazon ([US](https://www.amazon.com/dp/1077319851) | [CA](https://www.amazon.ca/dp/1077319851) | 
[UK](https://www.amazon.co.uk/dp/1077319851)) (or use search in your local Amazon store).

(The process for getting the book printed is described [here](http://openlogicproject.org/2015/11/22/getting-your-book-to-print/) and [here](http://openlogicproject.org/2017/05/19/forall-x-yyc-is-now-on-amazon-and-how-it-got-there/).)

## Make PDFs Yourself

Clone the [GitHub repository](https://github.com/rzach/forallx-yyc) locally or download the ZIP file and run [LaTeX](http://www.latex-project.org/) on one of

  - `forallxyyc.tex` (in color, for screen reading)
  - `forallxyyc-accessible.tex` (accessible version)
  - `forallxyyc-print.tex` (b/w, for printing on Quarto stock)
  - `forallxyyc-letter.tex` (b/w, for printing on regular letter-size paper)

You'll have to run `makeglossaries` to produce the glossary as well.

To make changes to the definitions in the preamble and `forallyyc.sty`
file, put them in a file named `forallxyyc-local.sty`. For instance,
to get the connectives to be & for and and horseshoe for the
conditional, copy `forallxyyc-local-sample.sty` to that file.
