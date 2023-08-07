English | [简体中文](./README.md)

<p align="center"><img width="100" src="https://vuejs.org/images/logo.png"></p>
<h2 align="center">wpm-cli（A simple front-end CLI tool）</h2>
<p align="center"><b>Generate personal front-end scaffolding based on Node construction（vue）</b></p>
# 目录

- [feature](#feature)
- [QuickStart](#QuickStart)
  - [Install](#Install)
  - [Usage](#Usage)
- [Contribution](#Contribution)
- [Maintainers](#Maintainers)
- [License](#license)

### feature

- Easy to use
- Support custom template addition and deletion

### QuickStart

### Install

```bash
$ npm i wpm-cli -g               # install cli
$ omi init my-app     # init project, you can also exec 'omi init' in an empty folder
$ cd my-app           # please ignore this command if you executed 'omi init' in an empty folder
$ wpm init [templateName] [yourProjectName]
```

Install description:

The default scaffolding template name is vue-admin

> wpm init vue-admin [yourProjectName]

### New template usage

```bash
wpm add
# Select template and template address (github address)
```

![wpm-add](./img/readme_add.png)

-Note: The template address is the git repository name. The master branch is pulled by default.
If you want to specify a branch, please use **owner / name # my-branch**
![wpm-add](./img/readme_gitAddress.png)

### Remove template usage

```bash
wpm delete
# 选择模板
```

![wpm-add](./img/readme_delete.png)

### See all template usage

```bash
wpm list
```

### Initialize project scaffolding usage

```bash
wpm init 或者 wpm init [templateName] [yourProjectName]
```

![wpm-add](./img/readme_init.png)

## Contribution

- baiqi

## Maintainers

- [baiqi](https://github.com/baiqi-2019)

## License

- [MIT](https://opensource.org/licenses/MIT)
