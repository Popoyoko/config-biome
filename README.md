# Biome Configuration

Welcome to the repository for the Popoyoko Biome configuration! This repository contains the setup and configuration files for Biome, a tool for linting, formatting, and more. This configuration is tailored for use in various Popoyoko projects and includes rules and settings that adhere to our coding standards.

## Table of Contents

- [Biome Configuration](#biome-configuration)
  - [Installation](#installation)
  - [Run the config in your project](#run-the-config-in-your-project)
  - [Custom Rules and Settings](#custom-rules-and-settings)

## Installation

To use this Biome configuration, just paste this in yout terminal

   ```bash
   bun add --dev --exact @biomejs/biome
   bun add git@github.com:Popoyoko/config-biome.git
   bunx biome init
   sed -i '2s/^/    "extends": ["configuration\/biome"],\n/' biome.json
   ```

## Run the config in your project

Your project is ready to use the Popoyoko's biome configuration


## Custom Rules and Settings

The `biome.json` file contains custom rules and settings for the Biome tool. Feel free to modify this file according to your project's needs. For a full list of available options, refer to the [Biome documentation](https://biome.dev/docs).