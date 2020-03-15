# Cerberus pen and paper roleplay

view the project [here](https://cerberus-wiki.readthedocs.io/en/latest/cerberus/how_to_roll.html).
view the project on [Read The Docs](https://readthedocs.org/projects/cerberus-wiki/).

Cerberus is a home-brew alteration of the table top role-play rule set, [cogent](www.cogentroleplay.com).

The main goal of these alterations is to reduce the complexity in making a roll. The plan is to:

- Remove the distinction between assistable and non-assistable skills.
- Make combat and non-combat rolls consistent.
- Reduce the amount of times a player asks the GM whats the challenge level for an assist.
- Reduce confusion about how to roll.
- Maintain the functionality of cogent.

A secondary goal is to experiment and add new features that turn out to be fun to play with. The intention is to keep new features separate and optional.

---

## requirements

This project is hosted on [Read The Docs](https://readthedocs.org/) and we use [sphinx](https://www.sphinx-doc.org/en/master/index.html) to build our documentation.

## development TLDR

install sphinx
```
# install python if you don't have it

$ sudo apt-get install python-sphinx
$ pip install sphinx

```

Build local version
```
$ make html

$ firefox build/html/index.html
$ chromium-browser build/html/index.html
```

you may or may not need to install this stuff
```
$ pip install recommonmark
$ pip install sphinx_rtd_theme
```


## contribution

If you would like to contribute fork the repository and make your changes and submit a pull request.

