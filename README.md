# pycountsiris0614

Calculate word counts in a text file!

## Installation

```bash
$ pip install pycountsiris0614
```

## Usage

`pycountsiris0614` can be used to count words in a text file and plot results
as follows:

```python
from pycountsiris0614.pycounts import count_words
from pycountsiris0614.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycountsiris0614` was created by iris. It is licensed under the terms of the MIT license.

## Credits

`pycountsiris0614` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
