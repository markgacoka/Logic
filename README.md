# Truth Tables in Python
Discipline: Formal Analyses
Helpful for: Algorithms and Deduction

The truth_table.py file prints a truth table for any set of logical sentences connected with any number of logical connectives. This is helpful in Formal Analyses when 

* Dynamic
* Optimized
* Plug and play
  * A meaningful expression is called a well-formed formula.

## Getting Started

To get it into your computer, you can clone it using Git or downloaded directly as a .zip file and extract it.

### Prerequisites

The source code uses [PrettyTable](https://ptable.readthedocs.io/en/latest/tutorial.html) library for displaying the tables neatly. To install, type this into terminal.

```
python3 get-pip.py
pip3 install prettytable
```

If you have downloaded prettytable but you get an import error, download it to a virtual environment and run it from there.
```
source venv/bin/activate
pip install https://pypi.python.org/packages/source/P/PrettyTable/prettytable-0.7.2.tar.bz2
```

## Running the tests
To run the program, simply run the python file and follow the prompts:
```
python3 ~/truth_table.py
```

Supported connectives include:
* Conjunction (and, &)
* Disjunction (or, V)
* Implication (implies, →)
* Biconditional (bicon, ↔)
* Negation (not, ¬)

Explain how to run the automated tests for this system

## Practical Use Cases


## Built With

* [Python](https://docs.python.org/3/) - The language that the source code was made with
* [PrettyTable](https://ptable.readthedocs.io/en/latest/tutorial.html) - The Library used to print the data


## Authors

* [**Gacoka Mbui**](https://github.com/markgacoka)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Prof. Albretcht at Minerva Schools at KGI for giving me feedback on this project.


TODO: Create a UI for it, create a seperate program that scrapes data and extract the logical statements from the paragraph. With proper assignment of its truth values using NLP (Natural Language Processing), we can gauge whether we have an invalid argument.

