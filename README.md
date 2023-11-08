# Beers Dataset Search Examples

## Contents
1.  [Summary](#summary)
2.  [Approach](#approach)
3.  [Features](#features)
4.  [Prerequisites](#prerequisites)
5.  [Usage](#usage)


## Summary <a name="summary"></a>
This demonstrates a technique for loading normalized data into Redis without denormalization.  It further demonstrates some sample search queries on that data.

## Approach <a name="approach"></a>
Two normalized datasets in CSV format are loaded into Redis as JSON objects.  Association between the two sets (breweries and beer types) is made via JSON array of beers in the brewery JSON boject.

## Features <a name="features"></a>
- Redis JSON + Search

## Prerequisites <a name="prerequisites"></a>
- Docker Compose

## Usage <a name="usage"></a>
Simply follow the Jupyter notebook steps.
