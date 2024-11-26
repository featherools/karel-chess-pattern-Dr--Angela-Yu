# karel-chess-pattern-Dr--Angela-Yu
#Here's a short description under 340 characters:  ---  This project uses Karel the Robot to create a chessboard-like pattern by placing beepers in alternating squares. It’s part of "The Complete 2024 Web Development Bootcamp"by Dr. Angela Yu, where we learn programming concepts through fun challenges like this one.

#code below

# Challenge: Create a chessboard-like pattern using Karel the Robot
# Platform: Stanford Karel IDE (https://stanford.edu/~cpiech/karel/ide.html)
# Project: Solution for the chess-like pattern challenge

# Course Reference:
# This code is inspired by and developed as part of the course 
# "The Complete 2024 Web Development Bootcamp" by Dr. Angela Yu, 
# Developer and Lead Instructor.

# Code:
function main() {
    // your code here
    putBeeper();
    moveLikeAHorseAndFartLikeJaadu();
    moveLikeAHorseAndFartLikeJaadu();
    walkHalfRow();
}

function moveLikeAHorseAndFartLikeJaadu() {
    move();
    move();
    putBeeper();
    move();
    move();
    putBeeper();

    turnLeft();
    move();
    turnRight();

    turnAround();
    move();
    putBeeper();

    move();
    move();
    putBeeper();

    move();
    turnLeft();

    turnAround();
    move();
    putBeeper();

    turnRight();
}

function walkHalfRow() {
    move();
    move();
    putBeeper();
    move();
    move();
    putBeeper();
}
