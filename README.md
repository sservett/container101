# Containers 101

Welcome to the Containers 101 workshop! 

## Install Docker

Before you start running any of the exercises, make sure you have downloaded Docker CE from the [Docker store](https://store.docker.com/search?type=edition&offering=community).

### Considerations for Windows users

Docker CE is only compatible with Microsoft Windows 10 Professional or Enterprise 64-bit. For people running other versions of Windows, you will need to install [Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_windows/) 

If you can install Docker CE for Windows, then after you have installed Docker, you will need to ensure that you [switch to Linux Containers](https://docs.docker.com/docker-for-windows/#switch-between-windows-and-linux-containers).

## Registering for a free IBM Cloud Account

1. If you don't have one already, sign up for a free IBM Cloud Account [here](https://ibm.biz/containers-101).

2. Verify your account via the email the platform sends you.

3. Log in to your IBM Cloud Account.

## Install the IBM Cloud CLI

For the last part of tthe workshop, we will be using IBM Container Registry. To run this part of the workshop, you will need to install IBM Cloud CLI and then configure it to use Container Registry:

1. Go to [this docs link](https://console.bluemix.net/docs/cli/reference/bluemix_cli/get_started.html#getting-started) and follow the short instructions to download and install the CLI.

2. Install the Container Registry plug-in:

`bx plugin install container-registry -r Bluemix`

## Hands-on workshop

Now you're ready to go!

After completing the workshops, you will have experience with creating a Docker image from a Docker file, managing Docker containers (running, stopping, removing, viewing), working inside Docker containers, pushing and pulling Docker images to and from registries and working with persistent data.

To begin, let's start of with the [first exercise](./1_Create_view_pull_images) where you will create your first Docker image! You will also learn how to pull other existing Docker images from DockerHub and inspect the history of image.
