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

    > activate --help


## screens

Turn on/off an ``xrandr`` screen configuration/profile. For instance, to turn
on my office screens, I do this::

    > screens office on

At the end of the day, I turn them off::

    > screens office off

Install with:

    > sudo install screens /usr/local/bin

See the help:

    > activate --help


