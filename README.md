# Data Skills Handbook 📖

This online book is part of a set of instruments to develop **Data Skills** in a group setting. The material should be accessible to beginners who have moderate IT skills, are able to confidently browse Internet websites and have worked with spreadsheets before.

🕹️ 10 [GOTO WEBSITE](https://book.dribdat.cc)

## Background

The handbook builds on the [Data Pipeline](http://toolbox.schoolofdata.ch/overview.html) designed by the [School of Data](https://schoolofdata.org) to work with students, journalists, and the civil society. It references the [Dribdat](https://dribdat.cc) platform and other tools from the open data community ([Opendata.ch](https://opendata.ch) - Swiss chapter of Open Knowledge). The book was written for and with students of the Lucerne University of Applied Arts and Sciences ([HSLU](https://hslu.ch)).

## Contributing

🔜 This is an early draft and comments are very welcome. 

We welcome you to contribute ideas for this guide! Please post a discussion topic, open an issue, start a Pull Request. You may also write to 📬 dribdat@datalets.ch

This documentation site is built using [Livemark](https://livemark.frictionlessdata.io/). See instructions below to get a copy of this book running on your computer:

## Installation

Install [Python Poetry](https://python-poetry.org/) and then install the dependencies:

`poetry install`

Enter the Poetry environment:

`poetry shell`

If all is good you can start the local server:

`livemark start`

Open http://localhost:7000/docs/ in your browser.

## Deployment

This command updates the gh-pages branch on GitHub:

`livemark build && ghp-import -p -f -o docs/`

We are currently running this inside of a tidy [GitHub Action](.github/workflows/livemark-gh-pages.yml), no need for manual upload.
