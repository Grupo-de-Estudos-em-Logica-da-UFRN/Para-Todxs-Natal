# Para Todxs: Natal

![Book Cover](https://raw.githubusercontent.com/Grupo-de-Estudos-em-Logica-da-UFRN/Para-Todxs-Natal/main/paratodxscapa.png)

## Description

_Para Todxs: Natal_ é um livro didático completo sobre lógica formal.
 Ele aborda noções fundamentais da lógica, como consequência e validade 
de argumentos, a sintaxe da lógica proposicional verofuncional (LVF) e 
semântica de tabelas-verdade, a sintaxe da lógica de predicados de primeira 
ordem (LPO) com identidade (interpretações de primeira ordem), traduções 
(formalizações) do português para LVF e LPO, além de sistemas de prova em 
dedução natural (estilo Fitch) para LVF e LPO. Também são abordados alguns 
tópicos avançados, como completude verofuncional. São disponibilizados exercícios 
com soluções. O livro será disponibilizado inicialmente em LaTeX, em PDF para 
impressão e, posteriormente, em versões especiais para visualização em tela de 
dispositivos eletrônicos, além de uma versão com fonte especial para disléxicos. 
Um editor/checador de provas para o sistema usado no livro está disponível online 
em [proofs.openlogicproject.org](http://proofs.openlogicproject.org/).

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
