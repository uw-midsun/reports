This LaTeX template is intended for creating formal reports, including Vehicle Design Reports for ASC.

It is designed to be compiled using LuaLaTeX, which is included in standard LaTeX distributions such as TeXLive and MacTeX. The design of the template uses the Futura font. This font is included on Macs but needs to be separately obtained if compiling on another platform.

The bibliography management solution used by the template is Biber, an implementation of BibLaTeX (not to be confused with BibTeX, which is a separate, older program).

To correctly build this project, run the following commands:

lualatex <filename>.tex
biber <filename>.tex
lualatex <filename>.tex
lualatex <filename>.tex

The multiple compilations ensure that cross-references to figures, tables, etc. are correct (this is the standard build flow for LaTeX).
