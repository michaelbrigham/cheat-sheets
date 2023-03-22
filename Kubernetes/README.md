### Remove node from scheduling
kubectl drain <node_name> --ignore-daemonsets --delete-emptydir-data

### Add node back to scheduling
kubectl uncordon <node_name>
