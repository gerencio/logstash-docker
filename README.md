[![Build Status](https://travis-ci.org/elastic/logstash-docker.svg?branch=master)](https://travis-ci.org/elastic/logstash-docker)

## Description

This repository contains the official [Logstash][logstash] Docker image from
[Elastic][elastic].

Documentation can be found on the [Elastic website](https://www.elastic.co/guide/en/logstash/current/docker.html).

[logstash]: https://www.elastic.co/products/logstash
[elastic]: https://www.elastic.co/

## Supported Docker versions

The images have been tested on Docker 1.13.0.

## Requirements
A full build and test requires:
* Docker
* GNU Make
* Python 3.5 with Virtualenv

## Contributing, issues and testing

Acceptance tests for the image are located in the `test` directory, and can
be invoked with `make test`.

This image is built on [Ubuntu 16.04][ubuntu-1604].

[ubuntu-1604]: https://github.com/tianon/docker-brew-ubuntu-core/blob/188bcceb999c0c465b3053efefd4e1a03d3fc47e/xenial/Dockerfile
