LinkedIn 2 CV
==============

Turn your LinkedIn Profile into a professional resume in many formats (PDF / HTML5 / Latex / Asciidoc)

## Motivations

Everyone stalks you on LinkedIn and that's where you get opportunities. But apparently you still need to give a resume/CV before you have your next job interview. So, rather than duplicate efforts you can focus on writing it once well, and then producing a resume in whatever format you want!

Oh, and don't bother using the LinkedIn 'Export to PDF' feature - it sucks.

## Getting Started

First, install [MacTex](http://www.tug.org/mactex/) so that you can produce LaTeX documents. Then, simply run the converter:
    
    gem install linkedin2resume
    linkedin2cv convert  --format latex --options config.yml matt.fellows

The converter should open up a Web Browser and ask you to sign-in to LinkedIn, enabling it to pull down your profile and convert it into a pretty CV.

## Custom fields/data

Some templates may display extra information, or you may choose to make the resume more intelligent. For example, LinkedIn doesn't connect your projects to your role/company. See the example config.yml file for full details.

## Contributing your own template

TODO, sorry!

## Acknowledgements

* Asciidoctor
* LaTeX & MacTex
