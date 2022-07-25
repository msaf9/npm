# npm Commands

- [npm Commands](#npm-commands)
    - [Initialize](#initialize)
    - [Help](#help)
    - [Install package](#install-package)
        - [Dependencies](#dependencies)
        - [Dev dependencies](#dev-dependencies)
        - [Global installation](#global-installation)
    - [Uninstall](#uninstall)
    - [Update](#update)
    - [Prune](#prune)
    - [List](#list)
    - [Install all packages](#install-all-packages)
    - [Update all packages](#update-all-packages)
    - [Scripts](#scripts)

## Initialize
> npm init --yes
>
> npm init -y

## Help
> npm help
>
> npm help `keyword`

## Install package
### Dependencies
> npm install `package-name` --save
>
> npm i `package-name` -S

### Dev dependencies
> npm install `package-name` --save-dev
>
> npm i `package-name` -S-D

### Global installation
> npm install `package-name` -g --save
>
> npm i `package-name` -g --save

## Uninstall
> npm uninstall `package-name` --save | -g flag for global
>
> npm un `package-name` --save
>
> npm rm `package-name` --save

## Update
> npm update `package-name` | -g flag for global
>
> npm up `package-name`

## Prune
> npm prune
>
> - Uninstalls the packages not mentioned in package.json file

## List
> npm list --depth `level` | -g flag for global
>
> aliases: ls, la, ll

## Install all packages
> npm install

## Update all packages
> npm update | -g flag for global
>
> npm up

## Scripts
> npm `script-command` `app-name`