# FAIR-training-flowchart

This repository contains a flowchart for FAIR training, which is designed to help researchers and educators understand the principles of FAIR data management and how to apply them in their work.

In order to use the flowchart, fork this repository and edit `FAIR_training_flowchart.drawio` at draw.io. 

This repository contains the following files:
- `FAIR_training_flowchart.drawio`: The flowchart in draw.io format.
- `FAIR_training_flowchart.drawio.svg`: The flowchart in SVG format, which is used to embed the flowchart in the `flowchart_description.md` file. Once you have edited the flowchart, you can export it as an SVG file from draw.io (File > Export As > SVG ... ).
- `flowchart_description.md`: A markdown file that describes the flowchart and its components.
- `README.md`: This file, which provides an overview of the repository and how to use it.

## Using this repository as submodule

This repository is designed to be used as a submodule in other repositories, so you can include it in your own projects.

In order to include this flowchart in your own project, you can add it as a submodule:

```bash
git submodule add <repository-url>
```

More info about submodules can be found in the [Git documentation](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

If you want `flowchart_description.md` to be part of a documentation website (e.g. with `mkdocs`), you can add it to the `docs` folder of your project. Once you have included this `.md` file in your website, you're all set.

## Using a submodule with GitHub actions

If you render your page through GitHub actions, make sure to checkout the submodule in your workflow. You can do this by adding the following step to your workflow file:

```yaml
    steps:
      - uses: actions/checkout@v4
        with:
          submodules: 'recursive'  # Fetch submodules recursively
```