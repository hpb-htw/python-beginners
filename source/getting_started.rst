Getting started
***************



What is Python, exactly?
========================

Ok, so python is this thing called a **programming language**. It takes text that 
you've written (usually referred to as **code**), turns it into instructions for 
your computer, and runs those instructions. We'll be learning how to write code 
to do cool and useful stuff. No longer will you be bound to use *others'* 
programs to do things with your computer - you can make your own!

Practically, Python is just another program on your computer. The first thing to 
learn is how to use and interact with it. There are in fact many ways to do this; 
the first one to learn is to interact with python's interpreter.
We use the programm Thonny in this course to interact with the python' interpreter.
To start the programm Thonny just click the Thonny Icon on Desktop Screen.


Using Python
============



Interacting With Python
-----------------------

After Thonny opens, it will show you a Python Shell with some contextual information similar to this::

    Python 3.13.3 (main, Apr  9 2025, 08:55:02) [GCC 11.4.0] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>> 

.. note::

   The prompt ``>>>`` on the last line indicates that you are now in an
   interactive Python interpeter session, also called the "Python shell".
   **This is different from the normal terminal command prompt!**

You can now enter some code for python to run. Try::

    print("Hello world")

Press :kbd:`⏎` and see what happens. After showing the results, Python
will bring you back to the interactive prompt, where you could enter 
another command:

    >>> print("Hello world")
    Hello world
    >>> (1 + 4) * 2
    10

An extremely useful command is ``help()``, which enters a help functionality 
to explore all the stuff python lets you do, right from the interpreter.
Press :kbd:`q` to close the help window and return to the Python prompt.

To leave the interactive shell and go back to the console (the *system* shell), 
press :kbd:`Ctrl-Z` and then :kbd:`⏎` on Windows, or :kbd:`Ctrl-D` on 
OS X or Linux. Alternatively, you could also run the python command ``exit()``!


Exercise
--------

Just above we demonstrated entering a command to figure out some math. Try 
some math commands of your own! What operations does python know? Get it 
to tell you what 239 and 588 added together, and then squared is.

.. admonition:: Solution
    :collapsible: closed

    Here are  some ways you might have got the answer:

        >>> 239 + 588
        827
        >>> 827 * 827
        683929

        >>> (239 + 588) * (239 + 588)
        683929

        >>> (239 + 588) ** 2
        683929

Running Python files
--------------------

.. rewrite this section to use thonny

When you have a lot of python code to run, you will want to save it into 
a file, so for instance, you can modify small parts of it (fix a bug) and 
re-run the code without having to repeatedly re-type the rest. 
Instead of typing commands in one-by-one you can save your code to a 
file and open the file name in :program:`Thonny` program.
It will let :program:`python` execute that file's code.

**Let's try that!**  Create a file :file:`hello.py` in :program:`Thonny` and write the print command from above.
Now save that file. To run this file with python inside :program:`Thonny`, just click the :guilabel:`Run` Button (the green circle with white triangle (▶) inside).
Alternatively you can also press the :kbd:`F5` key.

When click ▶ now, the file is executed and you see the output as before.


And now we are all set and can get started with turtle!


.. warning::

   When playing around with turtle, avoid naming your file :file:`turtle.py` 
   --- rather use more appropriate names such as :file:`square.py` or 
   :file:`rectangle.py`.  Otherwise, whenever you refer to ``turtle``, Python 
   will pick up *your* file instead of the standard Python turtle module.
