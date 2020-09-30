# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

The `casadi` port has been added.

## [0.1.1] - 2020-07-14

### Added 
The `ipopt-binary` now installs a `Ipopt-config.cmake` file for compatibility with the [CasADi](https://web.casadi.org/) build (https://github.com/robotology/robotology-vcpkg-binary-ports/pull/10).

## [0.1.0] - 2020-03-04

First release of `robotology-vcpkg-binary-ports`, contains the following ports: 

| Port name | Official vcpkg triplet for which it is available |  Version |
|:---------:|:------------------------------------------------:|:--------:|
| ensenso-binary | `x64-windows`                | 2.3.1174 | 
| esdcan-binary | `x64-windows`                |  6.3.0 |
| ipopt-binary | `x64-windows`                | 3.12.7 |
