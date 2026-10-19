# School_Projects-with-files-

Small Python exercises from my school computer science lessons (2021), some written with classmates. They are short command-line scripts for practising basic algorithms, file handling and simple games.

## What's here

| File | What it does |
| --- | --- |
| `noughts_and_crosses.py` | Two-player noughts and crosses in the terminal, with coloured X/O (colorama) |
| `connect_four.py` | Early attempt at Connect Four on a 6x7 grid. Unfinished: it still uses the 3x3 noughts-and-crosses win check and has no column "drop" |
| `bubblesort.py` | Bubble sort on numbers you enter |
| `binary_search.py` | Binary search on a sorted list you enter, printing each step |
| `linear_search.py` | Linear search for a random number, plus an unfinished recursive search experiment |
| `marks_sorter.py` | Reads `marks.txt` (sample names and marks) and sorts it by mark, then alphabetically |
| `random_encryption.py` | Toy cipher that shifts characters by a random offset and hex-encodes them, with a matching decryptor. Not secure, just an exercise |
| `homework.py` | Averages a list of temperatures you enter |
| `psuedocode.txt` | Pseudocode for a class exercise (not runnable Python) |

## Tech

Python 3 (standard library), plus `colorama` for `noughts_and_crosses.py`

## Running it

```bash
pip install colorama
python noughts_and_crosses.py
```

Each script runs on its own, for example `python bubblesort.py` or `python marks_sorter.py` (run this one from the repository folder so it can find `marks.txt`). `main.py` just imports and runs `random_encryption.py`.

## Notes

These are beginner exercises kept as a record of early work. Some are incomplete, as noted in the table.
