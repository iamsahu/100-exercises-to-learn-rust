# Learn Rust, one exercise at a time

You've heard about Rust, but you never had the chance to try it out?  
This course is for you!

You'll go from knowing nothing about Rust to feeling productive on your own in roughly 100 exercises.

> [!NOTE]
> This course has been written by [Mainmatter](https://mainmatter.com/rust-consulting/).  
> It's one of the trainings in [our portfolio of Rust workshops](https://mainmatter.com/services/workshops/rust/).  
> Check out our [landing page](https://mainmatter.com/rust-consulting/) if you're looking for Rust consulting or
> training!

## Audience

This course is designed for people who have basic familiarity with at least another programming language
(e.g. Python, JavaScript, Java, C++, etc.), but have never written any Rust code before.

Due to the variety of backgrounds, we won't assume any prior knowledge of systems programming or low-level languages.
Approach the relevant exercises as a refresher if you've already been exposed to some of those topics in the past!

## Self-paced

This course is designed to be delivered by an experienced instructor over 4 days: each attendee advances through the
lessons at their own pace, with the instructor providing guidance, answering questions and diving deeper into the topics
as needed.  
As a rule of thumb: if you're stuck on an exercise for more than 10 minutes, ask for help!

You can also try to go through the course on your own, although we recommend having someone to ask questions to if you
get stuck.

## Requirements

- **Rust** (follow instructions [here](https://www.rust-lang.org/tools/install)).  
  If `rustup` is already installed on your system, run `rustup update` (or another appropriate command depending on how
  you installed Rust on your system)
  to make your running on the latest version.
- `mdbook`, to render the course material.
  You can install it with `cargo install --locked mdbook`. 
- _(Optional but recommended)_ An IDE with Rust autocompletion support.
  We recommend one of the following:
    - [RustRover](https://www.jetbrains.com/rust/);
    - [Visual Studio Code](https://code.visualstudio.com) with
      the [`rust-analyzer`](https://marketplace.visualstudio.com/items?itemName=matklad.rust-analyzer) extension.

## Getting started

Clone the repository and create a new branch to work on your solutions:

```bash
git clone git@github.com:mainmatter/rust-workshop.git
# Or `git clone https://github.com/mainmatter/rust-workshop.git` 
# if you haven't set up SSH keys for GitHub

cd rust-workshop
git checkout -b my-solutions
```

From inside the `book` folder, run `mdbook serve` to start a local server and view the course material in your browser.

```bash
cd book
# It'll open the browser automatically
# If it doesn't, open http://localhost:3012 in your browser
mdbook serve --port 3012 --open
```

Follow the instructions in the book to get started with the exercises!

## Solutions

You can find the solutions to the exercises in
the [`solutions` branch](https://github.com/mainmatter/rust-workshop/tree/solutions) of this repository.

## References

Throughout the course, the following resources might turn out to be useful:

* [Rust Book](https://doc.rust-lang.org/book/)
* [Rust documentation](https://doc.rust-lang.org/std/) (you can also open the documentation offline with `rustup doc`!)

# License

Copyright © 2024- Mainmatter GmbH (https://mainmatter.com), released under the
[Creative Commons Attribution-NonCommercial 4.0 International license](https://creativecommons.org/licenses/by-nc/4.0/).
