<!---
Copyright © 2020 Interplanetary Database Association e.V.,
BigchainDB and IPDB software contributors.
SPDX-License-Identifier: (AGPL-3.0-or-later AND CC-BY-4.0)
Code is AGPL-3.0-or-later and docs are CC-BY-4.0
--->

<!--- There is no shield to get the latest version
(including pre-release versions) from PyPI,
so show the latest GitHub release instead.
--->

[![Codecov branch](https://img.shields.io/codecov/c/github/bigchaindb/bigchaindb/master.svg)](https://codecov.io/github/bigchaindb/bigchaindb?branch=master)
[![Latest release](https://img.shields.io/github/release/bigchaindb/bigchaindb/all.svg)](https://github.com/bigchaindb/bigchaindb/releases)
[![Status on PyPI](https://img.shields.io/pypi/status/bigchaindb.svg)](https://pypi.org/project/Planetmint/)
[![Travis branch](https://img.shields.io/travis/bigchaindb/bigchaindb/master.svg)](https://travis-ci.com/bigchaindb/bigchaindb)
[![Documentation Status](https://readthedocs.org/projects/bigchaindb-server/badge/?version=latest)](https://docs.bigchaindb.com/projects/server/en/latest/)
[![Join the chat at https://gitter.im/bigchaindb/bigchaindb](https://badges.gitter.im/bigchaindb/bigchaindb.svg)](https://gitter.im/bigchaindb/bigchaindb?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Planetmint Server

This repository is for _Planetmint Server_.

Planetmint is a tendermint based DLT application - an extended version of [BigchainDB](https://github.com/bigchaindb) (like version 3.0 of BigchainDB) - that comes with 
* compatibility to the latest tendermint version (0.35.15)
* upcoming integration of [Zenroom](https://zenroom.org/)
* [Tarantool](https://www.tarantool.io/en/) as a storage solution 
* [Verifiable Conditions](https://w3c-ccg.github.io/verifiable-conditions/#:~:text=A%20verifiable%20condition%20type%20MUST,object%20property%20for%20that%20condition.&text=The%20Delegated%20fulfillment%20condition%20MUST,an%20array%20of%20DID%20URLs.)
* New transactions types to support industrial adapation and integration of DLT technology

## The Basics

Documenation relies on BigchainDB documentation, please bare in mind that all of that can still be used. Just refer to Planetmint repositories and packages/images in case you use this documentation. 
* [Try the Quickstart](https://docs.bigchaindb.com/projects/server/en/latest/quickstart.html)
* [Read the Planetmint 2.0 whitepaper](https://www.bigchaindb.com/whitepaper/)
* [Check out the _Hitchiker's Guide to Planetmint_](https://www.bigchaindb.com/developers/guide/)

## Run and Test Planetmint Server from the `main` Branch

Running and testing the latest version of Planetmint Server is easy. Make sure you have a recent version of [Docker Compose](https://docs.docker.com/compose/install/) installed. When you are ready, fire up a terminal and run:

```text
git clone https://github.com/planetmint/planetmint.git
cd planetmint
make run
```

Planetmint should be reachable now on `http://localhost:9984/`.

There are also other commands you can execute:

* `make start`: Run Planetmint from source and daemonize it (stop it with `make stop`).
* `make stop`: Stop Planetmint.
* `make logs`: Attach to the logs.
* `make test`: Run all unit and acceptance tests.
* `make test-unit-watch`: Run all tests and wait. Every time you change code, tests will be run again.
* `make cov`: Check code coverage and open the result in the browser.
* `make doc`: Generate HTML documentation and open it in the browser.
* `make clean`: Remove all build, test, coverage and Python artifacts.
* `make reset`: Stop and REMOVE all containers. WARNING: you will LOSE all data stored in Planetmint.

To view all commands available, run `make`.

## Links for Everyone

* [BigchainDB.com](https://www.bigchaindb.com/) - the main Planetmint website, including newsletter signup
<!--
* [Roadmap](https://github.com/planetmint/org/blob/master/ROADMAP.md)
* [Blog](https://medium.com/the-bigchaindb-blog)
* [Twitter](https://twitter.com/Planetmint)
-->

## Links for Developers

* [All Planetmint Documentation](https://docs.bigchaindb.com/en/latest/)
* [Planetmint Server Documentation](https://docs.bigchaindb.com/projects/server/en/latest/index.html)
* [CONTRIBUTING.md](.github/CONTRIBUTING.md) - how to contribute
* [Community guidelines](CODE_OF_CONDUCT.md)
* [Open issues](https://github.com/planetmint/planetmint/issues)
* [Open pull requests](https://github.com/planetmint/planetmint/pulls)
* [Gitter chatroom](https://gitter.im/planetmint/community)

## Legal

* [Licenses](LICENSES.md) - open source & open content
* [Imprint](https://ipdb.io/imprint/)
* [Contact Us](https://ipdb.io/)
