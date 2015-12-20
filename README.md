# Notes
# Fundamentals of Database Systems

#C3
Constraints are restrictions on actual values in a database state.

Types of constraints
 1. Implicit constraints - in herent in data model - e.g. tuple cannot have duplicate values
 2. Explicit constraints - specify by DDL - expressed in the schema of the data model 
   - Domain constraints - every atribute should be an atomic value
   - Key constraints
     - superkey - default super key is all attributes, superkey can have redundent attributes
     - key - key is the minimal superkey
     - candidate key - in general, relations can have more than one keys, each of them is called candidate key.
     - primary key - designating one candidate key as a primary key is common in dbs
   - Not Null constraints
   - Entity integrity constraints - no primary key can be null - this is specified on a single relation
   - Referential intergrity constraints - a tuple in one relation that refers to another should be an existing tuple in that relation
 3. Application-based constraints - not expressed in the schema of the data model
 4. Data dependencies - functional dependencies and multivalued dependencies - goodness of the db design


#C15
Prime attributes - any atribute that is part of a candidate key is refered as prime attribute.
