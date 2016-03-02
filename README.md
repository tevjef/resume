latex-moderncv is a repository containing my resume compiled in latex using a very nice modern theme


Prerequisites
=============

You will need to have latex installed on your system to compile the .tex file and to produce a pdf output.

#### Cross Platform (OSX, Windows, Linux)
* [Texmaker	The universal LaTeX editor](http://www.xm1math.net/texmaker/download.html)

####  Mac OSX 
* [MacTex](http://tug.org/mactex/)

Installation
============

Install Latex and download the moderncv theme. Place the moderncv theme somewhere Latex can find it. You can just place the folder in the same place as your .tex file as I have:

    /my-resume
        my-resume.tex
        my-resume.pdf
        /moderncv

Configure your editor to use my `moderncv.cls` file for the moderncv document class.

Compiling the Resume
====================

Simply use the ``pdflatex`` command in your terminal::

    pdflatex my-resume.tex

Credits
=======

Latex is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia. You can find out more about it here: http://www.latex-project.org/

The moderncv theme for my resume is contributed by Xavier Danaux and can be downloaded here: http://tug.ctan.org/tex-archive/macros/latex/contrib/moderncv/

Notes
=====

You are free to take my .tex file and modify it to create your own resume. Please don't use my resume for anything else without my permission, though! 

Good luck!
