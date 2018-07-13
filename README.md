# slide-template

Generally you can try these out with:

* git clone https://github.com/c-ale/c-ale-common.git
* git clone https://github.com/c-ale/c-ale-slide-template.git
* cd c-ale-slide-template
* make slides
* evince c-ale-slide-template-SLIDES.pdf

However to make your own set of slides do the following:

* git clone https://github.com/c-ale/c-ale-common.git
* git clone https://github.com/c-ale/c-ale-slide-template.git
* mv c-ale-slide-template my-talk
* cd my-talk
* mv c-ale-slide-template.tex my-talk.tex
* sed -i 's/c-ale-slide-template/my-talk/g' my-talk.tex
* make veryclean slides
* evince my-talk-SLIDES.pdf

There is a document <a href="https://cm.c-ale.org/Docs/C-ALE_talkware.pdf">here</a>
which explains how to use the latex language used here.

You will want to replace the example chapters in this slide
deck with your own material.

You will also need some packages installed to be able to
build your slide deck.

On CentOS, Fedora or RHEL

* sudo dnf install make texlive

On Debian or Ubuntu:

* sudo apt install make texlive

On openSUSE

* sudo zypper install make texlive

