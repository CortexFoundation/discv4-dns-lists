# discv4-dns-lists
If you want your node in the list, simply run your client ```(latest version)``` and make sure it is reachable through discovery. The crawler will pick it up and sort it into the right list automatically.
```
go run  .  --verbosity 5 discv4  crawl -timeout 30m   all-nodes.json 
```
