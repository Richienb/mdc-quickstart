# MDC Quickstart

An easy way to start using **Material Design Components for the Web**. This codebase is adapted from Google's [Getting Started](https://material.io/develop/web/docs/getting-started/) guide on the official Material Design website.

## How to start

There are three ways to start using the quickstart.

- Fork this repository
- [Download](https://github.com/Richienb/mdc-quickstart/archive/master.zip) this repository as a zip
- Clone this repository:
`git clone https://github.com/Richienb/mdc-quickstart.git`

## Installing the dependencies

This repository uses yarn as the package manager instead of the classic npm.

Yarn can be installed by running `npm install yarn --global`.

If you want to use npm instead, simply delete the `yarn.lock` file: `rm -f yarn.lock`.

To install the dependencies, run `yarn install`. If you're using npm, run `npm install`.

## Adding dependencies

To add dependencies with yarn, run `yarn add <NAME> --dev` or with npm, `npm install <NAME> --save-dev`.

## Removing dependencies

To remove dependencies with yarn, run `yarn remove <NAME>` or with npm, `npm uninstall <NAME>`

## Starting the development server

To start the development server, run `npm start`. You will then be able to preview the website live at [127.0.0.1:8080](http://127.0.0.1:8080)

## Building the website

To build the website, run `npm run build`.
