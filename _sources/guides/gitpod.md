# 🎧 Gitpod

## What is Gitpod?
* Gitpod is based on git, a software for tracking changes, just like the software for Github. 

## Why not just use GitHub?
The goal of using Gitpod is to edit code locally on your own computer, so you can make a bunch of changes all at once. This is much easier than making lots of separate pull requests on GitHub. 

How to use Gitpod?
You can go to view port (show a screenshot) via browser or embedded preview to check your work and make sure your edit worked (after saving your work with command S).

We inspected the element (right click or open developer tools to inspect element) and this confirms whether “. . .” changed to “...” (which was hard to tell without inspecting since it looked the same).

## DIY

1. Go to https://gitpod.io/#https://github.com/jupyterlab/jupyterlab
2. Make a fork copy of the code, using the git icon
3. Change branch name to save your own copy "Checkout branch" in the "command palette" which you can access with CMD SHIFT P
4. On the bottom it says Open Ports, which you can use to preview changes to open on the side or in a new browser. It takes a while to start up, so if there are no open ports, just wait.
5. search click ... for more options, then look for files ending in.ts typescript to only show files written in code as opposed to .md markdown or something else
6. make your change to the code, save your code, and reload/refresh the preview to see if it was right
7. press the + to stage the change (like a draft), add a message, then commit by pressing check mark, which saves your changes with a name
8. it's still just on gitpod so to move it to github to share with other people, then you have to push the change. 
9. Go to github, open a pull request for your branch, to suggest your changes. There is usually a link that pops up to suggest you to open one.

If you want to make another change on the same pull request, repeat 6-8


To start a new pull request, or to switch to some other work:

Command Palette: Open with CMD SHIFT P: https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette
command shift p is to open a file
command > is to run commands like >push or commity


## Terms:
* String is a clause of normal text instead of being interpreted as code. Something written as a string would be in either single quotes like ‘example’ or double quotes like “example” (it usually doesn’t matter if you use single or double quotes unless you have a real quoted phrase within the string).
* Ts is for type script a type of file ending similar to JavaScript
* trans is something you’ll see in the code a lot and it means it’s to translate that word into another language.
* Json is a way of storing data, like a mini programming language.

```shell
jupyter-book build .
python -m http.server --directory _build/html/
```