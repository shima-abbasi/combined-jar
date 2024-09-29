# Multi-Module JAR Combiner

This Maven project combines multiple module JAR files into a single JAR file using the Antrun plugin.

## Introduction

This project demonstrates how to combine multiple module JAR files into one JAR file using the Antrun plugin in a Maven project. This can be useful for simplifying deployment and distribution of multi-module projects.

## Features

- Combines multiple JAR files into a single JAR
- Uses Maven for project management
- Utilizes the Antrun plugin for custom build tasks

## Prerequisites

- Java 8 or higher
- Maven 3.6.0 or higher

## Installation

Clone the repository:
```sh
git clone https://github.com/shima-abbasi/multi-module-jar-combiner.git
cd multi-module-jar-combiner
```

## Usage

To combine the JAR files, run the following Maven command:
```sh
mvn clean package