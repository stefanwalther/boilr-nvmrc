# boilr-nvmrc

> Boilr template to create a dead simple .nvmrc file.

> **Retired / archived:** boilr templates predate AI coding tools and no longer make sense. This template is retired and this repository is archived read-only — it will receive no further updates. For new projects, use your AI coding tool to generate the files you need.

---

## Purpose
The following files are generated:

```
.
└── .nvmrc

0 directories, 1 file

```

## Installation
Install [boilr](https://github.com/tmrts/boilr) first.

Then use

```
$ boilr download stefanwalther/boilr-nvmrc <template-tag>
```

e.g.
```
$ boilr download stefanwalther/boilr-nvmrc boilr-nvmrc
```

## Usage
### Download the template

```
$ boilr template download stefanwalther/boilr-nvmrc <template-tag>
```

### Fork, modify locally and save it

```
$ git clone stefanwalther/boilr-nvmrc
```

cd into it, then

```
$ boilr template save $(PWD) <template-tag>

# e.g.
$ boilr template save $(PWD) nvmrc
```

if you have for force the local updates, use

```
$ boilr template save $(PWD) <template-tag> -f
```

### Use it

```
$ boilr template use boilr-nvmrc .
```

### Get all templates

Get a list of all - locally installed - templates:

```
$ boilr template list
```

## About

### Related projects
Some related projects:

- [boilr-editorconfig](https://www.npmjs.com/package/boilr-editorconfig): boilr template for an .editorconfig | [homepage](https://github.com/stefanwalther/boilr-editorconfig#readme "boilr template for an .editorconfig")
- [boilr-gitignore](https://www.npmjs.com/package/boilr-gitignore): boilr template for a .gitignore file. | [homepage](https://github.com/stefanwalther/boilr-gitignore#readme "boilr template for a .gitignore file.")

### Author
**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)
* [github.com/stefanwalther](http://github.com/stefanwalther)
* [LinkedIn](https://www.linkedin.com/in/stefanwalther/)
* [qliksite.io](http://qliksite.io)

### License
MIT
