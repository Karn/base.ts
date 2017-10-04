## Base.TS

An empty NodeJS application with a minimal TypeScript toolchain.


###### USAGE
The goal is to use the least amount of 3rd party libraries to begin using TypeScript.

You can start by doing a headless clone (a fork without actually forking). I.e copy the files from this repo into a local folder. This can be done via the following.
```sh
# Create a copy of this repository.
git clone --mirror https://github.com/Karn/base.ts.git

# Remove the tracking to this repo.
git remote rm origin
# Add the new tracked repo.
git remote add origin https://github.com/exampleuser/repo-name.git

# Update this branch to push and track the master branch.
git push -u origin master
``` 

First things first, run the `npm install` or `yarn install` command. This will install TypeScript and TSLint.

You can then being writing code within the `src` folder. When you are ready to build simply run `npm build` or `yarn build`. This process with lint and transpile your TypeScript code into JavaScript under the 'bin'.


###### LICENSE
```
MIT License

Copyright (c) 2017 Karn Saheb

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```