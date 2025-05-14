# markdown-transpiler

This project is a Markdown-to-HTML transpiler built using **ANTLR 4** and Java. It takes input written in Markdown syntax and converts it into raw HTML.

## 📌 Features

- Parses a subset of standard Markdown (headers, bold, italics, lists, etc.)
- Converts Markdown to HTML using a custom parse tree walker
- Built with a modular grammar using ANTLR 4
- Easily extendable for additional Markdown features

## 🛠️ Tech Stack

- Java (IntelliJ IDEA)
- [ANTLR 4](https://www.antlr.org/)
- Command-line interface (CLI)

## 🚀 Usage

### Run

After building the project, you can run the transpiler from the command line once you get to the file in your IntelliJ directory:

```bash
java -jar antlr4_MarkdownToHTML3_0/antlr4-MarkdownToHTML3.0.jar
