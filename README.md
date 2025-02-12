# dag_dataset

Json file consists of the following fields:

Name: the name of the paper (str)

Link: the link to the paper (str)
Nodes: nodes of the dag with the description {str: str, ...}
DAG: the DAG connections as a list of lists of two where the first entry point to the second [[str, str], ...]
Text: text with the information about the DAG (str)
