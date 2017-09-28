

ICFO poster template
====================

This is a LaTeX poster template designed to match the existing (powerpoint) poster template for ICFO - The Institute of Photonic Sciences, Barcelona.

This template uses the baposter.cls LaTeX class, available from http://www.brian-amberg.de/uni/poster/, and it requires LuaLaTeX, and the Swiss 721 font, to compile correctly in its standard form. To compile, the Swiss 721 font should be installed in the standard system directory, and (all being well) the fontspec package will get it from there. Given that, compilation is as simple as

    lualatex poster.tex

Given the dependence on fontspec, compiling with pdflatex will not work. If lualatex is not available, remove the fontspec dependence and default to the helvetica-based sans-serif fonts below it; it will compile, though it won't be too pretty.

--------------------

Created by Emilio Pisanty, 2017-09-20, based on existing ICFO materials
