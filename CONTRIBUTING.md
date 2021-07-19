# Contributing

Hello! In this document we'll discuss how to contribute to the
Haskell Performance Tuning Book.

- [How to contribute](#how-to-contribute)
    - [As a writer](#as-a-writer)
    - [As a reviewer](#as-a-reviewer)
    - [As a mentor](#as-a-mentor)
- [Contributing process](#contributing-process)
- [How to volunteer](#how-to-volunteer)
- [Expectations](#expectations)
- [Project goals](#project-goals)
- [Project guidelines](#project-guidelines)
- [Building locally](#building-locally)

## How to contribute

Here are a few ways you can contribute to this project:

### As a writer

One way to contribute is by writing new content for the book.
This could be a chapter, a case study, a section, an example, or something else.
We are looking for volunteers to take part in writing of this book!

This could be:

- Covering a particular topic for the book
- Explaining how to use a certain tool
- Adding or suggesting a really good example or case study to help illustrate
  a certain topic
- Something else?

[Let us know if you are interested!](#how-to-volunteer)

### As a reviewer

Another way is to review the content of the book.

- Did you spot a technical mistake?
- Is there a better way to approach a certain problem?
- Did you find a certain section not approachable enough
  or not explaining the subject well enough?
- Did you find typos or grammatical errors?
- Is there a crucial topic we ignored?

We would love to receive reviews from beginners and experts alike!

### As a mentor

Are you very experienced in Haskell, performance oriented programming
or technical writing and would like to mentor others to help with
the creation of this book? [We would love to hear from you!](#how-to-volunteer)

## Contributing process

Writing a book is no easy task, and figuring out the right way
to convey information to the audience requires us to be a bit flexible
and fluid.

We would like to be able to flesh out the content of the book,
have a volunteer volunteer to write the content, review it when
the writer is done, and merge it to be deployed when reviewers
requests have been address. But we recognize that in reality
we will need to be more flexible, and this effort
is more likely to be a collaboration between everyone to figure
out the right way to convey the information.

So while we have some ideas about the structure and content of the book,
we would like to discuss tihs further with volunteers interested in
contributing content, and sometimes changes things as we go.

If you are interested in writing new content, please first mention that
in the relevant ticket for the topic to avoid duplicating the work among
multiple volunteers. We will then talk together about how
to make this work effectively!

## How to volunteer

You can comment on the relevant github issue, open a new issue,
or talk to us on the Haskell foundation's slack (`#perf-book` channel).
You can get an invitation for the slack
[at the bottom of this page](https://haskell.foundation/contact/).

## Expectations

We recognize that we are all volunteers and have limited time and resources
to dedicate to side project. We appreciate your contribution and only ask
for transparency and clarity regarding progress and availability.
The rest we can figure out together.

## Project goals

We use the following goals to guide our approach to this project,
and we will often evaluate contributions and suggestions by how
well the fit said goals.

We want the book to be:

- Relatively short
- Maintained over time, covering the latest tools and techniques
- Incrementally delivered - once a task is merged to the main branch
  the content should be available automatically.
- Targeted at hobbyists and professional Haskell developers

These goals lead to the following decisions:

- Writing this book will be a community driven effort
- We will focus on writing idiomatic Haskell code that is fast
  rather than advanced state-of-the-art techniques
- We will mix prose chapters and case study chapters to cover
  the principles and mindset of performant Haskell code as well as
  providing concrete examples

## Project guidelines

This project is a [Haskell Foundation](https://haskell.foundation/)
project and follows the Haskell Foundation Ethos, as well as the
[Haskell Guidelines For Respectful Communication](https://haskell.foundation/guidelines-for-respectful-communication).

## Building locally

This book is built using [mdbook](https://rust-lang.github.io/mdBook),
which is a very easy to use command line tool for creating books using Markdown.

The easiest to get started is to
[download a binary release](https://github.com/rust-lang/mdBook/releases)
of mdbook, clone this repository, and run `mdbook serve`,
which will then build and render the book, and serve it over port 3000.
to be viewed by a web browser.

```sh
git clone https://github.com/haskellfoundation/gotta-go-fast
cd gotta-go-fast
mdbook serve
```

The content of the book can be found in the `src/` directory, editing
the markdown texts while `mdbook serve` is running will automatically
re-render the book on file save, to be viewed locally here: 
[http://localhost:3000](http://localhost:3000).


