\# Big Bang Generator



\## Description



This project generates an array of values from 1 to 100 using the following rules:



\* Numbers divisible by \*\*3\*\* are replaced with \*\*"BIG"\*\*.

\* Numbers divisible by \*\*5\*\* are replaced with \*\*"BANG"\*\*.

\* Numbers divisible by both \*\*3 and 5\*\* are replaced with \*\*"BIGBANG"\*\*.

\* All other numbers are stored as strings.



The generated array is written to `output.json`.



\## Requirements



\* Node.js



\## How to Run



1\. Clone the repository.

2\. Open a terminal in the project folder.

3\. Run:



```bash

node index.js

```



The script will generate `output.json`.



\## Example Output



```json

\[

&#x20; "1",

&#x20; "2",

&#x20; "BIG",

&#x20; "4",

&#x20; "BANG",

&#x20; "BIG",

&#x20; "7",

&#x20; "8",

&#x20; "BIG",

&#x20; "BANG",

&#x20; "11",

&#x20; "BIG",

&#x20; "13",

&#x20; "14",

&#x20; "BIGBANG"

]

```



