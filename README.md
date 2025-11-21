[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/ssciwr/heiplanet-platform-documentation/main.svg)](https://results.pre-commit.ci/latest/github/ssciwr/heiplanet-platform-documentation/main)


# heiplanet-platform-documentation
The combined documentation for the heiplanet-platform components.

If you want to build the documentation locally, you have to checkout the submodules too. When cloning, either use 
```bash
git clone --recursive <repo-name>
```
or clone normally and then initialize the submodules:
```bash
git submodule update --init --recursive
```

To build the documentation, install the necessary components as specified in `requirements.txt` into your environment using `pip` or `uv`. 

## Contributing
We are using `pre-commit` hooks, please make sure to activate these using `pre-commit install` before making your first commit.