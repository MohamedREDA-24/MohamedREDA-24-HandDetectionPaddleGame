# MohamedREDA-24-HandDetectionPaddleGame
This project implements a hand-tracking-based paddle game using OpenCV and the cvzone library. The game captures live video feed from the webcam and uses a hand detector to track the player's hand movements, which are used to control a virtual paddle (bat). The goal is to bounce a ball with the paddle to score points. The game ends when the ball touches the bottom of the screen, displaying a "Game Over" screen with the final score. Players can restart the game by pressing 'R' or quit by pressing 'Esc'.

Key features:

Hand tracking using the cvzone.HandTrackingModule.
Paddle control based on hand position.
Scoring mechanism and ball physics.
Game Over screen with options to restart or quit.
