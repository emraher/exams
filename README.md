I have changed 3 files to make the package compatible with LaTex exam class.

* read_metainfo.R

In this file, I have added `exspace` which creates some space after questions to give space for students to solve the question.

* exams2pdf.R

In this file, I have added `latex_exams = FALSE` to function calls and created an ifelse for `combine question+questionlist and solution+solutionlist` section in the code. This allows me to put points above each question.

* exams2pdf.Rd

In this file, I have updated the help for `latex_class` option.
