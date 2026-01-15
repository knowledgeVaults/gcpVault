# Gemini Enterprise: Connectors

A connector is a secure integration of selected internal and external data sources that a user's Gemini application will search and act on thaat data with natural language while respecting existing permissions

* Connectors can be either Google apps or third-party connectors

<br>

# Connector Modes

## Federated

Federated connectors leaves the data in the original system and uses a connector to query that system in place at question time ("Query in place" model)

* Reduces data duplication and can simplify governance
* Query latency and availability depends on the external system and network connectivity
* Requires user authentication and authorization to be set up on the external sources

<br>

## Ingested

Ingested connectors copy and store data from the data source into the Vertex AI Search Index ("Copy and index" model)

* Enables fast semantic search, grounding, and recommendations by having all content, metadata, and permissions are stored and indexed inside Gemini
* Provides low-latency search since everything is locally indexed
