# Jitsi Meet on Podman

[Jitsi](https://jitsi.org/) is a set of Open Source projects that allows you to easily build and deploy secure videoconferencing solutions.

[Jitsi Meet](https://jitsi.org/jitsi-meet/) is a fully encrypted, 100% Open Source video conferencing solution that you can use all day, every day, for free — with no account needed.

This repository contains the necessary files to run a Jitsi Meet stack in rootless mode on [Podman](https://podman.io/) using [Quadlet](https://docs.podman.io/en/latest/markdown/podman-systemd.unit.5.html) to generate the [systemd](https://systemd.io/) unit files.

All images are published on [DockerHub](https://hub.docker.com/u/jitsi/).

## Prerequisites 
Podman version 4.4 or later

## Installation

Clone this repository to `~/.config/containers/systemd/`

Follow the instructions [here](https://jitsi.github.io/handbook/docs/devops-guide/devops-guide-docker) until step 5, then carry on with the rest of the instructions below.

Copy the `.env` file you created in steps 2 and 3 to `~/.config/containers/systemd/jitsi/`

Now reboot the host to automatically pull the images and start the containers
