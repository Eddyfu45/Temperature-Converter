# Temperature Converter
The purpose is to create a temperature converter from Celsius to Fahrenheit and vice versa.

## Table of Contents
* [General Info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Issues](#issues)

## General Info
The overall objective was to create a way to convert temperature between Fahrenheit and Celsius. It was to practice using callback functions and other DOM elements to implement form to retrieve and utilize user input.


## Technologies
* Javascript
* Html
* Css

## Setup
To run this project:
* Create/login to your Github account
* Go on (github repository)
* Click "Fork" on the top right
* Click "Clone" and copy to clipboard
* Open up your coding terminal and clone it into your local repository

## Issues
I had some problems writing the syntax to call the data from user input and use it in the functions properly so I'm just doing this on the solution code that was provided in class for now until I fix it later.

# Image Test
// puts the image
![test](test.png)

# Code Snippet Test
// puts a code snippet

```
function colorizeDisplay(temp, units) {
  const display = document.querySelector('#display-result')

  if (units === 'c-to-f') {
    if (temp > 212) {
      display.style.background = 'red'
      display.style.color = 'white'
    } else if (temp < 32) {
      display.style.background = 'blue'
      display.style.color = 'white'
    } else {
      display.style.background = ''
      display.style.color = ''
    }
  }
  ```