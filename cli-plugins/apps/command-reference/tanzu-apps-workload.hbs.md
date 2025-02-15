# Tanzu apps workload

This topic helps you with workload life cycle management.

A workload may run as a Knative service, Kubernetes deployment, or other runtime. Workloads can be grouped together with other related resources, such as storage or credential objects as a logical application for easier management.

Workload configuration includes:

- Source code to build
- Runtime resource limits
- Environment variables
- Services to bind

## <a id="options"></a>Options

```console
  -h, --help   help for workload
```

## <a id="envvars"></a>Environment variables with default values

There are some environment variables that can be specify to have default values so users can execute their commands with the minimum required flags. 
These flags and its naming convention are listed below:

- `--type`: TANZU_APPS_TYPE
- `--registry-ca-cert`: TANZU_APPS_REGISTRY_CA_CERT
- `--registry-password`: TANZU_APPS_REGISTRY_PASSWORD
- `--registry-username`: TANZU_APPS_REGISTRY_USERNAME
- `--registry-token`: TANZU_APPS_REGISTRY_TOKEN

## <a id="parent-commands-options"></a>Options inherited from parent commands

```console
      --context name      name of the kubeconfig context to use (default is current-context defined by kubeconfig)
      --kubeconfig file   kubeconfig file (default is $HOME/.kube/config)
      --no-color          disable color output in terminals
  -v, --verbose int32     number for the log level verbosity (default 1)
```

## <a id="see-also"></a> See also

- [Tanzu applications](tanzu-apps.md)	- Applications on Kubernetes
- [Tanzu apps workload apply](tanzu-apps-workload-apply.md)	- Apply configuration to a new or existing workload
- [Tanzu apps workload create](tanzu-apps-workload-create.md)	- Create a workload with specified configuration
- [Tanzu apps workload delete](tanzu-apps-workload-delete.md)	- Delete workload(s)
- [Tanzu apps workload get](tanzu-apps-workload-get.md)	- Get details from a workload
- [Tanzu apps workload list](tanzu-apps-workload-list.md) - Table listing of workloads
- [Tanzu apps workload tail](tanzu-apps-workload-tail.md) - Watch workload-related logs
- [Tanzu apps workload update](tanzu-apps-workload-update.md)	- Update configuration of an existing workload
