## Installation

Install the requirements: `pip install -r requirements.txt`, then download the Wordnet data for NLTK.
Run the Python interpreter and type the commands:

```
>>> import nltk
>>> nltk.download('wordnet')
```


## Exploring Wordnet taxonomies

To visualize the hierarchical representations in Wordnet a command-line tool was created

**Usage:**

Get the taxonomy tree for a synset:

`./wordnet_tree.py -s n.01.dog`

Get the the taxonomy tree for the synset and generate IDs to be used for Yago queries:

`./wordnet_tree.py -s n.01.dog --ids`

Get the taxonomy tree for the synset and display descriptions

`./wordnet_tree.py -s n.01.dog --descriptions`

Show children for a selected synset

`wordnet_tree.py -s n.01.dog --children`