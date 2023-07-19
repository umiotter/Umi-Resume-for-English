# Umi-Resume-for-English

Menki's resume with latex.

# Directory Structure

```
.
├── cv                          .tex file for each section
│   ├── achievements.tex        Achivenments     
│   ├── education.tex           Education
│   ├── experience.tex          Work experience
│   ├── interests.tex           Interests
│   ├── languages.tex           Languages
│   ├── projects.tex            Selected project
│   ├── publications.tex        Publications
│   ├── references.bib          .bib file for publications
│   ├── skills.tex              Skills 
│   └── summary.tex             Biography
├── fonts
├── resume.pdf                  Compiled pdf file
├── resume.tex                  Base information and section display control
└── russell.cls                 Style file
```

# Usage

`resume.tex` file is the entry of controlling the display of each section.

For example, here I hiddened achievements, interests, and languages section by commenting. 

```tex
%-------------------------------------------------------------------------------
%	CV/RESUME CONTENT
%	Each section is imported separately, open each file in turn to modify content
%-------------------------------------------------------------------------------

\input{cv/summary.tex}
\input{cv/skills.tex}
\input{cv/projects.tex}
\input{cv/experience.tex}
\input{cv/education.tex}

% \input{cv/achievements.tex}
 \input{cv/publications.tex}
% \input{cv/interests.tex}
% \input{cv/languages.tex}```
```
# Reference

[Rusell Resume](https://github.com/themagicalmammal/Resume)

[Awesome CV](https://github.com/posquit0/Awesome-CV)

# License

Apache 2.0 