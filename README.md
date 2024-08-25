# CBT-CIP

Project 1

Rock Paper Scissor Game

Welcome to the Rock-Paper-Scissors game! This is a simple implementation of the classic game using Python. It’s a fun way to practice your Python skills and understand the basics of game development and user interaction.

Features Player vs Computer: Play against the computer with randomly generated choices. Command-Line Interface: Simple and easy-to-use CLI for interaction. Replay Option: Option to play multiple rounds without restarting the game.

How to Play Run the Game: Execute the rock_paper_scissors.py script to start the game. Choose Your Move: Type one of the following commands when prompted: rock

paper scissors

View Results: The game will display the computer’s choice and the result of the round. Play Again: After each round, you’ll have the option to play again or exit the game. Requirements Python 3.x

Project 2

Creating Payment receipt using python

Payment Receipt Generator
This Python project creates a formatted payment receipt PDF using the reportlab library. The receipt includes details such as date, subscription type, and pricing, and is styled for clarity and professionalism.

Features
Generate PDF Receipts: Creates a PDF file with payment receipt details.
Customizable Styles: Apply various styles to the table and title for a professional appearance.
Easy Integration: Simple script that can be integrated or adapted for various use cases.

Requirements
Python 3.x
reportlab library

Code Overview
Data Definition: The DATA list contains the receipt details to be included in the PDF.
Document Template: Uses SimpleDocTemplate to define the PDF layout.
Styles: TableStyle and Paragraph are used to style the table and title.
Table Creation: The Table class formats and displays the receipt data.
PDF Generation: The pdf.build() method generates and saves the PDF document.

