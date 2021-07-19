# Haskell Performance Tuning Book

- [Goals and Focus](#goals-and-focus)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Build instructions](#build-instructions)
- [License](#license)

## Goals and Focus

This book is a community-driven effort to provide a document describing how to
write *idiomatically fast Haskell* by providing insight into how Haskell behaves
under the hood, describing various techniques and tools used to identify
performance issues, categorizing common performance issues, and demonstrate
how to tackle performance problems step-by-step using case studies.

This book should:

- Focus on writing idiomatic Haskell code that is fast
- Target at hobbyists and professional Haskell developers
- Be a community led effort
- Be maintained over time
- Be relatively short
- Be incrementally delivered
- Be a mixture of prose chapters and case study chapters

## Roadmap

These are the general topics we would like to cover in this book:

1. Principles of Haskell's evaluation model, data representation,
   and the behavior of common functions
2. Classification of common performance issues
3. Identification of performance issues using profiling
4. Creation of automated tests for performance regressions
5. Case studies, including case studies for a web service
   and on program architecture

See the [project board](https://github.com/haskellfoundation/gotta-go-fast/projects/1)
for more information on the current status of the project.

## Contributing

We are very interested in contributors for the project!

If you are interested in contributing by writing, editing, reviewing,
suggesting additional content or anything else, please check the
[CONTRIBUTING.md](./CONTRIBUTING.md) guide for more information!

## Build instructions

This book is built using [mdBook](https://rust-lang.github.io/mdBook).
A binary distribution is downloadable from here:
https://github.com/rust-lang/mdBook/releases

The following commands should clone the repository, render the book,
serve it locally on http://localhost:3000 and watch for changes locally
in the `src/` directory:

```sh
git clone https://github.com/haskellfoundation/gotta-go-fast
cd gotta-go-fast
mdbook serve
```

## License

This book is licensed under [CC-BY-4.0](./LICENSE.txt)
