ECE444 Lab3

Shihua Sun

this repo is a clone of https://github.com/nelaturuk/education_pathways


Activity 5


Functional requirement: When a user gives keyword for searching, the list of results should be ranked according to their relevance
to the keyword for clear orginzation.

Improvement: Right now the searching results don't match the above criterion. In our design, we would employ advanced algorithm to rank the seached courses based on their relevance to the keyword.


Non-functional requirement: the website should use high-contrasting colors to distinguish between background and information.

Improvement: Right now the website only uses white colors and it's hard to tell which part is information and which part is functional buttons. In our design, we would use dark colors in the background and light colors in the text information box so that users can easily tell which part to look at.



# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
