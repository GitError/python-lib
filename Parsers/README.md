#  

## Parsers

[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Python_3.7-1f425f.svg)](http://commonmark.org)

### [split_by_delimiter.py](split_by_delimiter.py)

Split a *.txt that's line-delimited '{delimiter}{file_name.txt}' into multiple *.txt files

#### Script Usage

python split_by_delimiter.py file_path.txt [delimiter]

#### Defaults

- input_file_path: \\.input.csv
- delimiter: --\*\*\*{file_name.txt}
- output files path: \\.

### [split_by_lines.py](split_by_lines.py)

Split a *.txt into into multiple *.txt files based on a batch size (# of lines) with output file names as {input_file_name}{_fragment_number.txt}

#### Script Usage

python split_file_into_multiple_by_line.py file_path.txt [batch_size]

#### Defaults

- input_file_path: \\.big.txt
- batch size: 50,000
- output files path: \\.

### [convert_to_excel.py](convert_to_excel.py)

A simple script that prompts used to select a log file and converts it to nicely formatted excel file.

#### Script Usage

python convert_to_excel.py

#### Dependencies

- tkinter -> packaging
- pandas -> needs to be packaged with
