# Nils Flöser

Software developer building **traceable software for healthcare and public administration** – systems where every result can be explained and checked.

At [Berufsgenossenschaft Holz und Metall](https://www.bghm.de/), a German statutory accident insurance institution, I work on business applications with C#/.NET and SAP ABAP. In my own projects I own the whole path: architecture, tests, CI, documentation and a demo that runs with one command.

**Java · Spring Boot · Angular · TypeScript · C#/.NET · SAP ABAP · Python · PostgreSQL · Docker**

## Featured

### [NormaCase](https://github.com/nfloser/normacase) – rule-based decision support for medical assessments

Evaluates applications against versioned rules and shows the complete decision trail for every result. Missing information leads to a targeted follow-up request, conflicting evidence goes to a human, approval follows the four-eyes principle. Case data is deleted after pickup; only a decision record without case content remains.

Java 25 · Spring Boot · Angular · PostgreSQL · Keycloak · Docker · Kubernetes – 118 parity cases against the previous .NET engine, end-to-end and accessibility tests, load tests in CI. All cases are fictional.

### [Urbanium](https://github.com/nfloser/urbanium) – live urban data with sources attached

Brings live city data – weather from the German Weather Service (DWD), public transport alerts (VBB) – into one API, keeping the source of every value. The core is city-independent; Berlin and Mainz are the first deployments. [Browser demo](https://nfloser.github.io/urbanium/)

Python · REST/OpenAPI · RDF/SHACL

## More projects

- [AnoCore](https://github.com/nfloser/AnoCore) – Counter-Strike 2 server plugin with stats, ranks, map voting and match administration (C#)
- [VesicleScope](https://github.com/nfloser/vesicle-scope) – research tool for simulating extracellular-vesicle transport
- [Berlin Semantic Cadastre](https://github.com/nfloser/berlin-semantic-cadastre) – .NET service for Berlin cadastral data with spatial queries, GeoJSON and GeoSPARQL export

## How I work

Issue → branch → tests → pull request → CI → review → merge. Small commits, documented decisions (ADRs), and no claims a test can't back up.

[LinkedIn](https://www.linkedin.com/in/nils-floeser) · [All repositories](https://github.com/nfloser?tab=repositories)
