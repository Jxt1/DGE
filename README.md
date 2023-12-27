## DGE [TSC 2023]
Fast Subgraph Matching by Dynamic Graph Editing 

## Run
Under the root directory of the project, Execute the following command to run the program

```bash
export LD_LIBRARY_PATH=.:$LD_LIBRARY_PATH
./DGE -d ./data/data.txt -q ./data/query.txt -num 100000
```

Or run the program with the script:

```bash
export LD_LIBRARY_PATH=.:$LD_LIBRARY_PATH
./run.sh
```

# Output
The output includes the filter time, enumerate time and the number of matched subgraphs.


## Graph Format
You can find example data graph and query graph files under the data directory.

Here is an example:
```bash
t 5 7
v 0 0 2
v 1 0 3
v 2 0 3
v 3 0 3
v 4 0 3
e 0 1 0
e 0 2 0
e 1 3 0
e 1 4 0
e 2 3 0
e 2 4 0
e 3 4 0
```
