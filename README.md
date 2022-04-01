# Dynamo Charlotte Compiler

This is a modified version for running .dc files from the Command Line Interface. For more information about the language check the https://github.com/jc-juarez/dynamocharlotte repository.

Dynamo Charlotte is a Python-based Interpreter that runs on Python Lex-Yacc Parser. It is a beginner friendly language with a syntax similar to Visual Basic and Python, allowing to create anything from numbers to multi-dimensional arrays. The goal of Dynamo Charlotte is to keep a simple coding syntax while still referring to fundamental aspects of programming such as Non-Dynammic Memory, Explicit Data Types and much more. An ideal First-Time Language for teaching kids and programming beginners who are interested in coding, allowing them to learn and dive into the amazing world of Software Engineering 👩‍💻👨‍💻.

How to Run Dynamo Charlotte
==========

*Requirements: 
Python 3.6+ installed.

Make sure you have Python 3.6+ installed and run the following command on your terminal:

```python
pip install dccompiler
```

Now in any directory you like create a **.dc** file. For example, here we create **HelloWorld.dc**:

```python
  Main<>
    print("Hello World!")
  End<>
```
And to execute your Dynamo Charlotte program run the Dynamo Charlotte Compiler in your terminal as follows:

```python
python -m dcc HelloWorld.dc
```

- **Make sure your .dc file does not have spaces in between its name.**

- **Check out more examples at the 'Code Examples' directory in this repository.**


