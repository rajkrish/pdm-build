# Introduction

This repository hosts build scripts to various containers with enhanced tools and configuration for a select number of packages.

View the readme.md file for each subdirectory for details.

# WikiJS - Alma

Execute the following commands - 

```bash
$  cd wikijs-alma
$  podman build  --layers --force-rm --no-cache --pull --tag docker.io/rajkrish1/wikijs:latest-alma -f Containerfile . 
$  podman login docker.io
$  podman push docker.io/rajkrish1/wikijs:latest-alma


```

