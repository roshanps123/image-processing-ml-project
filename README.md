This project involves solving two distinct yet interconnected problems using Python, focusing on the Tower of Hanoi puzzle and audio processing of brick sounds to determine their quality. The solutions are implemented with specific requirements and visualization techniques.

Problem 1: Tower of Hanoi
Objective:

Write a Python code to calculate the number of steps required to solve the Tower of Hanoi puzzle for a given number of disks.
Rules:

Only one disk may be moved at a time.
Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or an empty rod.
No disk may be placed on top of a smaller disk.
Visualization:

Display the result on a custom width Dot Matrix Display.
Each dot is a circular disc (25-pixel radius), arranged in a 300px height grayscale image.
Bonus: Solve the Cyclic Hanoi variation.
Problem 2: Brick Sound Quality Analysis
Objective:

Write a Python program to analyze audio files of brick sounds and evaluate their quality as either high (metal-like sound) or low (cardboard-like sound).
Process:

Convert audio files to spectrograms using windowed Fourier transforms.
Use libraries like librosa to load audio, compute the mel spectrogram, and transform it to a decibel scale.
Evaluation:

High-quality bricks add 1 to a running sum, and low-quality bricks add 2.
Display this sum creatively on the previously created dot matrix display, using RGB values.
Key Features
Tower of Hanoi Solver:

Recursive function to calculate moves.
Visual representation using a Dot Matrix Display.
Audio Processing:

Use of librosa for audio analysis.
Spectrogram generation and interpretation.
Visualization:

Custom Dot Matrix Display for results.
RGB pixel manipulation for creative output.
This project combines algorithmic problem-solving with audio signal processing and creative visualization, providing a comprehensive learning experience in Python programming and data representation.
