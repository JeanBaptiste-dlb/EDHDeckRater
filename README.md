# EDHDeckRater

When playing casual EDH it is often a complicated discussion to evaluate the power level of decks. I propose a automated grader based on objective criterion. The input should be a decklist and the output a radar chart of different stats for the deck.

## Project Structure

```text
edh_deck_rater
|-- bin/                         # CLI scripts
|-- notebooks
|   |-- *.ipynb                  # Jupyter notebooks
|   `-- my_nb_path.py            # Imported by *.ipynb to treat src/ as PYTHONPATH
|-- requirements/                # Dependencies required by this project
|-- src                          # Python modules developed in this project
|   `-- my_nb_color.py           # Imported by *.ipynb to colorize their outputs
|-- tests/                       # Unit tests

# Miscellaneous files
|-- .editorconfig                # Editor config (for IDE / editor that support this)
|-- .gitattributes               # Files that Git must give special treatments
|-- .gitignore                   # Git ignore list
|-- .pre-commit-config.yaml      # Precommit hooks
|-- LICENSE                      # License
|-- README.md                    # Template document
|-- pyproject.toml               # Settings for select Python toolchains
`-- tox.ini                      # Settings for select Python toolchains
```

## Credits

This project was initialized by Jean-Baptiste de la Broise using:

```bash
cookiecutter https://github.com/aws-samples/python-data-science-template
```

## License

This library is licensed under the MIT License. See the [LICENSE](LICENSE) file.
