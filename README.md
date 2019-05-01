# Scoop Ansible module

[![Build Status](https://dev.azure.com/jamiemagee/jamiemagee/_apis/build/status/JamieMagee.ansible-win-scoop?branchName=master)](https://dev.azure.com/jamiemagee/jamiemagee/_build/latest?definitionId=4&branchName=master)

An Ansible module to manage packages using [Scoop](https://scoop.sh/)

## Options

| **parameter** | **required** | **default** | **choices**     |
|---------------|--------------|-------------|-----------------|
| name          | yes          |             |                 |
| state         | yes          | present     | present, absent |
