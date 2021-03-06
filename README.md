# BetterInput : Terminal-like Python `input()`

<p align="center">
<img src="./assets/icon.png" width="400">
<br>
<a target="_blank"><img src="https://img.shields.io/badge/platform-linux-lightgrey.svg"></a>
<a target="_blank" href="https://www.python.org/downloads/" title="Python version"><img src="https://img.shields.io/badge/python-%3E=_3.6-green.svg"></a>
<a target="_blank" href="https://opensource.org/licenses/MIT" title="License: MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
<a target="_blank" href="http://makeapullrequest.com" title="PRs Welcome"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
</p>

***
> A better Python `input()` function.
***
## Why `BetterInput`?

Look what happens when your client wants to fix their typo, using the Python built-in `input()`:

> <img src="./assets/gifs/input.gif">

Now use `BetterInput`:

> <img src="./assets/gifs/better_input.gif">

## Usage
```python
from better_input import BetterInput

client = BetterInput()
result = client.input("Enter something: ")
print(result)
```