# Kubernetes Manifest Exporter

This script automates the process of exporting YAML manifests for specified Kubernetes resources within each namespace present in a Kubernetes cluster. It organizes the exported manifests into directories based on namespace and resource type.

## Explanation

The script performs the following tasks:

- Retrieves a list of namespaces from the Kubernetes cluster.
- Loops over each namespace.
- Creates a directory for each namespace.
- Loops over specified Kubernetes resource types.
- Retrieves a list of resources of each type within the current namespace.
- Writes YAML manifest files for each resource into the corresponding namespace directory.

## Requirements

- Python 3
- kubectl

## Notes

This script is designed to facilitate the export of YAML manifests for Kubernetes resources. It can be customized to include additional resource types or exclude specific namespaces. Ensure that you review and understand the script before executing it in your Kubernetes environment. Always verify permissions and access rights to avoid unintended modifications to your cluster. Feel free to modify the script according to your specific requirements.

