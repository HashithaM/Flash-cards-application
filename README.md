# French Flash Cards

A Tkinter flash-card application for practising French-to-English vocabulary. Cards flip automatically after three seconds, and known words are removed from the remaining study list.

## Features

- Random French vocabulary cards
- Automatic English translation reveal
- Known/unknown controls
- Persistent progress in `words_to_learn.csv`
- Pandas-based CSV loading and saving

## Requirements

```bash
pip install pandas
```

## Run

```bash
python main.py
```

The current source references assets under `images/` and vocabulary files under `data/`. In this repository the files are stored at the root, so either create those directories and move the matching files or adjust the paths in `main.py` before running.
