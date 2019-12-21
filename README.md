# QuestionAnswer-Quiz-Generator

This program create questions and answers quiz based upon the dictionary.
You need to input the number of students. Questions and answers will be generated and added to `questions_dir` and `answers_dir`

### Run:

$ python quiz.py

### Output:

Creates `questions` and `answers` directory if doesn't exist.

```bash
$ python quiz.py 
Enter the number of students in exam (Number only): 5

Questions and Answers were created and added to questions and answers directories

$ ls -lR

total 16
drwxrwxr-x 2 navdeep navdeep 4096 Dec 21 13:58 answers
drwxrwxr-x 2 navdeep navdeep 4096 Dec 21 13:58 questions
-rw-rw-r-- 1 navdeep navdeep 3127 Dec 21 13:55 quiz.py
-rw-rw-r-- 1 navdeep navdeep  277 Dec 21 13:57 README.md

./answers:
total 20
-rw-rw-r-- 1 navdeep navdeep 291 Dec 21 13:58 capitalsquiz_answers1.txt
-rw-rw-r-- 1 navdeep navdeep 291 Dec 21 13:58 capitalsquiz_answers2.txt
-rw-rw-r-- 1 navdeep navdeep 291 Dec 21 13:58 capitalsquiz_answers3.txt
-rw-rw-r-- 1 navdeep navdeep 291 Dec 21 13:58 capitalsquiz_answers4.txt
-rw-rw-r-- 1 navdeep navdeep 291 Dec 21 13:58 capitalsquiz_answers5.txt

./questions:
total 40
-rw-rw-r-- 1 navdeep navdeep 4667 Dec 21 13:58 capitalsquiz1.txt
-rw-rw-r-- 1 navdeep navdeep 4684 Dec 21 13:58 capitalsquiz2.txt
-rw-rw-r-- 1 navdeep navdeep 4669 Dec 21 13:58 capitalsquiz3.txt
-rw-rw-r-- 1 navdeep navdeep 4684 Dec 21 13:58 capitalsquiz4.txt
-rw-rw-r-- 1 navdeep navdeep 4686 Dec 21 13:58 capitalsquiz5.txt
```
