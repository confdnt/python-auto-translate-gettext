python-auto-translate-gettext
===============

What is it?
-----------

This tool will translate a gettext .po file using `DeepL <https://www.deepl.com/>`__ and save the translated strings to that same file.

Documentation
-------------

You will need the polib and deepl python libraries installed on your system.
Get an API key from DeepL for free. Add it as an environment variable or directly in the script.

Just run python ./main.py

Provide the full path of your .po file.
Pick the language it should be translated to e.g. DE or FR.


Licensing
---------

python-auto-translate-gettext is licensed under the terms of the MIT License (see
`License <LICENSE>`__).

python-auto-translate-gettext includes copies of Python's ``captured_output``,
``captured_stdout`` and ``captured_stderr`` context managers, which are
licensed under the terms of the
`PSF LICENSE AGREEMENT FOR PYTHON <https://docs.python.org/3/license.html>`__.