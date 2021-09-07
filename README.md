# packer-nginx-AWS
Packer AWS on nginx

## Description
Create a nginx EBS on AWS with Packer

## Pre-requirements

* [Packer](https://www.packer.io/downloads)


## How to use this repo

- Clone
- Build

---

### Clone the repo

```
git clone https://github.com/ayahmuhamed/packer-nginx-AWS-/

```

### Change directory

```
cd packer-aws-nging
```

### Validate the template

```
packer validate aws-ubuntu.pkr.hcl
```

### Build the image

```
packer build aws-ubuntu.pkr.hcl
```
