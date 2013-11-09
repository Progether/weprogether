# README

## Synopsis

Culturally, we want to make everything related to the Progether project a
potential learning experience. It is in this vein that I have decided to make
the source for the progether website open to anyone who is interested in working
on it with me.

## Installation

Clone this repository to a web server. Please work using feature branches. This
means when you have a feature to add, create a branch for it, and make any
of your commits to it. The Workflow section goes into more detail on the exact
commands you will be using to do this. When you are prepared to submit your
final pull request for merging, you can do so from this feature branch. I will
then review the changes for merging into master. From there, they will be used
on the actual weprogether.com website!

## Workflow

As stated in the Installation section, we use a feature branch based workflow, like so:

```bash
git clone https://github.com/projectdelphai/weprogether.git
cd weprogether
git checkout gh-pages
git pull
git checkout -b <weprogether-yourfeaturebranchname>
make changes
git add <changed files>
git commit -m 'Useful, short message describing your most recent changes'
make changes
git add <changed files>
git commit -m 'Useful, concise message describing your changes since the last commit'
git push origin <weprogether-yourfeaturebranchname>
```

Once you have pushed to Github.com, log into Github.com and open a Pull Request from your feature branch TO THE GH-PAGES BRANCH, which I will review and either reject (with comments to help you fix any glaring issues), or merge into the gh-pages.

Easy peasy!

## License

Copyright (c) 2012 Michael J. Smalley

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
