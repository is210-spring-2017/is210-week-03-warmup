#####################
IS 210 Assignment #03
#####################
*************
Tasks
*************

:College: CUNY School of Professional Studies
:Course-Name: Software Application Programming I
:Course-Code: IS 210
:Lesson: 03

Overview
========

The warm-up tasks this week will focus on variables and operators. 

Instructions
============

The following tasks will  have you creating new scripts on the fly. 

.. important::

    In these exercises, you may, on occasion, come across a task that requres
    you to research or use a function or method not directly covered by the
    course text. Since Python is such a large language it would be impossible
    for the author to have included descriptions of each and every available
    function which would largely duplicate the offical Python documentation.

    A *vital* skill to successful programming is being comfortable searching
    for and using official language documentation sources like the
    `Python String Documentation`_ page. Throughout our coursework we will be
    practicing both the use of the language in practice and the search skills
    necessary to become functional programmers.

Tasks
=============

Task 01
-------


Specifications
^^^^^^^^^^^^^^

1.  Add the following line of code in a new Jupyter notebook

.. code:: pycon

    >>> RAVEN = 'quoth'
  

2.  After the line above, add a new line and assign a new value of ``Nevermore!`` to
    the ``RAVEN`` variable.

    .. note::

        Do not change the existing variable declaration. Add a new line
        instead.

Final Output (This should be your last line of code and produce the same result as what is shown below)
^^^^^^^^

.. code:: pycon

    >>> print (RAVEN)
    Nevermore!

Task 02
-------

Python's order of operations respects parentheses. Create a mathematical
statement in a single-line.

Specifications
^^^^^^^^^^^^^^

1.  In a new line on the same notebook, create a variable named ``WEEKS`` and, in a single statement:

    1.  Calculate the remainder of ``19`` divided by ``10``

    2.  Add the result to ``100``

    3.  Add that result to ``2^8`` (do exponentiation in Python!)

    4.  Divide all of the above by ``7`` 

Final Output
^^^^^^^^

.. code:: pycon

    >>> print (WEEKS)
    52

Task 03
-------

In this task, we'll perform a basic slice operation with a string.

Specifications
^^^^^^^^^^^^^^

1.  Add a new line of code in the same Jupyter notebook

.. code:: pycon

    >>> WILL_ROBINSON = 'Danger Will Robinson!'


2.  Use the *slice* syntax to slice the first ``7`` characters from the
    ``WILL_ROBINSON`` variable and assign the result into a new variable
    named ``KLAXON``

Final Output
^^^^^^^^

.. code:: pycon

    >>> print (WILL_ROBINSON)
    Danger Will Robinson!
    >>> print (KLAXON)
    Danger 


Task 04
-------

Next, we'll try repeating a string. 

Specifications
^^^^^^^^^^^^^^

1.  On a new line, use the string repetition operator to repeat ``KLAXON`` five
    times and save the result back into ``KLAXON``

.. hint::

    While not required to achieve this objective, you could use an *arithmetic
    assignment* operator to achieve this objective.

Final Output
^^^^^^^^

.. code:: pycon

    >>> print (KLAXON)
    Danger Danger Danger Danger Danger

Task 05
-------

The ``split()`` string function allows us to split a string according to a
specified delimiter and returns a list of the split statements.

Specifications
^^^^^^^^^^^^^^

1.  Add a new line of code in the same Jupyter notebook

.. code:: pycon

    >>> TEENAGE_MUTANT_NINJAS = ('Michaelangelo. Leonardo. Rafael. Donatello. Heroes '
                         'in a half shell.')


2.  Use the string ``.split()`` program to split up the
    ``TEENAGE_MUTANT_NINJAS`` variable using a period + space ``'. '`` as the
    delimiter.

3.  Save the result into a new variable named ``TURTLE_POWER``

Final Output
^^^^^^^^

.. code:: pycon

    >>> print (TURTLE_POWER)
    ['Michaelangelo', 'Leonardo', 'Rafael', 'Donatello',
     'Heroes in a half shell.']


Task 06
-------

The ``strip()`` commands are of great help when dealing with poorly formatted
data.

Specifications
^^^^^^^^^^^^^^

1.  Add a new line of code in the same Jupyter notebook

.. code:: pycon

    >>> NERVOUS_AS = """
 //////////A long-tailed cat in a room full of rockin' chairs.,,,,,,,,,, """.strip()


2.  Use the ``strip()`` function to remove whitespace from ``NERVOUS_AS`` and
    save the result back into the ``NERVOUS_AS`` variable

3.  In a single-line statement, use ``rstrip()`` and ``lstrip()`` to remove the
    commas (``,``), and forward slashes (``/``) from ``NERVOUS_AS`` storing the
    result back into the ``NERVOUS_AS`` variable.

.. note::

    Depending upon what a function returns, it is possible to chain together
    multiple function calls as a form of shorthand. This is possible because
    these functions either return the original object or an object of the
    exact same time (eg, a string) so subsequenct ``.function()`` calls may
    be strung together one after another.

Final Output
^^^^^^^^

.. code:: pycon

    >>> print (NERVOUS_AS)
    A long-tailed cat in a room full of rockin' chairs.


Task 07
-------

One of the simple, though useful, string functions available in Python are
the casing functions such as ``.lower()`` and ``.upper()``.

Specifications
^^^^^^^^^^^^^^

1.   Add a new line of code in the same Jupyter notebook

.. code:: pycon

    >>> MOVIE = 'dr. strangelove or: how i learned to stop worrying and love the bomb'
`

2.  Use a string function that will change ``MOVIE`` to titlecase and save its
    result into a new variable named ``ENTITLED``

Final Output
^^^^^^^^

.. code:: pycon

    >>> print (ENTITLED)
    Dr. Strangelove Or: How I Learned To Stop Worrying And Love The Bomb



Task 08
-------

There are just a few more basic types with which we ought to familiarize
ourselves at this point.

Specifications
^^^^^^^^^^^^^^

2.  On a new line, create a new variable named ``IS_TRUE`` and assign it a value of ``True``

3.  Create a new variable named ``IS_FALSE`` and assign it a value of ``False``

4.  Create a new variabled named ``IS_NONE`` and assign it a value of ``None``

5.  **In a single, one-line statement**, use the *logical AND* operator and the
    *equality* operator to test if ``IS_TRUE`` is equal to ``1`` and
    ``IS_FALSE`` is equal to ``0``

6.  Store the result into a new variable named ``INTEGER_EQUIV``

Final Output
^^^^^^^^

.. code:: pycon

    >>> print (IS_TRUE)
    True
    >>> print (IS_FALSE)
    False
    >>> print (IS_NONE)
    None
    >>> INTEGER_EQUIV
    True


Submission
==========

Code should be submitted via Blackboard as a single Jupyter notebook file.

In order to receive full credit you must complete the assignment as-instructed
and without any violations (reported in the build status). 


.. _GitHub: https://github.com/
.. _Python String Documentation: https://docs.python.org/2/library/stdtypes.html
