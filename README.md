[![CC BY 4.0][cc-by-shield]][cc-by]
# Interoperability Guidelines for the SIOS Data Management System (SDMS).

## Purpose
The purpose of this repository is to establish a collaborative work flow developing the SIOS Data Management System (SDMS) interoperability guidelines. These are used to define how contributing data centres can connect to the SDMS. 

The guidelines are automatically processed into a PDF and HTML variant. These versions are available through the links below. Please beware that the document provided through the links is the most recent working copy.

- [PDF](https://github.com/SIOS-Svalbard/SDMSInteroperabilityGuidelines/blob/master/doc/sdms_iog.pdf)
- [HTML](https://htmlpreview.github.io/?https://github.com/SIOS-Svalbard/SDMSInteroperabilityGuidelines/blob/master/doc/sdms_iog.html)

## Setup
Documents are transformed from the original OpenDocumentFormat into ASCIIDOC. Guidelines on how to format ASCIIDOC are available at
- https://asciidoctor.org/docs/asciidoc-syntax-quick-reference
- https://asciidoctor.org/docs/user-manual/

The document has been seperated into several logical building blocks which can be further separated if required.

## Work flow
The intention is to collaborate on the document using issues which are translated into pull requestsn (PR) when agreed. 
Major revisions will always require a separate review of the PR. 
In this context every modification should follow the process (assuming all contributors are members of the project, ask if not):
1. Do a git pull to update your local code
1. Create a new local branch using git checkout -b [name_of_your_new_branch]
1. Make you local changes and commit using git commit
1. Push local changes to GitHub using git git push origin [name_of_your_new_branch]
1. Create a PR using the graphical user interface at GitHub.

![WorkFlow](/doc/Pictures/github-workflow4documents.png)


## License
This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
