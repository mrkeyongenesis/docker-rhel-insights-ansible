# RHEL Linux 2025 Ansible Test Image

RHEL Linux 2025 Docker container for Ansible playbook and role testing.

## Tags

  - `latest`: Latest stable version of Ansible.

The latest tag is a lightweight image for basic validation of Ansible playbooks.

## How to Build

This image is built on Docker Hub automatically any time the upstream OS container is rebuilt, and any time a commit is made or merged to the `master` branch. But if you need to build the image on your own locally, do the following:

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. `cd` into this directory.
  3. Run `docker build -t rhel2025-ansible .`



Feel free to replace any placeholders like `yourusername` with your actual Docker Hub username. Let me know if you need further adjustments!