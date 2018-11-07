# Code for the Code+Design workshop 2018 at QAware Munich
This repository contains the code for the Code+Design workshop, which takes place on November at [QAware](https://www.qaware.de/) in Munich.
The goal is to create a breakout clone.

![Screenshot](https://raw.githubusercontent.com/qaware/code-design-2018/master/screenshot.png)

## Required software

* `npm -g http-server`
* Texteditor of your choice. I used [Visual Studio Code](https://code.visualstudio.com/).

## Running

* `http-server .`
* Open brower at http://localhost:8080/

## Helpful links for development

* Phaser API documentation: https://phaser.io/docs/2.6.2/index
* JavaScript documentation: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference

# Learning steps

1. Setup empty Phaser project, start webserver, open game in browser
1. Add racket to game (non-movable)
1. Make racket move with cursor keys (left / right)
1. Add ball to game (non-movable, over racket)
1. Make ball move
1. Make ball bounce of edges
1. Make ball bounce of racket
1. Make ball fall out of bottom
1. Implement reset of ball if it falls out of bottom
1. Add bricks
1. Implement brick destruction if ball hits brick
1. Add counter for destroyed bricks and lives
1. Implement game over if lives reaches 0
1. Implement new level if all bricks have been destroyed
1. Implement power ups
