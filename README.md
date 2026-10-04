# SWE-quarto-thesis

**Updated October 2026:** I am submitting my (actual) thesis in the next couple of months. This template site has been updated to enable others to snatch it for their own work, and hopefully save themselves some time.

This is a small working example of quarto project to make a PhD thesis which broadly corresponds to the regulations regarding layout of a thesis submitted within the University of Edinburgh. It is **not official**, but conforms as best as possible to the regulation as detailed at:

[The University of Edinburgh Academic Services](http://www.ed.ac.uk/academic-services/students/thesis-submission)

Please use and alter the project to your own liking, but note that the code is made available under the GNU GPL and must be similarly licensed should you wish to release your modified version. 

An example of the rendered thesis is available [here](https://github.com/Straightbourne/SWE-quarto-thesis/blob/main/The-inside-of-a-ping-pong-ball.pdf).

I am grateful to other doctoral researchers who openly share their tools and techniques, including [Cameron Patrick](https://cameronpatrick.com/post/2023/07/quarto-thesis-formatting/) for sharing his approach to using quarto for his own thesis.

## How to use it

Clone the repository or download it to your own machine. You will need to have the software installed on your computer, so be ready to trouble-shoot that until you have a smooth writing workflow established. It's worth reading the code so you know what does what, but feel free to dive in an render the project with `quarto render` from the project directory.

**Software required** includes [`quarto`](https://quarto.org/docs/get-started/) and a decent writing studio or integrated development environment. I use [Visual Studio Code](https://code.visualstudio.com/). There's [a good tutorial on using VS Code with quarto](https://quarto.org/docs/get-started/hello/vscode.html). Don't be intimidated by the "AI code editor" bit, you can [switch that off](https://deepakness.com/raw/vs-code-hide-ai/). You don't need it for writing.

**Basic settings** like your name are included in the project configuration file `_quarto.yml`

**Write your thesis.** The chapters are in their own files, which you have to list in the `_quarto.yml` file to be included in the thesis output. Edit the included chapter files. 

**Table, figures and listings** are exemplified in chapter 1 (`10-introduction.qmd`).

**Acronyms:** this template uses Remy Chaput's [nice extension](https://github.com/rchaput/acronyms). Put your acronyms in the `acronyms.qmd` file, which uses a `yaml` paired structure.

**Index:** I include the mechanism for an index, commented out. It works, if you want to make the effort.

**The citation style file** included with this repository is modified. Use your favourite - there are lots in the [repository](https://github.com/citation-style-language/styles), or ask your supervisors if they have particular requirements. Set the path in `_quarto.yml`.

## LICENSE

Copyright (C) 2026 Nick Hood <nick.hood@ed.ac.uk>

The Quarto website and PhD thesis code is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

The Quarto website and PhD thesis code is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with Quarto website and PhD thesis template and The Unofficial University of Edinburgh LaTeX2e thesis template. If not, see <http://www.gnu.org/licenses/>.
