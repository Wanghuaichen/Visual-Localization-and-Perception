﻿# Visual Localization and Perception
 
 This repository contains the implementations of assignments in Visual Localization and Perception Lesson (EE382).

## 1. Requirements
#### General
- Python (verified on 3.5.4)

#### Python Packages
- numpy (verified on 1.14.3)
- matplotlib (verified on 3.2.1)
- argparse (standard library, verified on 1.1)

## 2. Assignments
### 2.1. Assignment 1

For detailed information about Assignment 1, check document [Asgmt1-README](./Asgmt1/README.md)

## 3. Run the scripts

### Install the requirements

```
pip install -r requirements.txt
```

If everything works well, you can run `python ./Asgmt1/hist_spec.py` to apply histogram specialization to a pair of test images.

### Command-line

```
python [script name].py -h
```

All the scripts use `argparse` module to make it easy to write user-friendly command-line interfaces. You can use option `-h` or `--help` to get a useful usage message for each script.
