# nlp_aps

## Overview

This is an NLP (Natural Language Processing) project, extending Project ARIS to address known limitations such as implication questions and common sense knowledge.

## Features

- Uses Stanford CoreNLP for core NLP tasks
- Supports document processing with Apache PDFBox
- Employs Weka for machine learning integration
- Provides JSON serialization using json-simple and json-io
- Includes WS4J for semantic similarity operations

## Installation

1. **Environment Setup:**  
   Requires external libraries, which must be downloaded and referenced in your Eclipse project.

2. **Dependencies:**  
   The project uses the following libraries (see `pom.xml` for Maven setup):
   
   - `stanford-corenlp` (`edu.stanford.nlp:stanford-corenlp:3.2.0`)
   - `pdfbox` (`org.apache.pdfbox:pdfbox:1.8.16`)
   - `weka-stable` (`nz.ac.waikato.cms.weka:weka-stable:3.6.10`)
   - `json-simple` (`com.googlecode.json-simple:json-simple:1.1`)
   - `json-io` (`com.cedarsoftware:json-io:2.2.30`)
   - `ws4j` (`de.sciss:ws4j:0.1.0`)

   Add these dependencies to your Maven `pom.xml` or download them and reference them manually if not using Maven.

## Usage

1. Import the project into Eclipse.
2. Download all required libraries and add them to the build path if not using Maven.
3. Explore and run the `src/` directory to get started with project logic.

## Project Structure

- `pom.xml` – Maven dependencies for all main libraries.
- `src/` – Main Java source code (see this folder for usage and classes).
- `.idea/` – Project configuration for IntelliJ IDEA.
- `.DS_Store` – macOS metadata file (ignore).

## Notes

- All code is an extension to Project ARIS, attempting to tackle NLP challenges around implication and common sense reasoning.
- All rights belong to the original author/project.

---

For further details, see the [pom.xml](https://github.com/aditya-tangirala/nlp_aps/blob/master/pom.xml) and explore the `src/` directory in the repository.
