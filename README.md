# AIRS15 results

All the details are in [our paper](http://to_appear.pdf).

## Naming rule

```
[TREC_query_ID]_[ID_of_method].json
```

## Attributes

### qID

is the TREC query ID.

### methodID

is the ID of the method (0: Baseline, 1: Existing, 2: Ours, 3: Combination).

### rel*n*

is the snippet-based relevance judgment result of the *n*th document in the TREC baseline ranking (t: relevant, f: irrelevant).

## Note

* Each participant used each method almost evenly, e.g.
    * Participant A: (qID: 251, methodID: 0) -> (252, 1) -> (253, 2) -> (254, 3) -> (255, 0) -> ...
    * Participant B: (qID: 251, methodID: 1) -> (252, 2) -> (253, 3) -> (254, 0) -> (255, 1) -> ...
    * and so on.
