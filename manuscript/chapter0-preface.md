# Preface

No more hacks to create layouts, no more floats, no more tables. Finally, laying out things with CSS feels right.

## Book overview

In *Chapter 1* we will ....

In *Chapter 2* we will learn ...

In *Chapter 3* we will explore ....

## How to read this book

Every chapter of the book opens with a list of bullet points of important concepts. Each bullet point is then explored in detail through the chapter. You may find the book very dry in nature, so may want to take breaks while reading. Although you may want to read chapters out of order, or just skim through the chapters, please don't. Please take your time, study each chapter slowly, and take breaks frequently if you find yourself unmotivated. The book is designed this way to serve as a reference so that you can refer to any time in the future. Also, keep in mind that the book is always up-to-date with the latest spec of the language, which is currently ES2015. I genuinely hope you get something out of the book, and please submit an issue if you don't understand something, or if you find a spelling error or a mistake in the code. The book is written in Markdown and is hosted in github: https://github.com/aminmeyghani/flexbox-book

Happy coding :)

## Requirements

In order to follow along with the book, you need the following:

- Google Chrome
- Node > 5
- A text editor (Sublime Text is recommended, but not necessary)

Below, you can find useful information about Chrome DevTools and installing Node. Since we will be using them throughout the book, please take the time to make sure that you have all of them set up.

### Using Chrome DevTools

In order to open the DevTools, just right click on the page, and choose `inspect`. This will open up the Chrome DevTools.

![Using the Console](images/1-using-the-console.png)

### Installing Node

Node is a JavaScript run-time that you can use to execute JavaScript scripts. The easiest way to install and manage Node is with [nvm](https://github.com/creationix/nvm). You can use the following to install NVM:

```bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash
```

After that, make a new terminal and make sure that `nvm` is installed with `nvm --version`. If you don't get any output, try adding the following to your `~/.bash_profile` file:

```bash
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh
```

After NVM is installed, you can use it to install any Node version that you need. For example, to install the latest version 5, run:

```bash
nvm install 5
```
That's it! Now, if you want to set this version as your machine default, run the following:

```bash
nvm alias default 5
```

Now that you have Node installed, you can execute Node scripts. For example, make a file on your desktop called `script.js`:

```bash
touch ~/Desktop/script.js
```

Then add the following to the file:

```javascript
console.log('hello world');
```

Then execute the script with `node ~/Desktop/script.js` and you should see the output in the terminal. That's it.

**TODO**

### Setting up Dev Environemnt

You can follow along or just clone this template.

**TODO**

