# OWL-Ontology-of-Unit-Processes
Initial release of two OWL ontologies built in Protégé 
using Turtle syntax, formalizing unit processes executed 
by Student Admin 1 within the LCFM framework.

Ontologies cover:
- New Hiring (NH) contract request process
- Certificate of Employment (CoE) request process

Key classes: UserTask, StartEvent, IntermediateEvent, 
EndEvent, SequenceFlow, Role, DataStores

Key properties: triggeredBy, hasSequenceFlow, 
hasSubProcess, isPerformedBy, usesDataStore, 
hasDurationMinutes

Each named individual carries empirically measured 
task durations (RPT) in decimal minutes, enabling 
SPARQL-based querying and cross-process Operating 
Curve benchmarking.
