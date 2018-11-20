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

## Slides

[The slides](https://github.com/qaware/code-design-2018/blob/master/Slides.odp) contain some code snippets useful for presenting before the steps and provide some guidance.

## Helpful links for development

* Phaser API documentation: https://phaser.io/docs/2.6.2/index
* JavaScript documentation: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference

# Learning steps

1. Setup empty Phaser project, start webserver, open game in browser (`git checkout step-1`)
1. Add racket to game (non-movable) (`git checkout step-2`)
1. Make racket move with cursor keys (left / right) (`git checkout step-3`)
1. Add ball to game (non-movable, over racket) (`git checkout step-4`)
1. Make ball move and bounce of edges (`git checkout step-5`)
1. Make ball bounce of racket (`git checkout step-6`)
1. Make ball fall out of bottom (`git checkout step-7`)
1. Implement reset of ball if it falls out of bottom (`git checkout step-8`)
1. Add bricks (`git checkout step-9`)
1. Implement brick destruction if ball hits brick (`git checkout step-10`)
1. Add counter for destroyed bricks and lives (`git checkout step-11`)
1. Implement game over if lives reaches 0 (`git checkout step-12`)
1. Implement new level if all bricks have been destroyed (`git checkout step-13`)
1. Implement power ups (`git checkout step-14`)
1. Implement that the ball is hold until player moves the racket (`git checkout step-15`)
1. Implement ball spin - when moving the racket while the ball hits, the ball should get momentum (`git checkout step-16`)
