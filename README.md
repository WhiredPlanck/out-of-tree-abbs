# Out-of-tree ABBS/ACBS
This repo contains build configurations and scripts for some packages that are unable to be made available in the official AOSC OS [repository](https://repo.aosc.io/).

## Usage
1. You need to install `ciel` on your system.
    - For Arch Linux:
    ```shell
    $ paru ciel # or yay -S ciel
    ```
    AOSC OS has installed `ciel` by default.

2. Make a new dir, then clone this repo into it.
    ```shell
    $ mkdir -pv <dir_name>
    $ cd <dir_name>
    $ git clone https://github.com/WhiredPlanck/out-of-tree-abbs TREE
    ```
3. Then create a ciel workspace, follow the guide to configurate.
    ```shell
    $ sudo ciel new
    ```

4. Build the package(s).
    ```shell
    ciel build -i <INSTANCE> <PACKAGE_NAME_1> <PACKAGE_NAME_2> # ...
    ```
## ATTENTION
- `GPL-2.0 License` can only apply to the **build scripts** here.
- I doesn't and will not provide any binary packages, please follow the **Usage** above to build on yourself.
- This repository is just created for my personal needs without any guarantee.
