[![View in Greek](https://img.shields.io/badge/View%20in-Greek-blue)](README_el.md)
<p align="center">
  <img src="images/titlepage/ihu-logo-gr.png" alt="International Hellenic University logo">
  <br>
  <b>International Hellenic University Thesis Template</b>
</p>

# About

This LaTeX template is specifically designed for thesis writing at the International Hellenic University. It has been created with the purpose of providing a well-organized and easy-to-use framework for students.

The structure of the template is such that each part of the thesis is separated into different `.tex` files. This includes individual chapters, the abstract, the dedication, and the prolog, each of which can be modified separately. This not only makes the writing process more efficient but also ensures that the structure of the thesis remains consistent and well-organized.

Additionally, the template comes with built-in support for both Greek and English languages, which can be easily switched using the `\setdefaultlanguage{}` command. It also features FreeSerif, FreeSans, and FreeMono fonts, which provide a professional and clean aesthetic to the thesis.

We hope that this template aids you in writing your thesis and simplifies the process. For any issues or improvements, please feel free to contribute to this repository.

## How to Use

1. This template has been designed and used on Overleaf, but can be used with any distribution or Latex IDE, as long as it supports the `XeLaTeX` and `LuaLaTeX` compilers, which were tested and working.

2. Clone or download this repository.

3. Upload the downloaded .zip file or zip the cloned files and then upload to Overleaf, 

4. Open `main.tex` in your LaTeX editor.

5. Update the language & document-specific settings in `main.tex` according to your needs. The commands to be updated are:

```tex
%=================================================================
% Language settings, swith the two languages to change language.
\setdefaultlanguage{english} % Default language is English
\setotherlanguage{greek}     % Secondary language is Greek

% Document-specific information
\newcommand{\thesisTitle}{INSERT PAPER TITLE HERE}
\newcommand{\thesisTitleGreek}{ΕΙΣΑΓΕΤΕ ΕΔΩ ΤΟΝ ΤΙΤΛΟ ΤΗΣ ΕΡΓΑΣΙΑΣ}
\newcommand{\studentName}{Alexandros Magos}
\newcommand{\studentNameGreek}{Αλέξανδρος Μάγος}
\newcommand{\studentID}{185320}
\newcommand{\supervisorName}{Antonis Sidiropoulos}
\newcommand{\supervisorNameGreek}{Αντώνης Σιδηρόπουλος}
\newcommand{\undertakingDate}{14-01-2023}
\newcommand{\completionDate}{23-05-2023}
%=================================================================
``````

6. Add your chapters as separate .tex files inside the chapters folder. For each chapter, you should have a command `\include{chapters/Your_Chapter}` in main.tex.

7. Add your bibliography file (references.bib) in the includes folder.

8. Add your images in the images folder. To include images in your document, use the command `\includegraphics{images/Your_Image}`.

9. Once you have made all the necessary changes, compile main.tex.

If you encounter any problems while using this template, please check the error message in your LaTeX editor. For further issues or improvements, feel free to contribute to this repository.

## Note

- A step to step instruction file with images on the above setup using overleaf will be added soon.