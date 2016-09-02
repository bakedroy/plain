# plain

This is a beamer template. You can use this template with pandoc like bellow.
```
pandoc -f markdown -t beamer --latex-engine=xelatex -H plain.sty -o slide.pdf slide.md
```

If you want to use w/o xelatex, remove the following lines:
```
\usepackage{fontspec}
\usepackage{xeCJK}
\setCJKmainfont{MS PGothic}
```
These lines are for markdown files including Japansese.
