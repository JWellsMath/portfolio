The simple-example file is exactly what it says it is...a simple example! At present, it currently only contains the following:

<ul>
<li>sufficiently-randomized set of row operations so that I can ensure my students will need no more than three row operations to row reduce a matrix.</li>
</ul>

The important thing to remember about SageTeX is that it requires compiling, then running sage, and then compiling again. This is easily achieved in the terminal:</p>

```
pdflatex fake-exam.tex && sage -c "load('fake-exam.sagetex.sage')" && pdflatex fake-exam.tex
```


