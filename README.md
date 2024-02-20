# TL;DR

This repository is about showcasing a method to create material for teaching English.

* [OUTPUT1-lesson.pdf](OUTPUT1-lesson.pdf)  gives an example of slides that can be shown in class.

* OUTPUT2-worksheet.pdf gives an example of various exercises that can be printed out on worksheets for students.

* OUTPUT3-worksheet-corrected.pdf is the corrected version of OUTPUT2-worksheet.pdf.

* OUTPUT4-MOODLE-EXERCISES.xml gives an example of interactive online exercises that can be uploaded on [Moodle](https://moodle.com/).

* Folders `data/` and `pdfdata/` contain the files used to generate the output documents listed above.

![](flowchart.png)

# Outline

This repository stores the input and output files of my R-based set of functions to generate pedagogical material for teaching English (i.e. slides, worksheets and Moodle exercises).

This R-based set of functions, `UniversalDispatchR`, is **not** in the repository.

# Concept

The idea is to enable teachers like me to create content easily.

Simple text files can be used to generate exercises that can be printed on worksheets, shown on slides, or done online interactively on Moodle.

# Mechanics

A `.csv` file is fed into `UniversalDispatchR`.

Depending on its name and internal structure (*i.e.* its number of columns), a certain type of exercise will be created.

Corrections are provided in the slides, and they can also be easily generated in a corrected version of the worksheet.

# Files found in this repository

"OUTPUT1-lesson.pdf", "OUTPUT2-worksheet.pdf" and "OUTPUT3-worksheet-corrected.pdf" were created from the `.csv` files in the `pdfdata/` folder.

"OUTPUT4-MOODLE-EXERCISES.xml" was created using the `.csv` files in the `data/` folder.

These files showcase the different exercises that can be generated with `UniversalDispatchR`. 

The interactive Moodle exercises from "OUTPUT4-MOODLE-EXERCISES.xml" can be uploaded to a Moodle question bank, or tried on my website and its Moodle:

[englishforthefrench.com](https://englishforthefrench.com/moodle/)

**Login details:**

* id: tester
* pw: Super2024!!

Please use Firefox or Chrome, **not** Safari.
