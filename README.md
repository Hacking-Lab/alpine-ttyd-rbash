# Alpine Base 
## Introduction
This is the alpine ttyd web shell rbash image of the Hacking-Lab CTF system, based on hackinglab/alpine-base:latest

## Specifications
* based on alpine latest
* with s6 startup handling
* with user creation
* with or without known passwords for root and non-root user
* with dynamic ctf flag handling in `environment variables`
* with dynamic ctf flag handling in `files`
* provides rbash terminal via web shell
