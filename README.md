# Fox API in Python

Behind this API is a software layer connecting and optimizing communications networks around the world to allow your users to call and fetch specific user information as well as much more.

## Table of Contents
- [Getting Started](#getting-started)
    - [Installing](#installing)
    - [Common Issues](#common-issues)
- [Quick Start Guide](#quick-start-guide)
- [Authors](#authors)
- [License](#license)

## Getting Started

To get started using this api follow the instructions below.

### Installing

Please note if you are receiving an error feel free to open an issue.

```sh
pip install FoxApi
python -m playwright install
```
If you would prefer a video walk through of setting up this package A youtube video is available for just that. [YouTube video](https://www.youtube.com/).

If you're on MacOS you may need to install [XCode Developer Tools](https://webkit.org/build-tools/)

#### Docker Installation

Clone this repository onto a local machine then run the following commands.

```sh
docker pull foxapi
docker build . -t foxapi:latest
docker run -v FoxApi --rm Foxapi:latest python3 your_script.py
```

**Note** this assumes your script is named your_script.py and lives in the root of this directory.

## Quick Start Guide

Here's a quick bit of code to get the most recent trending on the Fox app. For More Examples visit the Example Directory.

```py
from FoxApi import FoxApi
api = FoxApi.get_instance()
results = 5

To run the example scripts from the repository root, be sure to the module form of python the interpreter

```sh
python -m examples.get_trending
```

## Authors

* **Ava Williams ** 

## License

This project is licensed under the MIT License
