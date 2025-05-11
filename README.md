# Hawk Backup - MongoDB

Simple docker image to auto-backup MongoDB database based on environment variables. Provides option to backup to local directory or to SFTP endpoint and basic alerting.

## Features

* 100% configured via environment variables
* Run standalone along with MongoDB docker container, thus eliminating the need for centralized backup solution.
* Send backups to local directory (via `/backups`) or to an external SFTP solution.
<!-- * Send basic alerting (Supported options: webhook, notifiers) -->

## Links

* [Setup](SETUP.md)
