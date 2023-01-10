# BI Beamer Theme

Before you use the theme, make sure that you have installed the following font families on your computer:

- Fira Sans Condensed (download OTFs from https://www.fontsquirrel.com/fonts/fira-sans-condensed),
- Fira Mono (download OTFs from https://www.fontsquirrel.com/fonts/fira-mono).

Note: The theme uses the following fonts
- Fira Sans Condensed,
- Fira Sans Condensed Italic,
- Fira Sans Condensed Light,
- Fira Sans Condensed Light Italic,
- Fira Mono,
- Fira Mono Medium.

If you want to use different fonts, search for `\setsansfont` and `\setmonofont` in `beamerthemebi.sty` and modify these two lines.

Until the official release, we recommend to use the BI beamer theme by copying `beamerthemebi.sty` and the `beamerthemebi` folder to the folder with your presentation. To use the theme, add the following line in the TeX source of your presentation:
```TeX
\usetheme{bi}
```
and run XeLaTeX twice to compile it and generate the PDF file, e.g.
```
xelatex sample_presentation.tex
xelatex sample_presentation.tex
```
