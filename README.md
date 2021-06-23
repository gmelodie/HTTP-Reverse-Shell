# HTTP-Reverse-Shell

![https://img.shields.io/github/stars/apurvsinghgautam/HTTP-Reverse-Shell](https://img.shields.io/github/stars/apurvsinghgautam/HTTP-Reverse-Shell) ![https://img.shields.io/github/forks/apurvsinghgautam/HTTP-Reverse-Shell](https://img.shields.io/github/forks/apurvsinghgautam/HTTP-Reverse-Shell)

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

A fork of [HTTP Reverse Shell](https://github.com/apurvsinghgautam/HTTP-Reverse-Shell) adapted to Python 3 and self-contained (no need for external libraries). It creates a reverse shell based over HTTP (dodges deep packet inspection).

# Prerequisites
- Python 3 (on both the attacker and the target machine

# Usage
1. Change `ATTACKER_IP` to the actual IP of the attacker on `client.py`
2. Change `ATTACKER_PORT` on both `client.py` and `server.py` (or you can just use the default)
3. Transfer `client.py` to the target machine
4. Run `server.py` on the attacker machine
```
python3 server.py
```
5. Run `client.py` on the target machine
```
python3 client.py
```
6. Connection will be established
