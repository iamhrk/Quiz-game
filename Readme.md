# A Quiz Program 💭 using Python OOPs Concepts

- **_data.py_** - Contains a set of questions as list of dictionary. Each dictionary object has a question and answer key value pairs.

- **_Question_** class 
    
    Attributes

    - question 
    - answer 
- **_QuizBrain_** class

    Attributes
    - question_number - set to 0 initially as questions are asked from the beginning of the question list
    - question_list - list of question objects
    - still_has_questions() - check to see if there are still questions to be asked from the list
    - next_question() - asks questions one by one from the list and call check_answer() method
    -check_answer() - verify if the answer from user is correct or not.

>This python program uses the concepts of using classes and objects to compartmentalize the program.

>This is one of the projects I created during #100DaysOfCode 💻 Challenge.