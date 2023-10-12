
#  Quiz Game{Python Game}
Here's a brief description of your Python quiz game:

The game consists of four Python files: `main.py`, `question_model.py`, `quiz_brain.py`, and `data.py`.

1. **`data.py`**: This file contains a list of dictionaries, where each dictionary represents a question. Each dictionary has two keys: "text" (the question itself) and "answer" (the answer to the question, which is either "True" or "False").

2. **`question_model.py`**: This file defines a class called `Question`. The `Question` class has an initializer method that takes two parameters: `text` and `answer`. These parameters are used to set the `text` and `answer` attributes of a `Question` object.

3. **`quiz_brain.py`**: This file defines a class called `QuizBrain`. The `QuizBrain` class has several methods:
   - An initializer method that takes a list of questions and initializes the `question_number`, `score`, and `question_list` attributes.
   - A method called `still_has_questions()` that checks if there are still questions left in the quiz.
   - A method called `next_question()` that displays the next question to the user and checks their answer.
   - A method called `check_answer()` that checks if the user's answer is correct, updates the score if it is, and provides feedback to the user.

4. **`main.py`**: This is the main script that runs the game. It imports the necessary classes and data, creates a list of `Question` objects based on the data, creates a `QuizBrain` object with this list of questions, and then runs the quiz by repeatedly calling the `next_question()` method until there are no more questions left. Finally, it prints out the user's final score.

The game is a simple True/False quiz where users are asked questions and must respond with either "True" or "False". Their score is tracked throughout the game, and their final score is displayed at the end. The game continues until all questions have been asked.
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![quiz](https://github.com/Sookchand/Quiz-Game/assets/34344439/a87f0e11-4504-4f3e-8522-77ba9d86c4b0)



## Tech Stack
The quiz game is built using Python, which is a high-level, interpreted programming language. Python is known for its simplicity and readability, which makes it a great choice for beginners as well as experienced developers.

The game uses basic Python concepts such as:
- **Classes and Objects**: The `Question` and `QuizBrain` classes are defined with their respective attributes and methods. Instances of these classes are created in the main script.
- **Loops**: A while loop is used in the main script to keep asking questions until there are none left.
- **Conditionals**: If-else statements are used to check the user's answers and update the score accordingly.
- **Lists**: A list is used to store all the question objects.
- **Dictionaries**: Each question and its answer are stored as a dictionary in the `data.py` file.

No other technologies or libraries were used in this game. It's a simple console-based game that runs on pure Python. It doesn't have a graphical user interface, so it runs in the terminal or command prompt. The user interacts with the game by typing their answers into the console. The game then prints out the next question or the final score, depending on whether there are any questions left.
## Documentation
Sure, here are the official Python documentation for the technologies you used in your quiz game:

1. **Python**: General Python documentation can be found at [Python.org](^1^) or [Python 3.12.0 documentation](^2^).

2. **Classes and Objects**: Documentation on Python classes and objects can be found in the [Python 3.12.0 documentation](^4^) and at [W3Schools](^6^).

3. **Loops**: Documentation on Python loops can be found in the [Python 3.12.0 documentation](^10^) and at [Codecademy](^12^).

4. **Conditionals**: Documentation on Python conditionals can be found in the [Python 3.12.0 documentation](^10^) and at [freeCodeCamp.org](^15^).

5. **Lists**: Documentation on Python lists can be found in the [Python 3.12.0 documentation](^18^) and at [Google for Developers](^19^).

6. **Dictionaries**: Documentation on Python dictionaries can be found in the [Python 3.12.0 documentation](^18^) and at [Real Python](^22^).

These resources should provide comprehensive information about these Python concepts.

Source: Conversation with Bing, 10/12/2023
(1) Our Documentation | Python.org. https://www.python.org/doc/.
(2) Python 3.12.0 documentation. https://docs.python.org/.
(3) 9. Classes — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/classes.html.
(4) Python Classes and Objects - W3Schools. https://www.w3schools.com/python/python_classes.asp.
(5) 4. More Control Flow Tools — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/controlflow.html.
(6) Python | Loops | Codecademy. https://www.codecademy.com/resources/docs/python/loops.
(7) 4. More Control Flow Tools — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/controlflow.html.
(8) How to Use Conditional Statements in Python - freeCodeCamp.org. https://www.freecodecamp.org/news/how-to-use-conditional-statements-if-else-elif-in-python/.
(9) 5. Data Structures — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/datastructures.html.
(10) Python Lists | Python Education | Google for Developers. https://developers.google.com/edu/python/lists.
(11) 5. Data Structures — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/datastructures.html.
(12) Dictionaries in Python – Real Python. https://realpython.com/python-dicts/.
(13) The Python Tutorial — Python 3.12.0 documentation. https://docs.python.org/3/tutorial/index.html.
(14) Built-in Types — Python 3.12.0 documentation. https://docs.python.org/3/library/stdtypes.html.
(15) inspect — Inspect live objects — Python 3.12.0 documentation. https://docs.python.org/3/library/inspect.html.
(16) Object Oriented Programming in Python: Defining Classes. https://redirect.cs.umbc.edu/courses/671/fall12/notes/python/07python_classes.pdf.
(17) Python Classes and Objects - Notes for Python Application ... - Studocu. https://www.studocu.com/in/document/visvesvaraya-technological-university/python-application-programming/python-classes-and-objects/31082212.
(18) Chapter 5 - Loops — Python 101 1.0 documentation - Python Library. https://python101.pythonlibrary.org/chapter5_loops.html.
(19) ForLoop - Python Wiki. https://wiki.python.org/moin/ForLoop.
(20) 6. Expressions — Python 3.12.0 documentation. https://docs.python.org/3/reference/expressions.html.
(21) If Statements and Chained Conditionals in Python 3 - Linode. https://www.linode.com/docs/guides/if-statements-and-conditionals-in-python/.
(22) How To Write Conditional Statements in Python 3 | DigitalOcean. https://www.digitalocean.com/community/tutorials/how-to-write-conditional-statements-in-python-3-2.
(23) Python List (With Examples) - Programiz. https://www.programiz.com/python-programming/list.
(24) Working with Lists — Python Beginners documentation - Read the Docs. https://python-adv-web-apps.readthedocs.io/en/latest/lists.html.
(25) Python Dictionaries - W3Schools. https://www.w3schools.com/python/python_dictionaries.asp.
## Lessons Learned
Building this quiz game in Python can provide several valuable lessons:

1. **Understanding of Python Basics**: This project helps reinforce understanding of Python basics such as variables, loops, conditionals, lists, and dictionaries.

2. **Object-Oriented Programming (OOP)**: The game uses classes and objects, which are fundamental concepts in OOP. This can help you understand how to design and use classes in Python, and how objects can interact with each other.

3. **Data Structures**: The game uses lists and dictionaries to store questions and answers. This can help you understand when and how to use these data structures effectively.

4. **Code Organization**: The code for the game is split across multiple files, each with a specific purpose. This can help you understand how to structure and organize code in a larger project.

5. **Problem Solving**: Building a game like this requires problem-solving skills to figure out how to implement the game logic, keep track of the score, and determine when the game should end.

6. **User Interaction**: The game interacts with the user through the console, taking input and providing output. This can help you understand how to handle user input and provide appropriate feedback.



# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.
