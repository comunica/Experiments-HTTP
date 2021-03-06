# Comunica HTTP Actors Experiment

This is an experiment to compare the performance of the different HTTP actors within [Comunica](https://github.com/comunica/comunica) over a [Triple Pattern Fragments server](https://github.com/LinkedDataFragments/Server.js/).

This experiment was created with [jbr](https://github.com/rubensworks/jbr.js).

Example results:

![Example output](https://raw.githubusercontent.com/comunica/Experiments-HTTP/master/example_output/plot_queries_data.svg)

## Requirements

* [Node.js](https://nodejs.org/en/) _(1.12 or higher)_

## Installation

Before this experiment can be used, its dependencies must be downloaded first:

```bash
$ npm install
```

## Usage

Generate the dataset and queries:

```bash
$ npm run jbr -- prepare
```

Run the experiment locally:

```bash
$ npm run jbr -- run
```

The `output/` directory will now contain all experiment results.

## Usage if jbr is installed globally

If [jbr is installed globally](https://github.com/rubensworks/jbr.js/tree/master/packages/jbr#installation),
you can prepare and run this experiment as follows:

```bash
$ jbr prepare
$ jbr run
```
