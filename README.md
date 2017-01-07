# program-slides
Reveal.js stencil for program slides during a meetup.

## How to view

1. clone the repo.

  ````
  git clone <repo url>
  ````
2. checkout the meetup branch you would like to see the slides for.

  ````
  git checkout <YYYYMMDD>-<name>
  ````
3. open the index.html file in a browser.

## How to customize

1. clone the repo.

  ````
  git clone <repo url>
  ````
2. start a branch based of the master branch named `<YYYYMMDD of meetup>-<name or venue>`.

  ````
  git branch <YYYYMMDD>-<name>
  git checkout <YYYYMMDD>-<name>
  ````
3. customize the content in the index.html file.
4. push the branch to this repo.  

  ````
  git push -u origin <YYYYMMDD>-<name>
  ````

Customizations that could benefit future meetups can be committed to the master branch.
