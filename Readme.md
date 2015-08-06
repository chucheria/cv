# About
Adrien Friggeri's CV, typesetted in Lato and using colors inspired by Monokai (there is an `print` option which renders in black and white, and reverts the header to dark on light, if printing on paper is needed).

Uses TikZ for the header, XeLaTeX and Lato font used from Google Fonts, biblatex to print my publications and textpos for the aside.


# New
Added Cover letter with the same design. The letter it's... well... it lacks of spirit, but I want to add Font Awesome Icons to personalice it. Anyway, it has a Lorem Ipsum text because every cover letter should be unique (or so they say ;) ). 

Added if command to show English or Spanish content. Use:

* In cv.tex

```
\ifenglish
  The technology described in the article is very complex.
\else 
  La tecnología descrita en el artículo es muy compleja.
\fi
```

* In cv.cls

```
\englishtrue 
Show English text only
\englishfalse 
Show Spanish text only 
```

Added a new line spacing (because of the change of font).

#Atribution

**CV** by Adrien Friggeri: https://github.com/afriggeri/cv
**Lato** by Google fonts: https://www.google.com/fonts/specimen/Lato
**Font-Awesome** by Dave Gandy: http://fortawesome.github.io/Font-Awesome/
