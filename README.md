# tanzu-bootstrap
Released on Monday February 13th, 2023

Ansible playbooks for creating a Tanzu Bootstrap server. These are designed to be run locally
on a Ubuntu Linux VM/machine.

- prereqs.yml: Ansible playbook to pre-install all the Docker bits necessary
- tanzu_pkgs.yaml: Installs the Tanzu CLI and kubectl for the specific version
of Tanzu Kubernetes Grid. Uses a pre-configured S3 bucket to download the files
from a private S3 bucket. You will need to setup this download yourself.
