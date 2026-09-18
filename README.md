# Power System Notebooks, 1<sup>st</sup> edition

Welcome to the main repository of Power Systems and High Voltage for electrical engineers course at HEIG-VD.

This repository is for the courses, all the tutorials and installation information is on the public repository the repository [python_installation_and_tutorials](https://github.com/heig-vd-ie/python_installation_and_tutorials/tree/main#).

## Installation and clean setup

To have a clean installation, please follow the [detailed installation instructions bigining in this link](https://github.com/heig-vd-ie/python_installation_and_tutorials/blob/main/README.md).

If you get many problems with your git branch or repo, please get in touch with [Luca](mailto:luca.tomasini@heig-vd) or [Thierry](mailto:thierry.fracheboud@heig-vd.ch).

> [!IMPORTANT]
> For the package installation, run the ***make*** commande as explain in the following section.


## How to Run

1. After you have followed the installation instruction in previous section and having forked the repository, clone it on your computer, create your personnal folder inside as explain in [work on a github project](https://github.com/heig-vd-ie/python_installation_and_tutorials/blob/main/INSTALL.md#work-on-a-github-project).
1. On the linux terminal (on vscode or on windows terminal with ubuntu), install `make` (if not already installed): 
```sh
    sudo apt update
    sudo apt install make
```
1. Then Initialize the project and create the virtual environment: 
```sh
    make
```
1. If you delete your `.venv`, you can run `make` to install everything from beginning.

## Remarks

This template currently works on Linux-based systems (including WSL).
On macOS, some Makefile targets may not work.
To see all available Makefile commands, open the Makefile directly to see what’s going on under the hood.

## Contributors

This repository and the code were created by the following people from the Institut des Énergies at HEIG-VD:

- Luca Tomasini, Chargé de Ra&D HES
- Antoine Giraldi, Collaborateur scientifique HES
- Thierry Fracheboud, Assistant HES-SO & Research Engineer
- Mokhtar Bozorg, Professor HES-SO
- Marc Pellerin, Senior lecturer HES-SO
