# Introduction to Electrical Circuits

Jupyter book is available on github.io [here](https://hrstnikolov.github.io/2023-cicuits/intro.html).

Lecture notes and exercises on Dr. Ravel Ammerman's course "EGGN 281 Introduction to Electrical Circuits". The lecture videos are available for free in [Youtube](https://www.youtube.com/watch?v=IRgZ-puZjfA).

### Update procedure

To update the book, run the following commands:

In the parent of the local repository:  
`conda activate ENVNAME`  
`jb build 2023-cicuits`  

Then, in the local repositor (containing the `.git` folder):  
`git add, commit and push`  
`ghp-import -n -p -f _build/html`  