# npm commands
npm commands  for reference.

- [npm commands](#npm-commands)
  - [Introduction](#introduction)
    - [Commands list](#commands-list)
      - [Initialize](#initialize)
      - [Help](#help)
      - [Config](#config)
      - [Install package](#install-package)
        - [Dependencies](#dependencies)
        - [Dev dependencies](#dev-dependencies)
        - [Global installation](#global-installation)
      - [Install all packages](#install-all-packages)
      - [Uninstall](#uninstall)
      - [Update](#update)
      - [Update all packages](#update-all-packages)
      - [Prune](#prune)
      - [List](#list)
      - [Scripts](#scripts)
  - [Technologies](#technologies)
  - [Project status](#project-status)
  - [Installation](#installation)
    - [Get repository](#get-repository)
  - [License](#license)

## Introduction
A repository with all npm commands.

### Commands list
#### Initialize
[Initialize command list](INITIALIZE.md "Initialize Commands")

#### Help
[Help command list](HELP.md "Help Commands")

#### Config
```npm
npm config set
```

```npm
npm config get
```

```npm
npm config delete
```

```npm
npm config list
```

```npm
npm config edit
```

```npm
npm get
```

```npm
npm set
```

#### Install package
##### Dependencies
```npm
npm install `package-name` --save
```
or
```npm
npm i `package-name` -S
```
##### Dev dependencies
```npm
npm install `package-name` --save-dev
```
or
```npm
npm i `package-name` -S-D
```
##### Global installation
```npm
npm install `package-name` -g --save
```
or
```npm
npm i `package-name` -g --save
```

#### Install all packages
```npm
npm install
```

#### Uninstall
```npm
npm uninstall `package-name` --save
```
or
```npm
npm un `package-name` --save
```
or
```npm
npm rm `package-name` --save
```

#### Update
```npm
npm update `package-name`
```
or
```npm
npm up `package-name`
```

#### Update all packages
```npm
npm update
```
or
```npm
npm up
```

#### Prune
```npm
npm prune
```
> Uninstalls the packages not mentioned in `package.json` file

#### List
```npm
npm list --depth `level`
```
> aliases: ls, la, ll


#### Scripts
```npm
npm `script-command` `app-name`
```

> -g flag for global

## Technologies
- npm
- Git

## Project status
> **Continuous**

## Installation
### Get repository
```git
git clone https://github.com/msaf9/npm.git
cd npm
```

## License
