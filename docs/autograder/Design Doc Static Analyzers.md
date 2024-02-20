﻿<a name="br1"></a>**Code Assist Static Code Analyzers**

The **purpose** of this design document is to ensure the use and development of static code analyzers for the use in code assist

To ensure the quality and maintainability of Python code, various static code analyzers have

PyLint: PyLint is a widely used Python static code analyzer that checks code for potential bugs

Flake8: Flake8 is another popular Python static code analyzer that combines the functionality of

Bandit: Bandit is a security-focused Python static code analyzer that checks code for potential

Prospector is a Python static code analyzer that combines the capabilities of multiple tools into a

This is why I suggest the use should use PyLint for checking style issues and Bandit for

Tool Purpose Mypy Type checking PyLint Linting Flake8 Linting, style checking PyFlakes Linting




<a name="br2"></a>Above we can see the output for a sample submission for project 1, CS313E.

This is all done through the run\_autograder file within the assignment folders as depicted below.

From the sample tests we open the file and print each line:

A rating is displayed that may correspond to styling points. However, there are limitations and




<a name="br3"></a>Pylint and Bandit are two popular static code analyzers that can be used as autograders. Pylint

By incorporating both Pylint and Bandit into the autograder, instructors can ensure that student

The run\_autograder file is the main script that runs the autograder and generates the feedback

Overall, autograders are valuable tools for both instructors and students in computer science

**Pyreverse**

Pyreverse is an excellent tool that can make learning Python coding a lot easier and

For example, if you're just starting out in a programming course, codeassist might have you use




<a name="br4"></a>However, pyreverse can be expanded to advanced advanced programming courses or projects.

Pyreverse imay also help students compare designs after a project has been submitted and

Pyreverse is a great tool that can make learning and working with Python code more fun and




<a name="br5"></a>In additon a docker account is being set up to run autograder files faster based off base images.




<a name="br6"></a>**Next steps**

● Integrating the autograder with code assist and perhaps displaying html images instead

● Expanding the number of code analyzers to bandit and perspective

● Implement a way for students to download results and pyreverse output