---
content_type: page
title: Projects
uid: ce7d4f4a-59ad-4d14-4592-be7641ff9daf
---

Project 1 – Hangman
-------------------

Project 1 ([PDF]({{< baseurl >}}/resources/project1)) was the game of Hangman. The handout guides you through the process. This process is called _incremental programming_. It allows you to tackle complex problems, like writing a game of Hangman, by tackling small sub-tasks first. In this case, we can tackle the problems of figuring out whether the user has guessed the word, or creating a string of the word with the letters guessed so far. With the sub-tasks taken care of, it's easier to take on the bigger task.

Optional project files: word list ([TXT](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/projects/word_list.txt)) contains many words; hangman\_lib.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/projects/hangman_lib.py)) contains helper functions to get a random word and to print a Hangman image; hangman.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/projects/hangman.py)) contains example usage of hangman\_lib.

Example solution: hangman\_soln.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/projects/hangman_soln.py)) (needs to be in same directory as above files)

Project 2 – Guitar Hero Clone
-----------------------------

Project 2 was a clone of the game of Guitar Hero. This is a decently complex game, and trying to do it all at once is not practical. Instead, we learn the importance of _modularity_ and _teamwork_ by breaking up the functional parts of the game (input, graphics, sound and logic) and completing these parts in teams. This approach even allowed us to have a working, playable prototype at the end of class, despite being incomplete.

Note: this project could not be included in MIT OpenCourseWare due to copyright restrictions.

Sample Program 1 – Tic-Tac-Toe
------------------------------

Many of you asked for us to write a tic-tac-toe program as one of our sample programs. In the beginning of class 6, Mihir wrote such a program in front of you all. The goal of that program was to be simple and straightforward, and it was successful.

I've written another version, with a different goal: to be polished. My implementation is considerably different, and that's fine; we all have different styles of programming. Take a look. It's extensively commented, but feel free to email with questions.

File: tictactoe.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/projects/tictactoe.py))

Sample Program 2 – Connect Four
-------------------------------

Here's another sample program with the goal of being polished. This is a great example where the implementation is not trivial (unlike in Tic-Tac-Toe), so abstraction is vital to prevent bugs and to keep the code readable.

There are some Python things in the code that you may not know yet. The assert statement just throws an error if the following condition isn't True. Writing a string with the % symbol lets you plug in the variables that follow into that spot in the string (%s means string, %i means integer and %c means one letter).

So take a look. It's not quite so extensively commented as the Tic-Tac-Toe program, so feel free to email me with questions.

File: connectfour.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/projects/connectfour.py))