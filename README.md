# Utils

Scripts, programs, and other utilities I use frequently.


## activate

Activate a Python virtual environment by running the following command
in the current directory::

    > . activate

That, in turn, runs this::

    > . venv/bin/activate

If the virtual env directory is named differently, e.g., ``pyvenv``, use
the ``--venv`` flag:

    > . activate --venv pyvenv

Install with::

    > sudo install activate /usr/local/bin

See the help::

    > . activate --help


## screens

Turn on/off an ``xrandr`` screen configuration/profile. For instance, to turn
on my office screens, I do this::

    > screens office on

At the end of the day, I turn them off::

    > screens office off

Install with:

    > sudo install screens /usr/local/bin

See the help:

    > screens --help


## jenv

Activate a particular version of Java. For instance, to use the Java
installed at ``~/jubbajdk/jdk1.8.0_u66``, I'd do this:

    > . jenv ~/jubbajdk/jdk1.8.0_u66/bin

To deactivate that version of Java, just exit the terminal session.

Install with:

    > sudo install jenv /usr/local/bin

See the help:

    > jenv --help