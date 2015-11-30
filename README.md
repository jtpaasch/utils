# Utils

Scripts, programs, and other utilities I use frequently.


## activate

Activate a Python virtual environment by running the following command
in the current directory:

    > . activate

That, in turn, runs this:

    > . venv/bin/activate

If the virtual env directory is named differently, e.g., `pyvenv`, use
the `--venv` flag:

    > . activate --venv pyvenv

Install with:

    > sudo install activate /usr/local/bin

See the help:

    > . activate --help


## screens

Turn on/off an `xrandr` screen configuration/profile. For instance, to turn
on my office screens, I do this:

    > screens office on

At the end of the day, I turn them off:

    > screens office off

Install with:

    > sudo install screens /usr/local/bin

See the help:

    > screens --help


## use-java

Activate a particular version of Java. For instance, to use the Java
installed at `~/jubbajdk/jdk1.8.0_u66`, I'd do this:

    > . use-java ~/jubbajdk/jdk1.8.0_u66

To deactivate that version of Java, just exit the terminal session.

Install with:

    > sudo install use-java /usr/local/bin

See the help:

    > . use-java --help


## use-maven

Activate a particular version of Maven. For instance, to use the Maven
installed at `~/maven/apache-maven-3.3.3`, I'd do this:

    > . use-maven ~/maven/apache-maven-3.3.3

To deactivate that version of Maven, just exit the terminal session.

Install with:

    > sudo install use-maven /usr/local/bin

See the help:

    > . use-maven --help


## use-python

Activate a particular version of Python. For instance, to use the Python
installed at `~/python/Python-3.5.0`, I'd do this:

    > . use-python ~/python/Python-3.5.0

To deactivate that version of Python, just exit the terminal session.

Install with:

    > sudo install use-python /usr/local/bin

See the help:

    > . use-python --help

