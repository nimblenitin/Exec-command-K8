# Exec-command-K8
Exec command allows you to shell inside a container and perform various commands.

Simple example-

*As Root*
```

1 Create a simple Pod with a container running Nginx
$ kubectl apply -f shell-demo.yaml

2. Verify that the container is running:
$ kubectl get pod shell-demo

3. Shell into the container created
$ kubectl exec --stdin --tty shell-demo -- /bin/bash

4. Run a command in the container
$ ls /

```
*As Root*


