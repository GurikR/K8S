# Helm Basics

+ **kubectl get ns** command to list of namespaces in a cluster
+ **helm list** command to list the namespaces in clusters
+ **helm install ${namespace} .** command to add new namespace in kubernetes cluster, (.) at the end of command indicates the current folder 
${namepace} indicates chart namespace value
+ **helm uninstall ${namespace}** command to delete given namespace in kubernetes cluter
+ **helm history ${namespace}** command to list the history of helm revisions right from install, upgrade and rollbacks
+ **helm rollback ${namespace}** **${revision}** command to rollback/revert to mentioned revision
+ **helm uninstall ${namespace} --dry-run** command to execute deletion of namespace in dry run manner w/o actually deleting it
+ **helm upgrade --install ${namespace} .** command which install the namespace if it's not present if already present uprades the namespace
