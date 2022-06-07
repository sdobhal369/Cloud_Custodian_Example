# Cloud_Custodian_Example
Cloud Custodian Example Files.

## Installation or setup Custodian (Linux/MacOs)

```
$ sudo apt install software-properties-common
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt update
$ sudo apt install python3.8
$ python --version

$ sudo apt install python3.8-venv
$ python3 -m venv custodian
$ source custodian/bin/activate
$ pip install c7n                              # This includes AWS support
$ custodian version 
```

## For Azure:

```
$ pip install c7n_azure 
```

## For GCP:

```
$ pip install c7n_gcp
```

## Note

```
# We have to run:

$ source custodian/bin/activate 

# every time whenver we want to use custodian on a fresh/new Terminal.
```
