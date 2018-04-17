# Setting up your development environment

This is a brief note on how to set up your ML/DL development environment on your
own workstation for success. You do not necessarily require a powerful laptop or
workstation as ultimately your goal for doing ML/DL on your workstation is to
figure out what sort of experiments to run. Not fitting large models but rather
to run a set of tests and figure out answers to questions such as:

- What data to use
- How to prepare data
- What models to use
- What configuration to consider and use

Once these preliminary questions have been answered, you can then move on to
running larger experiments on servers and clusters. Just not on your
workstations. This may mean that you use a smaller data samples or scale down
your model runs. Work with what you have.

## The absolute minimum

We support Windows 10 running WSL, macOS and Linux as the operating systems of choice in the
curriculum. If you are running anything else, please consider running a Linux
distribution such as Ubuntu as a VM and use that as your development
environment.

At the minimum, please install the following:

1. [Anaconda Distribution](https://www.anaconda.com/distribution/). This is a
   popular distribution of Python with the necessary scientific and ML/DL
   packages.
2. A decent text editor. If you do not have any preference yet, [Visual Studio
   Code](https://code.visualstudio.com) is recommended.
3. Git for version control. Please install the package provided by your
   operating system.
4. Make for automation. Please install the package provided by your operating
   system.

## Next steps

In later weeks, we will cover things such as containers and orchestration. For
the most part, most of the tasks will be run in our cluster environment but you
are also recommended to install Docker for your operating system. Please refer
to the [install instructions](https://www.docker.com/get-docker) and install it on your workstation.



