# Hermes

Create a password generator that builds passwords from customisable "elements" - not just single letters, numbers, or symbols, but also whole words you select. Each element (letter, number, symbol, or chosen word) counts as one building block in the password.

# How it works

You define a list of available elements:

- Letters (A-Z, a-z)

- Numbers (0-9)

- Symbols (~!@#$...)

- Custom words (from a file or predefined collection in code, e.g., "example", "0811")

The generator should create all possible passwords up to N elements long, where each element can be any letter, number, symbol or word from your list.

Example: For N=3, possible passwords include A7!, wordZ9, or hello12@ (where word or hello are words in the list)

# Acceptable Criteria

Generates a lists of passwords up to N **elements** containing letters, numbers and words.
    Specify maximum password length in elements (not just characters).

# Goal

Quickly generate comprehensive password lists with flexible, user-defined building blocks, making it easy to create strong, memorable, or highly varied passwords.
