![](https://github.com/SergeyMi37/zapm-addcmd/blob/master/doc/zapm-dark.png)

## zapm-addcmd
[![Gitter](https://img.shields.io/badge/Available%20on-Intersystems%20Open%20Exchange-00b2a9.svg)](https://openexchange.intersystems.com/package/zapm-addcmd-1)

An example of adding new commands to the zapm shell.

## Installation with ZPM

zpm:USER>install zapm-addcmd

## Installation with Docker

## Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.

## Installation 
Clone/git pull the repo into any local directory

```
$ git clone https://github.com/SergeyMi37/zapm-addcmd.git
```

Open the terminal in this directory and run:

```
$ docker-compose build
```

3. Run the IRIS container with your project:

```
$ docker-compose up -d
```

## How to Test it
Open IRIS terminal:

```
$ docker-compose exec iris iris session iris
USER>
USER>zapm "cmd"

```

## Additional commands.
```
USER>zapm "StopProd"
...
USER>zapm "StartProd"

```
![](https://github.com/SergeyMi37/zapm-addcmd/blob/master/doc/Screenshot_2.png)