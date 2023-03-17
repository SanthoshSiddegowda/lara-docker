# Laravel Installation with docker

# Docker Desktop Installation

1. Go to the Docker Desktop download page: [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)
2. Click on the **Download** button for your operating system.
3. Double-click on the downloaded installer package to start the installation process.
4. Follow the instructions in the installation wizard to install Docker Desktop.
5. Once the installation is complete, you should see the Docker icon in your system tray or menu bar.


    ### System Requirements
    
    Before installing Docker Desktop, make sure your system meets the following requirements:
    
    - **Windows**: Windows 10 64-bit: Pro, Enterprise, or Education (Build 16299 or later).
    - **Mac**: macOS Yosemite 10.10 or later.
    - **Linux**: Ubuntu 20.04 LTS, 18.04 LTS, Debian 10, Fedora 32, or CentOS 7.
    
    Docker Desktop also requires virtualization support to run containers. On Windows, this is provided by Hyper-V. On macOS, this is provided by the built-in Hypervisor Framework. On Linux, this is provided by KVM or VirtualBox.


## Running the configuration


Run this command for the initial app configuration

```bash
make configure
```

Build the docker services with

```bash
make build
```

Installing the dependencies

```bash
make install
```
## Running the Application

Run this command to start the app

```bash
make up
```

After completion, verify by visiting the endpoint below.

```bash
http://localhost:8010/
```