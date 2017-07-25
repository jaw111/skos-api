# Client server operation-matching ingredients 

Match goal with possible operations based on intent, parameters, and post-conditions.

## Client
- **Goal:** a RDF graph containing triples
- **Intent:** Create, Retrieve, Update, Delete

## Server:
- **Operation:**
  * uri
  * name
  * description
- **Action:** Create, Retrieve, Update, Delete 
- **Parameters (or unknowns):** The necessary input for the operation, in terms of the metamodel.
- **Post-conditions:** A SHACL shape which describes the result of the operation in terms of the metamodel.
- **Returns:** What the operation returns in terms of the metamodel.
