# aur-apps

Use AUR (Arch User Repository) on Ubuntu Linux

在 Ubuntu 使用 Arch Linux 的 AUR

# Initialize

    wget https://github.com/shellexy/aur-apps/raw/main/aur-apps
    bash aur-apps init

# Usage

    aur-apps run                    # run a command in aur sandbox
    aur-apps bash                   # run bash shell in aur sandbox
    aur-apps list      <package(s)> # list packages based on package names
    aur-apps search    <keyword(s)> # search in package descriptions
    aur-apps show      <package(s)> # show package details
    aur-apps install   <package(s)> # install packages
    aur-apps remove    <package(s)> # remove packages
    aur-apps files     <file(s)>    # search files in packages
    aur-apps showfiles <package(s)> # list files in packages
    aur-apps status                 # show status
    aur-apps update                 # update list of available packages
    aur-apps upgrade                # upgrade the system by installing/upgrading packages
    aur-apps upgrade_self           # upgrade this tool


# example

    aur-apps search notepad
    aur-apps install notepadqq
    aur-apps notepadqq
    aur-apps status
