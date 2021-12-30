# Terraform - Docker mod for code-server

This mod adds the Terraform binary and extension to code-server, to be installed/updated during container start.

In code-server docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:code-server-terraform`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:code-server-terraform|linuxserver/mods:code-server-zsh`
