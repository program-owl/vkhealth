VKhealth
========

Module that shows the health of VKontakte platform.

Requirements
============

* *Python* (>= 3.5)
* *bs4* package
* *requests* package
* *lxml* package
* *json* package

Usage
=====

* Install package from `pypi.org <https://pypi.org>`_.
* Import it using ``import vkhealth.vkhealth as vkhealth`` command.
* Run ``vkhealth.get()`` command.

Output Format
=============

Output contains the JSON file that sees like that:

``{``

    ``'module_name_1': {``

        ``working': true/false,``

        ``'ping': 1 [s],``

        ``'uptime': 100.0 [%]``

    ``},``

    ``'module_name_2': {``

        ``'working': true/false,``

        ``'ping': 1 [s],``

        ``'uptime': 100.0 [%]``

    ``}``

    ``...``

``}``

Autor
=====
`Daniil Chizhevskij <mailto:daniilchizhevskij@gmail.com>`_
