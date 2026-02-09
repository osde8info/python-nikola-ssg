# python nikola ssg

nikola (parent proj)

[![PyPI Downloads](https://static.pepy.tech/personalized-badge/nikola?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads)](https://pepy.tech/projects/nikola)

this proj

[![nikola](https://github.com/osde8info/python-nikola-ssg/actions/workflows/nikola.yaml/badge.svg)](https://github.com/osde8info/python-nikola-ssg/actions/workflows/nikola.yaml)

This folder contains the source used to generate a static site using Nikola.

Installation and documentation at [https://getnikola.com/](https://getnikola.com/)

Configuration file for the site is ``conf.py``.

## install

```bash
pipx install nikola
pipx runpip nikola install Jinja2
```

## build

To build the site::

```bash
nikola build
```

To check it::

```bash
nikola check -l
```

To see it::

```bash
nikola serve -b
```
