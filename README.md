# Honours Project - NLP Backend

## Requirements

* Python 3
* [Pip](https://pip.pypa.io/en/stable/)
* [punkt](https://www.nltk.org/_modules/nltk/tokenize/punkt.html)

## Installation

I would recommend having [`virtualenv`](https://virtualenv.pypa.io/en/stable/) installed to keep versions separate from one another.

To install the Python dependencies, run

    pip install -r requirements.txt

You must also install the Punkt Sentence Tokenizer (https://www.nltk.org/_modules/nltk/tokenize/punkt.html) in order for the input files to be parsed properly.

To do this, run

    python install.py

## Usage

To use the program, run the command

	python generate.py <INPUT_FILE> [OUTPUT_FILE]

NOTE: If you have multiple `python` versions on your computer, you might need to replace `python` with `python3` in the commands.

Where `INPUT_FILE` is the path (relative or absolute) to the source textfile, and `OUTPUT_FILE` is an optional argument detailing the desired path where the output JSON tree will be saved. 

If `OUTPUT_FILE` is not specified it will default to `trees/FILE_NAME.esc` where `esc` stands for escutcheon and `FILE_NAME` is the same as the input file, minus any file extension.
