# AutoimgRenamer

[![PyPI version](https://img.shields.io/pypi/v/autoimgrenamer.svg)](https://pypi.org/project/autoimgrenamer/)
[![Python version](https://img.shields.io/pypi/pyversions/autoimgrenamer.svg)](https://pypi.org/project/autoimgrenamer/)

AutoimgRenamer is a Python tool to rename image files in a folder with a specified base name and incremental index.

## Installation

You can install AutoimgRenamer from PyPI:

```bash
pip install autoimgrenamer
```

## Usage
```bash
from autoimgrenamer import autoimgrenamer

directory_path = "/path/to/your/images"
new_img_name = 'base'
autoimgrenamer(directory_path, new_img_name)
```
This will rename all supported image files in the directory using the base name (base_0000.PNG, base_0001.PNG, etc.).

Supported Image Formats: JPG, JPEG, PNG, GIF, BMP, WebP
