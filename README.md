# skyrmion

Python package to analyze the spatial organization of skyrmions in microscopy
images. Built on [vistiq](https://github.com/ksiller/vistiq), with
[bioio-emd](https://pypi.org/project/bioio-emd/) for reading EMD files.

## Requirements

- Python 3.12 or newer
- [uv](https://docs.astral.sh/uv/)

## Installation

```bash
git clone https://github.com/ksiller/vistiq-skyrmion.git
cd vistiq-skyrmion
uv sync
```

## Usage

Run the command-line entry point:

```bash
uv run skyrmion
```

An example analysis is in [`notebooks/skyrmion.ipynb`](notebooks/skyrmion.ipynb).

## Project layout

```
src/skyrmion/   package source
notebooks/      example notebooks
```

## License

BSD 3-Clause. See [LICENSE](LICENSE).
