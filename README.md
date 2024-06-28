# Circom Docker

Docker image for circom and snarkjs

Circom Version : 2.1.6

### Installation

You can pull the image from docker hub

```bash
docker pull saleel/circom:2.1.6
```

### Building Manually

```bash
docker build -t circom .
```

### Usage
Both `circom` and `snarkjs` are available as a global command

```bash
docker run circom circom -V
docker run circom snarkjs ..
```
