# About This Project

The website in this repository was developed at the request of the Department of Cognitive Science at Rensselaer Polytechnic Institute. It documents the _Minds & Machines_ course, including use of the WAR API and Connect 4 Moderator for final projects.

Wumpus-Arduino-Redux is an open-source hardware schematic and API, provided as an electrical and programming platform so that students may focus their efforts on the design of their robotic agent and their algorithmic solution to the "Wumpus World" problem rather than the low-level electrical engineering and computer science topics that such a robotics project requires.

This website was developed with the [hyde](https://github.com/hyde/hyde) static site generator and then deployed as html files. The SASS preprocessor builds `style.css` stylesheet using the included `*.scss` files. This project is licensed for free use and distribution, including modification.

```bash
# Build this site using hyde by running this bash from the top level directory.
# The resulting static files are put into the deploy/ directory.
$ sass content/assets/css/style.scss:content/assets/css/style.css --style compressed
$ hyde gen
$ hyde serve # optional, this command tests deploy on localhost:8080
```


## Project Members

* **Website** - Theodore X. Pak
  - <mail@theopak.com>
  - Rensselaer Polytechnic Institute Class of 2015
  - GitHub: theopak
* **[WAR API](https://github.com/AsherGlick/Wumpus-Arduino-Redux) Documentation** - Asher Glick
  - <glicka@rpi.edu>
  - Rensselaer Polytechnic Institute Class of 2013
  - GitHub: AsherGlick
* **[Connect 4 Moderator](https://github.com/Moomaster36/ConnectFourModerator) Documentation** - Dan Bulger
  - Rensselaer Polytechnic Institute Class of 2015
  - GitHub: daniel-bulger


## License

    Copyright (c) 2012, Theodore X. Pak et al., except as indicated
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:

    1. Redistributions of source code must retain the above copyright notice,
       this list of conditions and the following disclaimer.
    2. Redistributions in binary form must reproduce the above copyright notice,
       this list of conditions and the following disclaimer in the documentation
       and/or other materials provided with the distribution.

    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
    AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
    IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
    ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
    LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
    CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
    SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
    INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
    CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
    ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
    POSSIBILITY OF SUCH DAMAGE.
