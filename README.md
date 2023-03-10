# mkdocs-macros-yaml-examples

_An example site to demo using [mkdocs-macros-plugin](https://github.com/fralau/mkdocs_macros_plugin) with YAML to generate content._

[Browse the examples](https://starfallprojects.github.io/mkdocs-macros-yaml-examples/)

mkdocs-macros-plugin allows you to use variables and macros in your MkDocs sites. It's a powerful tool, and I recommend reading the [mkdocs-macros documentation](https://mkdocs-macros-plugin.readthedocs.io/en/latest/) to learn more about it.

This repo focuses on one task: using YAML to define variables that you can then use in your site. This can range from pulling in something from your `mkdocs.yml` and displaying it in your content, to using extra YAML files to generate page contents.

## Run the examples

You need:

* Python 3.7 or above.
* git

```sh
git clone https://github.com/StarfallProjects/mkdocs-macros-yaml-examples.git
cd mkdocs-macros-yaml-examples
# Create a virtual environment https://docs.python.org/3/library/venv.html
python -m venv venv
# Active your virtual environment
./venv/Scripts/<script-for-your-system>
# Install requirements
pip install -r requirements.txt
# Build and serve locally
mkdocs serve
```
