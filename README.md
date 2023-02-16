# Resume style file

This repository contains a `resume.sty` file and an example of its
use.  The style file contains convenient commands and environments
to make a resume with LaTeX.  The `example.tex` may be used as a 
reference example or a template for making a resume.  The example
has been compiled to `example.pdf` showing the resume format.

## Requirements and Notes

The style file was only tested using the BasicTeX package of the
macTeX distribution.

## Features

The provided environments help with formatting the resume and
commands provide useful utilities.  Details can be found in the
comments found in `resume.sty' file.

### Environments

* `rtitle` specify individual's name and contact information
* `position` specify employer, position, date, and a 
    list environment for enumerating achievements and responsibilities
    of that position
* `publications` list environment for enumerating publications
* `skills` list environment for enumerating skills

### Commands

* `\degree` provides formatting for each earned academic degree
* `\programPackage` is the `\texttt` font to distinguish program
    and package names from normal text
* `\resumeSection` provides the text and line formating for resume 
    sections, e.g Selected Experience, Academic degrees, etc.
* Proficiency scales to compactly communicate proficiency of 
    enumerated skills:

    - `\basicknowledge`
    - `\priorexp`
    - `\competent`
    - `\expert`


## Todo & improvements

* Update citation command so that multiple citations can be made

