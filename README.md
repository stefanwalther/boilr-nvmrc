# boilr-nvmrc

> Boilr template to create a dead simple .nvmrc file.

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

 

### Author
**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)  
* [github.com/stefanwalther](http://github.com/stefanwalther) 
* [LinkedIn](https://www.linkedin.com/in/stefanwalther/) 
* [qliksite.io](http://qliksite.io)

### License
MIT

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on October 31, 2018._

