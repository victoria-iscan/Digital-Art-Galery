# Digital-Art-Galery

## Description:
For this project I will pursue my passions of art and illustration, and create a digital interactive art gallery of some artwork I have created. Each piece of artwork will have an available description when clicked on the date that it was created and some tools I used to make it. To start I will use a previously made project on open processing as a base that I will build onto: https://openprocessing.org/sketch/1757184 


## Why?
I am motivated to do this project because it gives me an opportunity to be creative and have fun as well as express my passions, while learning more about computer science and programming.

## How?
I will incorporate the tools I learned from different projects throughout this course such as: creating images, creating buttons, creating different colors, making sounds, and making different screens. 

## Milestones
 Create the images on the walls in the project - Jan 4
 Make the images clickable - Jan 7
 Create a  description screen for each piece of artwork - Jan 15
 Final touches, colors, and sounds for buttons - Jan 20


## Pseudocode
let camera
let x
let y
let z
let rgb...
etc


function setup () {
Createcanvas (windowidth, windowheight)
createcamera

function draw() {
background (0)
camera position set (x, y, z)
makeimages()
makeframes()
box(1000, 1000)
fill(0)
stroke(255)
movearound();
paintingClicked();


if mouseX >100 {campan moveX()
}
if mouseX <100 { camtilt moveY() 
}}


function moveAround ()
if LEFT_ARROW = down {
moveleft}
else if RIGHT_ARROW = down {
moveright}


if DOWN_ARROW = down {
movedown}
else if UP_ARROW = down {
moveup}

if ENTER_KEY = down {
moveforward}
if SHIFT_KEY = down {
movebackward}


function preload{
image
image
image
image....
etc
}


function makeImages () {
image(20,30)
image(30,30)
image(40,30)
image(50,30)
image(60,30)....
etc


function makeFrames () {
box (20,30)
noFill()
box (30,30)
noFill()
box (40,30)
noFill()
box (50,30)
noFill()...
etc

function paintingClicked() {
if MouseX < 100 & mouseY >100{
sqaure (30, 30)
text("details about the drawing")
}
