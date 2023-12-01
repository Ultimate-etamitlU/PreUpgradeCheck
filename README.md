# PreUpgradeCheck

A script to check pre-requstisites and checks before marking a cluster to upgrade.


## Sequesnce.

- Check all ClusterOperators states
- Check all node states
- Check all MCP's
- Check all PODS
- Check all nodes kubelet status
- Check all nodes rpm-ostree status

To be worked further! 
