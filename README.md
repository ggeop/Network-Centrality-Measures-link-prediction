# Network-Centrality-Measures-link-prediction :thought_balloon:
![alt text](https://github.com/ggeop/Network-Centrality-Measures-link-prediction/blob/master/images/Stackoverflow_net.png)

## Dataset
The graph sx-stackoverflow contains the union of these graphs. These graphs were constructed from the Stack Exchange Data Dump. Node ID numbers correspond to 
the Owner-User-Id tag in that data dump. For our analysis the data transformed to the following format: [Source, Destination, Unix Timestamp], 
where Source is the id of the source node, Destination is the id of the target node and Unix Timestamp is the seconds since the epoch.

### Note
Since the aforementioned dataset was big enough1 we have initially decided to execute the algorithms we’ve made in a dummy dataset we created, not only to 
avoid long time executions, but also to have an easy to compute by hand dataset for the validation process. This dummy dataset cannot be found in our code, as it only 
gave as the confirmation we were right on the small scale. After that, a smaller dataset was created, having only a small number of rows of the initial one. The 
purpose of this action is the same to the dummy creation’s one, thus to avoid long time executions. 