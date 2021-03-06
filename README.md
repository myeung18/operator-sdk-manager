# Operator SDK Manager
Version Manager for operator-sdk

## Overview
This project is used for managing multiple version of operator-sdk cli tool. It allows to install & switch between versions

## Usage:
``
  operator-sdk-manager [command]
``
### Example

 ```
   //Dowloading version v0.17.0
   $operator-sdk-manager install v0.17.0
   
   //Setting version v0.17.0
   $operator-sdk-manager set v0.17.0
   
   //Run operator-sdk
   $operator-sdk version 
   > operator-sdk version: "v0.17.0"
 ```
 

## Install the Operator SDK Manager CLI
Installation guide: [install-operator-sdk-manage](doc/install-operator-sdk-manager.md)


## Features

```
 * install:- install the version of operator-sdk
 * list :-  list all installed versions
 * search:-  search available version
 * set:- set as the operator-sdk version
 * uninstall:-  uninstall the version of operator-sdk
 * version:-  Prints the version of operator-sdk-manager
 ```
