# README: how to use this folder?

Before jumping into the code, let's clarify the content of this folder, starting from the extension of the files `.ipynb`.

The extension `.ipynb` characterizes the type of files referred to `notebooks`
that are supportive tools to mix (a) code used to produce results and (b) textual and graphics description
of the code itself.

The key ingrediant of notebooks are `cells` that are of two main types:
- `Code cells`: that contain executable code. They can be executed and the outputs may be printed just below the cell
- `Markdown cells`: they are descriptive cells containing a description of the code being executed in the nearby cells

In this package, you can find examples for basic programming used for teaching for both julia and python examples. A folder is dedicated to each language and appropriate environment files are added to ease the installation and use of the material.

# The environment

Please, each folder Julia and Python contains an environment file that can be used to create a new environment with the necessary packages to run the notebooks.

- In the Julia folder, the environment is contained in the file `Project.toml`
- In the Python folder, the environment is contained in the file `environment.yml`

