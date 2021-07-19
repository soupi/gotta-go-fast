# Haskell Performance Tuning Book

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

## Build instructions

This book is built using [mdBook](https://rust-lang.github.io/mdBook).
A binary distribution is downloadable from here:
https://github.com/rust-lang/mdBook/releases

The following commands should clone the repository, render the book, serve it locally on
http://localhost:3000 and watch for changes locally in the `src/` directory:

```sh
git clone -b rfc https://github.com/haskellfoundation/gotta-go-fast
cd gotta-go-fast
mdbook serve
```
