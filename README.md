# devops

This project provides a set of tools for deploying Nitrogen services based on CoreOS.

## Getting Started

A service environment is defined via a set of JSON description files. This project includes templates for a staging environment and a small production environment in enviroments/staging and environments/production. You can use these as templates for building out your own environments. Simply copy the whole directory and then edit the config.json and etcd.json files.

Config.json is

## Nitrogen Project

The Nitrogen project is housed in a set of GitHub projects:

1. [service](https://github.com/nitrogenjs/service): Core platform responsible for managing principals, security, and messaging.
2. [client](https://github.com/nitrogenjs/client): JavaScript client library for building Nitrogen devices and applications.
3. [admin](https://github.com/nitrogenjs/admin): Web admin tool for working with the Nitrogen service.
4. [device](https://github.com/nitrogenjs/devices): Device principals for common pieces of hardware.
5. [commands](https://github.com/nitrogenjs/commands): CommandManagers and schemas for well known command types.
6. [cli](https://github.com/nitrogenjs/cli): Command line interface for working with the Nitrogen service.
7. [reactor](https://github.com/nitrogenjs/reactor): Always-on hosted application execution platform.
8. [apps](https://github.com/nitrogenjs/apps): Project maintained Nitrogen applications.
