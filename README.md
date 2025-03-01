# Tester - An online replacement for flashcards

If you've ever needed to quickly generate methods for studying, Tester combined with any AI method may be beneficial.

## What is Tester?

Tester is a simple static web tool for testing yourself. It uses importable JSON configuration files to quickly help you review information that would usually be written down on flashcards. It randomizes questions and provides multiple-choice answers (answers from other questions). You can subdivide multiple tests and combine them as necessary to aid memorization.

## How can I use it?

You can access Tester at [bqbbo.github.io/tester](https://bqbbo.github.io/tester/). Import a valid configuration file, and start testing! If you need help creating a configuration file, fill out the following,

```json
{
    "title": "The title of your test!",
    "label": "The label of your test!",
    "blankText": "___",
    "questions": {
        "Your Question!": "Your Answer!"
        // You may want to use AI to generate the JSON file for you.
        // Supply it with this basic configuration, and copy in your questions and answers from an external source.
        // Import and done!
    }
}
```

`blankText` replaces occurrences of `{blank}` in questions with its value. Good for fill-in-the-blank questions!

If you don't have a test, there are some presets you can use to check out the program on the main element.

## Contributing

Contributing is fairly simple, as this is a static site. Please follow Github's instructions for cloning to a local environment (or use Codespaces). If you decide to contribute, please preserve all information in the Info modal and four-space indenting.

All contributions are greatly appreciated!

## Anything else?

If you would like more background info on the creation of Tester, please take a look at the site! Here are some "statistics" as this is one of my biggest projects.

-   This was likely the most complicated thing I've ever done with JavaScript surprisingly, it required the use of a lot of unfamiliar practices, like JSON parsing and file imports with HTML.
-   Creating the CSS for this was surprisingly hard; it underwent 3 redesigns before the final foundation.
-   This site shares a lot of similarities to one of my past projects, [Galactic Tourism Project](https://github.com/bqbbo/galactic-tourism-project). Both were primarily created at school using school Chromebooks. Don't underestimate the power of GitHub Codespaces.
-   This project was created over a month, totaling about 30-40 hours of _redundant_ work.
-   This project was originally created in Python on three different occasions, all using JSON and a CLI. This website was simply an alternative to that hell and was requested by some of my peers.
-   The main motive of this project was to have a chance at beating the "tryhards" of other 8th-grade humanities classes on our Constitutional Challenge. It would allow me to quickly study the flashcards provided in class.

I hope Tester is beneficial to you, and that you enjoy using it as much fun as I had creating it!
