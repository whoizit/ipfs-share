#### You need enable these features first:
- [ipfs-filestore](https://github.com/ipfs/go-ipfs/blob/master/docs/experimental-features.md#ipfs-filestore)  
- [ipfs-urlstore](https://github.com/ipfs/go-ipfs/blob/master/docs/experimental-features.md#ipfs-urlstore)

#### For example:
```
ipfs shutdown
ipfs config --json Experimental.FilestoreEnabled true
ipfs config --json Experimental.UrlstoreEnabled true
ipfs daemon --enable-gc --migrate --enable-pubsub-experiment
```
