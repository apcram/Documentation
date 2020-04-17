# Documentation
Full documentation to come. 

~~**ap**cram strives to be a free, open-source, and crowdsourced (wiki-style) site that compiles student notes into comprehensive and concise study sheets. We are striving to offer notes for every AP subject. These notes strive to be living and dynamic notes. Every year, as the course syllabus changes, our notes will too. ~~

~~As with all open projects, documentation is necessary to ensure everybody stays on the same page. ~~

## Table of Contents

- [Documentation](#documentation)
  * [Table of Contents](#table-of-contents)
  * [Organizational Structure](#organizational-structure)
  * [Contributing](#contributing)
  * [Site Structure](#site-structure)
  * [Theme Changelog](#theme-changelog)
  * [To-Do](#to-do)

## Organizational Structure
~~We are community-run and community-supported. Every course will be assigned an **editor team** that is in charge of compiling and editing content. These teams will consist of students who have mastered the material and course, as well as undergraduates who are currently studying in the respective field (and teachers who are teaching the course, if possible).~~

~~A list of editor teams are here. [WIP]~~

## Contributing
~~Students who have taken the respective courses and/or exams may submit their notes to the respective editor teams who will compile, combine, and synthesize notes to create the  review sheets. Contributors will be attributed as *major* or *minor* contributors depending on how much of their notes were appropriated and used. ~~

## Site Structure
Currently, the site is hosted on GitHub Pages with Jekyll (running the Doks theme). The main site and the course page is hosted in the repo `apcram.github.io`, course pages are hosted within their individual repositories (with a copy of the theme). 

The `template` repo can be forked to create a page of the individual course. Please name this fork the name of the path you wish for the course to have. This is usually the name of the course without 'AP' delimited using dashes. Longer names can be shortened/abbreviated as deemed fit. Please name courses so that there will be no ambiguity (there are multiple English courses). For example, `physics-c-mechanics`, `us-history`, `us-government`, `spanish-literature`. 

These will show up as `https://apcram.github.io/physics-c-mechanics`, etc... Edit the `index.md` files and additional files as deemed fit to create the individual course page. 

For site-wide design changes, change `doks-theme` in the `template` and `apcram.github.io` first, then copy across individual subjects. [WIP - this needs to be streamlined. Looking into Git Hooks.]

Documentation on how to use the theme can be found [here](https://doks.themejack.com/). 

## Theme Changelog
The following have been changed from the stock theme: 
 - Colors have been tinkered with. 
 - There is a separate variable for site titles (only in the main page, not in courses). 
 - `.hero-subheader-compressed` is a version of `.hero-subheader` that is narrower. 
 - `homepage` layout includes nav bar, `landing` layout does not, `courses` layout includes a list of all courses. 

## To-Do
A lot...
 - [ ] Create links and repositories for every course. 
 - [ ] Create a system that can propogate theme changes to every repository. 
 - [ ] Write about pages, and general guide articles. 
 - [ ] Complete guide on contributing content. 
 - [ ] Recruit contributor and editor teams. 
