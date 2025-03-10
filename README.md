# natural-language-processing-project
# Unit 6 - Natural Language Processing Project

## Introduction

Natural language processing (NLP) is used in many apps and devices to interact with users and make meaning of text to determine how to respond, find information, or to create new text. Your goal is to use natural language processing techniques to identify structure, patterns, and meaning in a text to have conversations with a user, execute commands, perform manipulations on the text, or generate new text.

## Requirements

Use your knowledge of object-oriented programming, ArrayLists, the String class, and algorithms to create a program that uses natural language processing techniques:

- **Create at least two ArrayLists** – Create at least two ArrayLists to store the data used in your program, such as data from text files or entered by the user.
- **Implement one or more algorithms** – Implement one or more algorithms that use loops and conditionals to find or manipulate elements in an ArrayList or String object.
- **Use methods in the String classs** - Use one or more methods in the String class in your program, such as to divide text into sentences or phrases.
- **Use at least one natural language processing technique** – Use a natural language processing technique to process, analyze, and/or generate text.
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions.

## UML Diagram

Put and image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one word, otherwise it might not properly get display on this README.

![UML Diagram for my project](UML.png)

## Video

Record a short video of your project to display here on your README. You can do this by:

- Screen record your project running on Code.org.
- Upload that recording to YouTube.
- Take a thumbnail for your image.
- Upload the thumbnail image to your repo.
- Use the following markdown code:

[![Thumbnail for my projet](thumbnail.png)](https://youtu.be/uBkdr9dOT8s)

## Project Description

Our NLP project's goal is to find the frequency of a keyword in a list of reviews to a restaurant called Sugarfish. The user types a keyword, and the program find how manny times the keyword is shown in the text file that consists of a list of the reviews. In addition to the frequency, the program prints out all the reviews with the specific keyword. 

## NLP Techniques

Nicole and I used the NLP, keyword frequency counting. The program gets all the words in reviews.txt, and extract the word that is inputted by the user. The countKeyword() method is essential to reach this goal, as the program iterates through every word in reviews.txt and increases the count when a word matches the keyword inputted by the user. This is necessary in NLP technique because it allows the user to find keywords and search for specific reviews with ease and efficiency.