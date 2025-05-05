# NCC 2025

The official CTF from NCC 2025 is now public!

In the second edition of NCC (North Coding Challenge – 2025), you will explore a variety of IT fields through a personalized Linux-based CTF.
This is the same version used during the live NCC 2025 event, and it's now open to anyone who wants to try it! Try it at your own pace and learn something new.

**Built by [@hypertrophic](https://github.com/hypertrophic)**, proudly for ECDH.

---

## Overview
### Format
The North Coding Challenge follows a Capture The Flag (CTF) format hosted on a Linux machine. Each level is assigned to a unique user in the machine. Solving the challenge associated with a user will give you a flag, which also serves as the password to access the next user's environment.

### Level Structure
Level 0: `user0` hosts the first challenge
  Solving it reveals `pswd1`
  
Level 1: Login as `user1` using `pswd1`
  Solving this provides pswd2
  
Level 2: Login as `user2` using `pswd2`
  ... and so on.

Each level is isolated and authored individually.

### Areas Covered
Unlike traditional CTFs that focus solely on cybersecurity, this edition of NCC aims to provide a broader exploration of the IT landscape. The challenges will touch on:
Linux fundamentals and system usage
Cryptography
Cybersecurity concepts and practices
Networking principles and tools
Coding and scripting techniques

## Quick Start

1. Install [Docker](https://www.docker.com/products/docker-desktop/) if you don't have it.
  
2. Pull the image:
```bash
docker pull wissamecdh/ncc-2025
```
3. Run the following command:
```bash
docker run -it wissamecdh/ncc-2025
```
## Login:
Username: ncc0
Password: ncc0
