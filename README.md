# Haskell Articles

Dervied from the post [A List of Haskell articles on good design, good testing](https://williamyaoh.com/posts/2019-11-24-design-and-testing-articles.html)

All articles are contained in this repostory in LaTeX book format.

## LaTeX'ing

The source uses the LaTeX package minted for syntax highlighting. This package needs the flag "-shell-escape" specified. So to build the document:

```
pdflatex -shell-escape HaskellArticles.tex
```

There is also a bibilography contained, so you need to run BibTex as well and pdflatex several times to get the cross references right. 


