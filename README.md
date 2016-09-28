# dlbook_chap20

This repository contains a beamer-style presentation slide for the latter half of the chapter 20 in [the deep learning book](http://www.deeplearningbook.org/) written by Goodfellow et al.

There are two possible ways to build a PDF slide from the source files. One way is to use an org file, and the other way is to use a tex file. If you are familiar with an emacs org mode, go ahead and use an org file. Otherwise, it is probably easier to compile a tex file by typing the following command in the terminal.

```bash:
$ platex chap20_deep_generative_models.tex
$ platex chap20_deep_generative_models.tex
$ dvipdfmx chap20_deep_generative_models.dvi
```

If everything works correctly, it generates many files including ` chap20_deep_generative_models.pdf`.