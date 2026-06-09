# Unit Process Ontologies for Lean Analysis of Non-Manufacturing Workflows

## Description
Two OWL ontologies formalizing unit processes within 
the LCFM framework:
- New Hiring (NH) contract request process
- Certificate of Employment (CoE) request process

Both processes are executed by the same organizational 
role (Student Admin 1) and were selected as an initial 
example for semantic formalization within the LCFM 
framework.

## Purpose
The ontology layer serves three purposes:
1. Establishes a shared vocabulary across the four 
   LCFM partners: Human, Machine, Material, and Method
2. Provides a machine-readable model between every 
   observed task duration and its corresponding BPMN 
   element, directly encoding the raw process time (RPT) 
   of each unit process
3. Supports cross-case comparability between the NH and 
   CoE workflows under a unified semantic framework, 
   facilitating Operating Curve benchmarking

## Contents
- `NewContractsOntology.ttl` — NH process ontology
- `CertificatesOfEmploymentOntology` — CoE ontology

## Ontology Details
- Built in: Protégé
- Syntax: Turtle / OWL 2
- Key classes: UserTask, StartEvent, IntermediateEvent,
  EndEvent, SequenceFlow, Role, DataStores
- Key properties: triggeredBy, hasSequenceFlow,
  hasSubProcess, isPerformedBy, usesDataStore,
  hasDurationMinutes

## Visualization
- New Hiring Ontology: https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/cobrie23tcd/OWL-Ontology-of-Unit-Processes-/main/NewContractsOntology.ttl
- CoE Ontology: https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/cobrie23tcd/OWL-Ontology-of-Unit-Processes-/main/CertificatesOfEmploymentOntology.ttl

## Citation
O'Brien Christ (2026). Unit Process Ontologies for 
Lean Analysis of Non-Manufacturing Workflows (v1.0) 
[Dataset]. Zenodo. https://doi.org/10.5281/zenodo.20607494

## References
- W3C OWL Working Group (2012). OWL 2 Web Ontology 
  Language Document Overview. 
  https://www.w3.org/TR/owl2-overview/
- W3C SPARQL 1.2 Query Language. 
  https://www.w3.org/TR/sparql12-query/
