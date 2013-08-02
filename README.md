PyCubic
=======

A Python interface for cubic graphs manipulation

<img src="PyCubicIcon.png" />

Practical Studies team project at INSA of Rennes, PyCubic is developed for mathematicians working with cubic graphs theory.

What does it do ?
-----------------
PyCubic is able to display, manipulate and edit cubic graphs, by opening graph6 or GraphML files.
You can create, save and load graph layouts, or just apply some layout algorithms to compute an automated representation of the graph.
Then, you can save your edited graphs in graph6 or graphML format, and export them as PDF, PS, SVG and PNG files.


Run the application
-------------------
```sh
$ python run.py
```

    
Prerequisites and installation
------------------------------
* Python 2.7+: http://www.python.org/download/releases/2.7.5/ (should already be installed under Unix)
* nauty and Traces programs: http://cs.anu.edu.au/~bdm/nauty/
* graph-tool library: http://projects.skewed.de/graph-tool/
    
Example for Debian, DISTRIBUTION being replaced by squeeze or sid:
```sh
$ apt-get install nauty
$ vim /etc/apt/sources.list
# Add the following lines, replacing DISTRIBUTION
deb http://downloads.skewed.de/apt/DISTRIBUTION DISTRIBUTION main
deb-src http://downloads.skewed.de/apt/DISTRIBUTION DISTRIBUTION main
# Save file
$ apt-get update
$ apt-get install python-graph-tool
```
    
Example for Ubuntu, DISTRIBUTION being replaced by raring, quantal, precise, oneiric, natty or maverick:
```sh
$ apt-get install nauty
$ vim /etc/apt/sources.list
# Add the following lines, replacing DISTRIBUTION
deb http://downloads.skewed.de/apt/DISTRIBUTION DISTRIBUTION universe
deb-src http://downloads.skewed.de/apt/DISTRIBUTION DISTRIBUTION universe
# Save file
$ apt-get update
$ apt-get install python-graph-tool
```
  
Documentation
-------------
Technical documentation in HTML format is available by opening the file doc/index.html in your favorite web browser.


Authors
-------
Gwenegan HUDIN ( https://github.com/Gweylorth )

Nicolas BUSSENEAU

Note
----
This project was originally hosted on SourceForge : https://sourceforge.net/projects/pycubic/

Feel free to check our progress through the project there, or download a tar.gz of our latest release.


Legal mentions
--------------
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.

Copyright 2013, Gwenegan HUDIN and Nicolas BUSSENEAU
