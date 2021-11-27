Awesome OpenSearch [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
=============

<img src="https://opensearch.org/assets/img/opensearch-logo-themed.svg" height="64px">

A community driven list of useful OpenSearch stuff.  Inspired by [awesome-python](https://github.com/vinta/awesome-python). Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

Projects with over 500 stargazers are in bold.

## Table of Contents

- [Awesome OpenSearch ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-opensearch)
  - [Table of Contents](#table-of-contents)
  - [Plugins](#plugins)
  - [Tools](#tools)
  - [Articles](#articles)
  - [Support](#support)
- [Contributing](#contributing)

## Plugins

* [IK Analysis for OpenSearch](): The IK Analysis plugin integrates Lucene IK analyzer (http://code.google.com/p/ik-analyzer/) into opensearch, support customized dictionary. This is a port of [medcl's IK Analysis](https://github.com/medcl/elasticsearch-analysis-ik).
* [OpenNLP Ingest Processor](https://github.com/aparo/opensearch-ingest-opennlp): This processor is doing named/date/location/'whatever you have a model for' entity recognition and stores the output in the JSON before it is being stored. This is a port of [spinscale's Elasticserch OpenNLP ingest plugin](https://github.com/spinscale/elasticsearch-ingest-opennlp).
* [Langdetect Ingest Processor](https://github.com/aparo/opensearch-ingest-langdetect): Ingest processor doing language detection for fields. Port of https://github.com/spinscale/elasticsearch-ingest-langdetect
* [Pinyin Analysis for OpenSearch](https://github.com/aparo/opensearch-analysis-pinyin): This Pinyin Analysis plugin is used to do conversion between Chinese characters and Pinyin. Port of https://github.com/medcl/elasticsearch-analysis-pinyin
* [Prometheus Exporter Plugin](https://github.com/aparo/opensearch-prometheus-exporter): This is a builtin exporter from OpenSearch to *Prometheus* based on the code of Vincent Van Hollebeke and others at https://github.com/vvanholl/elasticsearch-prometheus-exporter . It collects all relevant metrics and makes them available to Prometheus via the OpenSearch REST API. 
* [Learning to Rank Plugin](https://github.com/aparo/opensearch-learning-to-rank): This is a port of https://github.com/o19s/elasticsearch-learning-to-rank to work with OpenSearch. It's a rewrite of some parts to be able to work with OpenSearch.
* [STConvert Analysis](https://github.com/aparo/opensearch-analysis-stconvert): STConvert is analyzer that convert Chinese characters between Traditional and Simplified. Port of https://github.com/medcl/elasticsearch-analysis-stconvert



## Tools

* [ElasticSearch OpenSearch Migration Scripts](https://github.com/aparo/elasticsearch-opensearch-migration-scripts): Scripts useful to migrate code/plugins from ElasticSearch to OpenSearch

## Support

* [Official Web Site](https://opensearch.org)
* [Official Forum](https://discuss.opendistrocommunity.dev/)


# Contributing
* Make sure you are about to post a valuable resource that belongs to this list
* Do NOT group ++Add and --Remove changes in same PR. Make them separate pull requests
* Use spellchecker
* All spelling and grammar corrections are welcome (except for the rule above)
* Fork this repo, do your edits, send the pull request
* Feel free to create any new sections
* Do not even try to add this repo to any awesome-awesome-* lists 
