Portfolio State Graph Workflow using Langgraph
This project showcases building a simple workflow graph using the langgraph Python library. It demonstrates how to define a typed portfolio state, create processing functions, and connect them sequentially in a state graph to transform the data step-by-step.


Project Overview
Defines a PortfolioState typed dictionary with financial attributes.

Implements functions to calculate total USD amount and convert it to INR.

Builds a state graph with nodes representing these functions connected in sequence.

Visualizes the workflow graph and executes it with sample input to show state transformations.

Features
Typed state representation with Python's TypedDict

Modular, reusable function nodes for state modifications

Graph-based orchestration using langgraph

Visual graph rendering for easy understanding of the workflow

Practical example of workflow automation for financial data processing

Usage
Install the langgraph package.

Run the Jupyter notebook or Python script to see the graph construction and execution.

Modify the portfolio functions or expand the graph to model more complex workflows.

How It Helps
This project demonstrates workflow orchestration through state graphs, which can be applied in data pipelines, financial modeling, ETL processes, and automation tasks. The visualization and modular structure enhance clarity, testing, and maintenance of complex workflows.
