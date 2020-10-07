# Basic Report Template for Teams in Labs

Basic team report written in LaTeX (Spanish encoding)

This latex template uses files.

## Basic Usage

Add your sections as files (inside this files you can have subsection etc.) , so if you need three sections you need to create 3 files, 
let say: **section1.tex**, **section1.tex**, **section1.tex**.
for simplicity I added a folder named sections, so you will add your section files in **sections/my_section.tex**.

To add your files to the final PDF just open up in the root the file called report.text, then go to the document section and add them
in the **\input(your_file.tex)**. 

Finally, just compile your file and that's all.
