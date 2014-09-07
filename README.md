Forked from: https://github.com/robv/dokku-elasticsearch

# Dokku Solr Plugin

The dokku solr plugin adds a solr service to your
dokku stack. (currently using version 3.6.2 of solr)

## Installation

The plugin assumes that [dokku](https://github.com/progrium/dokku) is
already installed.

```
cd var/lib/dokku/plugins
git clone https://github.com/fermuch/dokku-solr
dokku plugins-install
```

## Commands

```
$ dokku help
    solr:create <app>
    solr:delete <app>
    solr:info <app>
    solr:link <app>
    solr:logs <app>
```
