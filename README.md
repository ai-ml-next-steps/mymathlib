# mymathlib

A simple Python library for basic arithmetic and geometry operations.

## Installation

```bash
pip install -e .
```

## Usage 

```python
from mymathlib import add, subtract, area_of_circle

print(add(2, 3))              # 5
print(subtract(5, 2))         # 3
print(area_of_circle(1))      # 3.14159...
```

## ✅ 5. Optional: LICENSE

Include an MIT license for open source:

📄 `LICENSE`


## 6. Github Books

```sh
$ ghp-import -n -p -f docs/book/_build/html    
```

### What ghp-import -n -p -f docs/book/_build/html Does:

1. -n: No Jekyll processing (recommended for Jupyter Book)
2. -p: Push the gh-pages branch to your remote repo (origin)
3. -f: Force push, overwriting the branch

- So this command pushes your built book to the gh-pages branch on GitHub.


