# Anagram with Ajax
Vocabulary anagrams game for primary school English language learners (ELL)

## Overview

A simple anagram game designed for English-language learning students in elementary and middle school. Students are presented with a list of vocabulary words (taken from a text file) and an anagram. The anagram is a jumble of some number of vocabulary words, randomly chosen. Students attempt to type words that can be created from the jumble. When a matching word is typed, it is added to a list of solved words. 

The vocabulary word list is fixed for one invocation of the server, so multiple students connected to the same server will see the same vocabulary list but may  have different anagrams.


# Tasks

* Familiarize yourself with flask_vocab.py and flask_minijax.py by running them separately. You need to understand them to do this project.

* Your task is to replace the form interaction (in flask_vocab.py) with AJAX interaction on each keystroke using flask_minijax.py. 

* You will write your own Dockerfile (see examples provided in prior projects). Dockerfile should be placed inside vocab folder.

* You will submit your credentials.ini in canvas. It should have information on how we should get your git repo (which should contain your Dockerfile). 

# Contributors
--------------
Initial version by M Young; Docker version added by R Durairajan; and Ronny Fuentes <ronnyf@uoregon.edu>

