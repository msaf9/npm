# npm Commands for reference
npm commands.

## Table of contents
1. Introduction
2. Technologies
3. Project status
4. Installation
5. License

## Introduction
This repository is for experimenting with npm commands.

### Played command list
#### Initialize
```npm
npm init --yes
npm init -y
```

#### Help
```npm
npm help
npm help `keyword`
```

#### Install package
##### Dependencies
```npm
npm install `package-name` --save
npm i `package-name` -S
```
##### Dev dependencies
```npm
npm install `package-name` --save-dev
npm i `package-name` -S-D
```
##### Global installation
```npm
npm install `package-name` -g --save
npm i `package-name` -g --save

```
#### Uninstall
```npm
npm uninstall `package-name` --save | -g flag for global
npm un `package-name` --save
npm rm `package-name` --save
```

#### Update
```npm
npm update `package-name` | -g flag for global
npm up `package-name`
```

#### Prune
```npm
npm prune
- Uninstalls the packages not mentioned in package.json file
```

#### List
```npm
npm list --depth `level` | -g flag for global
aliases: ls, la, ll
```

#### Install all packages
```npm
npm install
```

#### Update all packages
```npm
npm update | -g flag for global
npm up
```

#### Scripts
```npm
npm `script-command` `app-name`
```

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
