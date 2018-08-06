Create a Travis file:

```yml
sudo: required
services: docker
script:
  - docker pull miktex/miktex
  - docker run -ti -v --mount src=$TRAVIS_BUILD_DIR/lesson-01-basics/doc/,target=/usr/src/tex,type=bind miktex/miktex pdflatex handout.tex
  
  docker run -ti -v miktex:/miktex/.miktex -v `pwd`:/miktex/work miktex/miktex pdflatex handout.tex.tex
```  
