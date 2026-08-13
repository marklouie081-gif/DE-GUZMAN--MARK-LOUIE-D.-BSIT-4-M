# Laboratory 02 – Build the Cloud Infrastructure Blueprint

## Mission Overview

This laboratory activity focused on investigating the infrastructure of a Linux server running in the cloud using the KillerCoda Playground. The mission involved examining compute, storage, networking, and operating system resources and documenting the findings. It also included comparing the infrastructure services of AWS, Microsoft Azure, and Google Cloud Platform and designing a simple cloud infrastructure diagram.

## Objectives

* Explain the major components of cloud infrastructure.
* Investigate hardware and software resources in a Linux environment.
* Differentiate compute, storage, networking, and identity resources.
* Interpret the relationship between cloud infrastructure components.
* Create technical documentation using Markdown.
* Continue building a structured GitHub Cloud Computing Portfolio.

## Cloud Infrastructure Components

### Compute Resources

The CPU and CPU cores provide the processing power required to execute commands, applications, and services on the Linux server.

### Storage Resources

Disk storage provides space for the operating system, applications, files, and other data used by the server.

### Networking Resources

Networking allows the cloud server to communicate with users, other systems, and services through network connections and an IP address.

### Operating System

The Linux operating system manages the server's hardware resources and provides the environment for running applications and executing commands.

## Tools Used

* KillerCoda Playground
* Linux Terminal
* GitHub
* Web Browser
* Markdown
* Draw.io / Diagramming Tool

## Linux Commands Executed

The following Linux commands were used to investigate the cloud server:

```bash
cat /etc/os-release
uname -r
lscpu | grep "Model name"
nproc
free -h
lsblk
df -h
hostname
hostname -I
```

These commands were used to determine the operating system, kernel version, CPU model, CPU cores, RAM, disk capacity, mounted file systems, hostname, and IP address.

## Skills Learned

Through this laboratory activity, I learned how to investigate a Linux cloud server using command-line tools. I also learned how to identify cloud infrastructure components, compare equivalent services between AWS, Microsoft Azure, and Google Cloud, create a basic cloud architecture diagram, and organize technical documentation using Markdown and GitHub.

## Challenges Encountered

One challenge I encountered was understanding the different names used by AWS, Microsoft Azure, and Google Cloud for similar infrastructure services. Another challenge was interpreting the information returned by Linux commands and organizing the results into a clear technical report. Creating and organizing the required files and screenshots in the GitHub repository also required careful attention to the required folder structure.

