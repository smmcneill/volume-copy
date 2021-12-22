# Purpose
This is a simple exercise that shows how one might spin up a container for the purpose of grabbing a file from the container

## Details
Given an empty host directory which is mounted to an empty container folder, we can then copy files into the guest mount which persist in the host directory after the container dies.

Run the example:
```bash
docker compose up
```