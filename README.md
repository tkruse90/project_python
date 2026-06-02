# Python Basics

This repository is a notebook-based learning path for building a solid
foundation in [Python](https://docs.python.org/3/tutorial/). The notebooks
begin with the [VS Code Jupyter Notebook](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
workflow and readable code conventions, then progress through variables,
strings, control flow, data structures, comprehensions, and reusable functions.

Follow the notebooks in numerical order. Each notebook is self-contained, but
the concepts build from basic expressions to a final functions challenge.

## Learning Objectives

By the end of this repository, you should be able to:

- Work productively with Jupyter notebooks in VS Code.
- Write readable Python code using clear naming and formatting conventions.
- Use variables, numeric operators, strings, conditional statements, and loops.
- Choose and manipulate lists, tuples, dictionaries, and sets.
- Build concise collection transformations with comprehensions.
- Define, call, test, and explain reusable Python functions.

## Learning Path

The modules build on each other in order.

### 1 - Getting Started

VS Code notebooks and readable-code conventions.

| File | Description |
| ---- | ----------- |
| [**1 - Intro To Jupyter Notebook**](1_Getting_Started/1_Intro_to_Jupyter_Notebook.ipynb) | Open notebooks in VS Code, select a kernel, execute cells, work with Markdown, and use notebook tooling |
| [**2 - Coding Best Practices**](1_Getting_Started/2_Coding_best_practices.ipynb) | Apply readable naming, whitespace, and formatting practices based on [PEP 8](https://peps.python.org/pep-0008/) |

### 2 - Python Basics

Variables, strings, conditions, and loops.

| File | Description |
| ---- | ----------- |
| [**1 - Numeric Variable Types**](2_Basics/1_Numeric_Variable_Types.ipynb) | Work with variables, numeric data types, operators, and type conversion |
| [**2 - Strings**](2_Basics/2_Strings.ipynb) | Create, combine, index, slice, format, and iterate through text values |
| [**3 - If Statements**](2_Basics/3_If_Statements.ipynb) | Express conditional logic with `if`, `elif`, `else`, and boolean operators |
| [**4 - Loops**](2_Basics/4_Loops.ipynb) | Repeat operations with `while` and `for` loops and control execution with `continue` and `break` |

### 3 - Data Structures

Collections, mutability, and concise transformations.

| File | Description |
| ---- | ----------- |
| [**1 - Lists**](3_Data_Structures/1_Lists.ipynb) | Store, modify, index, slice, and iterate through ordered collections |
| [**2 - Tuples**](3_Data_Structures/2_Tuples.ipynb) | Understand immutable sequences and compare them with mutable lists |
| [**3 - Dictionaries**](3_Data_Structures/3_Dictionaries.ipynb) | Map keys to values, update dictionaries, and loop through keys, values, and items |
| [**4 - Sets**](3_Data_Structures/4_Sets.ipynb) | Store unique values and use set operations for membership and comparison |
| [**5 - Comprehension**](3_Data_Structures/5_Comprehension.ipynb) | Build lists, dictionaries, and tuples concisely from iterables |

### 4 - Functions And Challenge

Reusable code, arguments, and final practice.

| File | Description |
| ---- | ----------- |
| [**1 - Introduction To Functions**](4_Functions/1_Introduction_to_Functions.ipynb) | Understand why functions are useful and define simple reusable operations |
| [**2 - Function Definitions**](4_Functions/2_Function_Definitions.ipynb) | Work with parameters, annotations, defaults, and multiple arguments |
| [**3 - Calling Functions**](4_Functions/3_Calling_Functions.ipynb) | Use positional and keyword arguments correctly |
| [**4 - Challenge**](4_Functions/4_Challenge.ipynb) | Apply the unit's concepts in progressive practice tasks |

### Additional Folders and Files

| File / Folder | Description |
| ------------- | ----------- |
| [**Solution**](solution/) | Complete solution versions of the notebooks with worked code and explanations |
| [**Assets**](assets/) | Local screenshots used in the VS Code Jupyter notebook introduction |
| [**pyproject.toml**](pyproject.toml) | Project configuration and dependency declarations |
| [**uv.lock**](uv.lock) | Reproducible dependency lock file |

## Setup

> [!NOTE]
> Throughout these steps, text in angle brackets like `<repo-name>` is a
> **placeholder**. Replace it including the `< >` brackets with your own
> value. For example, `cd <repo-name>` becomes `cd my-python-basics-project`.

### 1. Create the Repository from the Template

Click **Use this template** on GitHub.

When creating the repository:

- Set yourself as the **Owner**
- Choose a repository name
- Disable **Include all branches**
- Click **Create repository**

> [!IMPORTANT]
> If you are working in pairs or groups, only **one person** should complete this step.

---

### 2. Add Collaborators (Pairs/Groups Only)

If you are working with teammates:

1. Open the repository on GitHub
2. Go to **Settings → Collaborators**
3. Add your teammates as collaborators
4. Share the repository link with your team

---

### 3. Clone the Repository

Copy the SSH URL from the **Code** button on GitHub, then run:

```bash
git clone <copied-ssh-url>
```

The copied SSH URL will look like:
`git@github.com:<your-username>/<repo-name>.git`.

---

### 4. Move into the Project Folder and Install Dependencies

This installs all dependencies and creates a virtual environment in `.venv/`.

```bash
cd <repo-name>
uv sync
```

---

### 5. Open the Notebooks

> [!NOTE]
> Open VS Code from the project root so it detects the environment created by `uv sync`.

Launch VS Code in the project root:

```bash
code .
```

Then open a notebook and select the Python environment created by `uv sync` as the kernel.

## References & Further Reading

- [**The Python Tutorial**](https://docs.python.org/3/tutorial/): Official Python
  introduction covering syntax, data structures, control flow, and functions.
- [**Built-in Functions**](https://docs.python.org/3/library/functions.html):
  Official reference for functions such as `len`, `range`, `type`, `print`,
  `input`, `zip`, and `sorted`.
- [**Jupyter Notebooks in VS Code**](https://code.visualstudio.com/docs/datascience/jupyter-notebooks):
  Official VS Code guide for notebook editing, kernels, variables, and cell
  execution.
- [**PEP 8 - Style Guide for Python Code**](https://peps.python.org/pep-0008/):
  Widely used conventions for readable Python code.
- [**uv Documentation**](https://docs.astral.sh/uv/): Official documentation for
  dependency management and reproducible Python environments.
