# Free a port that is stuck

`lsof -ti :3000 | xargs kill` stops whatever is holding port 3000.
