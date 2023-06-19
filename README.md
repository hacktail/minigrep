# minigrep
A smal grep written in rust guided by [the rust book](https://rust-book.cs.brown.edu/ch12-00-an-io-project.html)

## Usage:
  ```bash
  minigrep {query} {file path}
  ```
  Incase you want to ignore case create an enviromental variable called "IGNORE_CASE" and give it whatever value you want
  ```bash
  IGNORE_CASE=1 minigrep {query} {file path}
  ```
