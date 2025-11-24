---
slug: github-supreme-court-transfer-service-uniques-note-technical-overview
id: github-supreme-court-transfer-service-uniques-note-technical-overview
title: Supreme Court Transfer Service Uniques
repo: justin-napolitano/supreme-court-transfer-service-uniques
githubUrl: https://github.com/justin-napolitano/supreme-court-transfer-service-uniques
generatedAt: '2025-11-24T18:47:59.244Z'
source: github-auto
summary: >-
  This repo transfers Supreme Court case metadata from a PostgreSQL database to
  a Neo4j graph database. It ensures unique nodes and optimizes relationships in
  the graph while following normalization principles.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo transfers Supreme Court case metadata from a PostgreSQL database to a Neo4j graph database. It ensures unique nodes and optimizes relationships in the graph while following normalization principles.

## Key Features

- Transfer metadata from PostgreSQL to Neo4j
- Prevent duplication in the graph
- Create efficient relationships between nodes
- Optimize graph queries using a normalized source

## Tech Stack

- Java
- PostgreSQL
- Neo4j

## Getting Started

### Prerequisites

- Java JDK
- PostgreSQL instance with case metadata
- Neo4j database

### Quick Setup

1. Clone the repo:

    ```bash
    git clone https://github.com/justin-napolitano/supreme-court-transfer-service-uniques.git
    cd supreme-court-transfer-service-uniques
    ```

2. Build and run the app (assumes Maven or Gradle):

    ```bash
    # Maven
    mvn clean install
    mvn exec:java

    # Gradle
    ./gradlew build
    ./gradlew run
    ```

Make sure to configure the database connection parameters before running.
