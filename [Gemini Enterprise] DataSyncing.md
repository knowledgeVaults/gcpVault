# Gemini Enterprise: Data Sync

Data sync is the process that regularly updates a Gemini data store with the latest information from an external system

* Fetches, transforms, and then synchornizes the data into the data store

<br>

# Sync Types

Sync types determine how connectors update data stores with content from external sources

## Full Sync

Full sync captures the entire state of the third-party app or service

* Replaces the existing contents of the data store

<br>

## Incrememntal Sync

Incremental sync captures entity data that has been added or updated since the last sync

* Doesn't sync identity data or deletions of entity data

<br>

# Sync Schedules

Sync schedules determine the frequency of data synchronization between connectors and their associated data stores


