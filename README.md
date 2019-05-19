## AST_L1T
Ingests AST_L1T Products
----
There is 1 associated jobs:
- Ingest - AST_L1T

### Ingest - AST_L1T
-----
Job is of type iteration. It takes in an input MET-AST_L1T product. It localizes and publishes the associated product if it does not exist on GRQ.

L1T product spec is the followingc:

    AST_L1T-<sensing_start_datetime>_<sensing_end_datetime>-<version_number>
