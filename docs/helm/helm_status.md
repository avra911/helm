## helm status

displays the status of the named release

### Synopsis



This command shows the status of a named release.
The status consists of:
- last deployment time
- k8s namespace in which the release lives
- state of the release (can be: UNKNOWN, DEPLOYED, DELETED, SUPERSEDED, FAILED or DELETING)
- list of resources that this release consists of, sorted by kind
- details on last test suite run, if applicable
- additional notes provided by the chart


```
helm status [flags] RELEASE_NAME
```

### Options

```
      --revision int32   if set, display the status of the named release with revision
```

### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "~/.helm")
      --host string               address of tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of tiller (default "kube-system")
```

### SEE ALSO
* [helm](helm.md)	 - The Helm package manager for Kubernetes.

###### Auto generated by spf13/cobra on 11-Mar-2017
