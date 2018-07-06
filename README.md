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
