
# SOLR

## Installation

## Setup

## Usage

### command-line

```
export URL='http://localhost:8983/solr/gettingsstarted_shard1_replica1'
curl "$URL/update?stream.body=<delete><query>*:*</query></delete>"
```
