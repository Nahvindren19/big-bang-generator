# Big Bang Generator

## Description

This project generates an array of values from 1 to 100 based on the following rules:

* Numbers divisible by **3** are replaced with **"BIG"**.
* Numbers divisible by **5** are replaced with **"BANG"**.
* Numbers divisible by both **3 and 5** are replaced with **"BIGBANG"**.
* All other numbers are stored as strings.

The generated array is then written to an `output.json` file.

## Requirements

* Node.js

## How to Run

1. Clone the repository.
2. Open a terminal in the project directory.
3. Run the following command:

```bash
node index.js
```

After execution, an `output.json` file will be generated in the project directory.

## Example Output

```json
[
  "1",
  "2",
  "BIG",
  "4",
  "BANG",
  "BIG",
  "7",
  "8",
  "BIG",
  "BANG",
  "11",
  "BIG",
  "13",
  "14",
  "BIGBANG"
]
```
