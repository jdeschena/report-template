# Project report template

- See [here](https://github.com/jdeschena/report-template/blob/main/main.pdf) for the default compiled file.
- To compile this project locally, install `pdflatex` and run `pdflatex -shell-escape main.tex`.
- You can zip and upload this template to overleaf.
- To change the lab logo, simply replace the file `figures/lab-logo.png`.
- You can update the project's subtitle (` Semester project (12 ECTS) - Master project report` by default) in `title.tex`.
- To modify the project title, student name, lab name and supervisor name, change the following liens in `main.tex`:
```tex
\newcommand{\mytitle}{Project Title}
\newcommand{\authorname}{Student Name}
\newcommand{\professor}{Name of the professor}
\newcommand{\supervisor}{Name of PhD student}
\newcommand{\labname}{CLAIRE}
```


## References
- This template is inspired by the template from the [HexHive](https://hexhive.epfl.ch) laboratory [available here](https://github.com/HexHive/thesis_template).