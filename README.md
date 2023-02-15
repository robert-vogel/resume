# Resume style file

This repository includes `resume.sty` file for formatting resumes
with LaTeX and `example.tex` as a template for users and to 
demonstrate the provided environments and commands.  Lastly, 
I've included `example.pdf` to show the intended output.  

## Requirements and Notes

The style file was only tested using the BasicTeX package of the
macTeX distribution.

## Features

The provided environments help with formatting the resume and
commands provide useful utilities.  Details can be found in the
comments found in `resume.sty' file.

### Environments

* `rtitle` specify the resume title: name and contact information
* `position` specify position title, employer, etc., and a 
    list environment for enumerating achievements and responsibilities
    of that position
* `publications` list environment for enumerating of publications
* `skills` list environment for enumerating skills

### Commands

* `\degree` provides formatting for each earned academic degree
* `\programPackage` is the `\texttt` font to distinguish programs
    and packages from normal text
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

