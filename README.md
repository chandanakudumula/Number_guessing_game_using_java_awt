# java_project
In the Number guessing game, the computer program will come up with a random number within a range. The player (user) is asked to guess this number. If the player's guess is wrong, it displays in the textbox as the wrong number. Players can also use hints to guess the number but it decreases the score.
PACKAGES: This project is mainly based SWING and AWT(Abstract Window Toolkit). The packages used in this project are util,awt,javax.swing.
Java util package:  It contains the collections framework, legacy collection classes, event model, date and time facilities, internationalization, and miscellaneous utility classes (a string tokenizer, a random-number generator, and a bit array).We are using this project to generate the number for guessing.
Java AWT package Contains all classes for creating user interfaces and painting graphics and images. A user interface object such as a button or a scrollbar is called, in AWT terminology, a component.
Java Swing package: It is a part of Java Foundation Classes (JFC) that is used to create window-based applications. It is built on top of AWT (Abstract Windowing Toolkit) API and entirely written in Java.
Unlike AWT, Java Swing provides platform-independent and lightweight components.
The javax.swing package provides classes for java swing API such as JButton, JTextField, JTextArea, JRadioButton, JCheckbox, JMenu, JColorChooser, etc. We are using JButton , JLabel, and JTextField to implement this project.
DISPLAY: JButtons(Hint,score, check and cancel) are created to perform the event.
Labels(5) are used to display “enter the guessing number”,” Answer or Hint” and “enter hint number”, “number guessing game” and to display the image.
CODE LOGIC: Random() method is used to generate the guessing number. For Comparing the guessing number with the entered number, the If statement is used. And to calculate the score conditional statement is used. Hints are created by using Arithmetic operators. The first window pops up. The user has to enter the number in the given Text field. When the user clicks on the check button that displays whether the entered number is right or not. To get the hints user has to display the hint number in the respective text field. If the user uses more hints then the score decreases.  

