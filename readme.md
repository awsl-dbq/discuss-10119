## Source:
https://discuss.dgraph.io/t/whats-problem-of-this-query/10119

## The way to reproduce the bug
I find the bug is deeply related to the data.

I tar the /dgraph to dgraph.tar

using the data in dgraph.tar , then you can reproduce the bug.

If I export the data and reload it to a new cluster, it' okay.

If I copy the p,w,zw to a new cluster, it's bugs here.

The dgraph version is v20.7.0