# Fortran

# About

Fortran is old. Very old. The first version of it is from 1957.

As one might expect, programming something from the [punch card](https://en.wikipedia.org/wiki/Punched_card) era can be painful. Old versions of the language reflected punch cards in that certain columns on the screen were used for certain things. Specifically, this meant indenting with spaces until column 7, where you would start a new line; continuing long lines by indenting to column 6 and starting; using the first 5 columns for a label (used in looping); and placing a C in column 1 to skip all of those rules and use the entire line as a comment.

Yuck!

With a large amount of legacy code written in Fortran and the language still being pretty usable for a lot of things, the standard kept evolving and Fortran 90 onward remove the above fixed format rules. Each version (Fortran 90, Fortran 95, Fortran 2003, Fortran 2008) has added additional functionality and made the language a better choice for modern development.

It's still far from ideal for almost any task, but it has its specialties (such as number crunching and working with matrices) that make it a good choice for some projects.

If you find yourself writing Fortran code, I strongly recommend Fortran 90 and newer if at all possible. Many of my links are F77-specific as that's what I first learned a bit of, but there are some generic ones as well.

[Read more](https://en.wikipedia.org/wiki/Fortran) at Wikipedia.

# Free Resources

## Books/Tutorials

+ [Fortran Wiki](http://fortranwiki.org/fortran/show/HomePage): a large wiki devoted to the language.
+ [Fortran wikibook](https://en.wikibooks.org/wiki/Fortran): community-written book on Fortran, mostly focused on Fortran 95.
+ [Fortran 90](http://www.fortran90.org/index.html): best practices for writing Fortran code. Also includes a helpful guide showing [how to write things in Fortran](http://www.fortran90.org/src/rosetta.html) based on how you would write them in [Python](https://github.com/rnelson/learnsomethingnew/blob/master/programming_languages/python.md).
+ [Professional Programmer's Guide to Fortran77](http://www.star.le.ac.uk/~cgp/prof77.html): a book covering Fortran 77.
+ [Fortran Resources and Fortran 77/90/95 Compilers for Windows and Linux](http://www.personal.psu.edu/faculty/h/d/hdk/fortran.html): compilers and tutorials for Fortran.
+ [Fortran 77 standard](http://www.fortran.com/fortran/F77_std/rjcnf0001.html): a very technical list of the entire F77 standard. Not intended for people without prior programming experience.
+ [Using C/C++ and Fortran together](http://www.yolinux.com/TUTORIALS/LinuxTutorialMixingFortranAndC.html): a somewhat advanced topic, this covers using C/C++ and Fortran together, such as using a third-party C library to do some work in your Fortran project.
+ [Clive Page's list of Fortran Resources](http://www.star.le.ac.uk/~cgp/fortran.html): compilers, tutorials, and small tips for Fortran.
+ [Fortran90 for Fortran77 Programmers](http://www.star.le.ac.uk/~cgp/f90course/f90.html): helpful information for migrating from F77 to F90.
+ [Source Codes in Fortran90](http://people.sc.fsu.edu/~jburkardt/f_src/f_src.html): hundreds of examples of doing various things, mostly scientific, in Fortran.

## Software

+ [g95](http://www.g95.org): open source Fortran 95 compiler.
+ [gfortran](https://gcc.gnu.org/fortran/): another open source Fortran 95 compiler originally based on g95. Most things I've found recommend g95 over gfortran.
+ [Photran](http://www.eclipse.org/photran/): Eclipse IDE for Fortran.
+ [Free PGI for OS X](https://www.pgroup.com/purchase/freepgi.php): free PGI compilers (C and Fortran) for OS X. Limited use; binaries built with these compilers cannot be used on any other machine.
+ [Fortran Resources and Fortran 77/90/95 Compilers for Windows and Linux](http://www.personal.psu.edu/faculty/h/d/hdk/fortran.html): compilers and tutorials for Fortran (listed above as well).
+ [Fortran on a Mac](http://www.macinchem.org/reviews/fortran/fortran.php): a list of Fortran compilers and libraries commonly used on OS X.
+ [Clive Page's list of Fortran Resources](http://www.star.le.ac.uk/~cgp/fortran.html): compilers, tutorials, and small tips for Fortran (listed above as well).
+ [Open Watcom](http://www.openwatcom.org/index.php/Main_Page): open sourced (formerly commercial) [C/C++](https://github.com/rnelson/learnsomethingnew/blob/master/programming_languages/cpp.md) and Fortran 77 compilers for DOS, OS/2, Windows, and Linux.

# Paid Resources

+ [Practical Programming](https://pragprog.com/book/gwpy2/practical-programming): this is a great book for learning Python by writing cool things. The first few chapters cover the basics of the language, and after that it moves on to interesting real-world examples that teach you additional features as you go. **Note:** I purchased [the first edition](https://pragprog.com/book/gwpy/practical-programming), which is no longer in print. The second edition is tailored to Python 3; at present, you can get a copy of the first edition by purchasing the second and contacitng support.
