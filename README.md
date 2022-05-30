# npm commands
npm commands  for reference.

## Table of contents
1. Introduction
2. Technologies
3. Project status
4. Installation
5. License

## Introduction
A repository with all npm commands.

### Commands list
#### Initialize
```npm
npm init --yes
```
or
```npm
npm init -y
```

#### Help
```npm
npm help
```
or
```npm
npm help `keyword`
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

#### Install all packages
```npm
npm install
```

#### Update all packages
```npm
npm update
```
or
```npm
npm up
```

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
