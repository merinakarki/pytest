# pytest
![image](https://user-images.githubusercontent.com/91168990/144521810-075ecdf5-ab23-4d1a-bd5d-f45fa04d66d5.png)

What Is Pytest
pytest is the framework that makes it easy to write, test, and scale to support complex testing for the applications and libraries. It is the most popular Python package for testing. The basis for a rich ecosystem of testing is plugins and extensions.

The way pytest is designed is as a very extensible system, easy to write plugins and there are a lot of plugins present in the pytest that are used for various purposes. Testing is very important before delivering the code in production.

It is a mature full-featured Python tool that helps to write better programs.


Features Of pytest
Does not require API to use.
Can be used to run doc tests and unit tests.
Gives useful failure information without the use of debuggers.
Can be written as a function or method.
Has useful plugins.


Advantages Of pytest
It is open-source.
It can skip tests and automatically detect the tests.
Tests are run parallel.
Specific tests and subsets of tests can be run from the program.
It is easy to start with as it has a very easy syntax.

How To Install pytest In Linux

Make a directory with a name suitable for you in which the Python files will take place.

Make a directory using the command (mkdir <directory name>).
Make a virtual environment, in which the installation of specific packages will take place rather than in the whole system.
Run: `pip install -U pytest` or `pip install pytest` (make sure that the pip version should be the latest).

![image](https://user-images.githubusercontent.com/91168990/144522811-204b51b5-a570-4be0-ba6c-a299dd5104aa.png
  
How To Use Pytest Using Python  
Create a Python file with the name `helper_function.py`.
Add the basic Python functions to it as below.

  
![image](https://user-images.githubusercontent.com/91168990/144527711-02d7c89b-4584-496d-8a4f-039772c480fd.png)

In the above example, the function selects a random adjective from a list of adjective strings and a list of nouns from a list of noun strigs and combine 
them together separated by a space.
Now, it’s time to perform automatic testing using pytest.
pytest expects the test file name to be in the format: ‘*_test.py’ or ‘test_*.py’
Add the following code in that file.
  
![image](https://user-images.githubusercontent.com/91168990/144522868-046d08f0-bb58-4c47-ad8f-dc4ad6d7f8dd.png)

In order to run the test functions, remain in the same directory, and run the `pytest`, `py.test`, `py.test test_func.py` or `pytest test_func.py`.
In the output, you will see all that the test cases are passed successfully.

