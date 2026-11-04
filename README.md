# TagDecod

Purpose-built for Egyptian streets—detecting vehicles, localizing plates, and decoding dual-script license text on the fly.

## Requirements 

- Python 3.14.7 or later

#### Install Python using MiniConda 

1) Download and install MiniConda from [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)
2) Create a new environment using the following command:
```bash
$ conda create -n tag-decod python=3.14.7
```
3) Activate the environment
```bash
$ conda activate tag-decod
```

### (Optional) Setup your command line for better readability
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## Installation

### Install the required packages

```bash
$ pip install -r requirements.txt
```

### Setup the environement variables

```bash
$ cp .env.example .env
```

Set your environment variables in the `.env` file.