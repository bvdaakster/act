# Android CLI Tools
Aims to provide a collection of useful command line tools for Android developers.

## Features
- Generate missing drawables (by down or upscaling existing dpi variants)

## Installation

### From source
`pip install .`

### From PyPI
`pip install androidact`

## Usage
### Generate missing drawables
`act generate-drawables ~/my-android-project`

### Help
```
usage: act [-h] {generate-drawables} ...

Android CLI Tools

positional arguments:
  {generate-drawables}  Description
    generate-drawables  Generate missing bitmap drawables

optional arguments:
  -h, --help            show this help message and exit
```
