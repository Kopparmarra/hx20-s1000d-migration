# HX-20 S1000D-Style Migration Notes

This sample shows how a legacy maintenance procedure can be audited, split into data modules and prepared for an S1000D-oriented technical publication workflow.

The source document is a fictional Word-based HX-20 helicopter hydraulic pump maintenance procedure with repeated safety information, paragraph-based instructions and embedded MK2 configuration notes.

## Migration focus

The S1000D-style migration focuses on:

- identifying required data modules
- assigning data module codes
- separating removal and installation procedures
- separating operational test content from installation content
- adding identification and status metadata
- modelling MK2-specific content with applicability
- assembling the output through a publication module

## Included files

- `DMC-HX20-A-29-10-00-00A-040A-A.xml` - simplified system overview description data module
- `DMC-HX20-A-29-10-00-00A-520A-A.xml` - simplified removal procedure data module
- `DMC-HX20-A-29-10-00-00A-720A-A.xml` - simplified installation procedure data module
- `DMC-HX20-A-29-10-00-00A-790A-A.xml` - simplified operational test data module
- `PMC-HX20-A-29-10-00-00A-000A-A.xml` - simplified publication module

## Identifier note

The sample uses `FICTV` as a fictional enterprise code for portfolio purposes. A production project would use the customer-approved enterprise identifier, such as a registered CAGE/NCAGE code or another identifier defined in the business rules.

## Scope note

These files are intentionally compact portfolio examples. A production S1000D delivery would be validated against the selected S1000D issue, project business rules, BREX, SNS policy and CSDB delivery requirements.

## Naming note

The example names use S1000D-style data module and publication module codes. In a real project, these codes would be defined according to the project's SNS structure, business rules, information code policy and issue management process.

## Tooling note

S1000D is not a software tool. It is a technical publication specification. A production workflow would normally use an XML editor, validation tools, a CSDB and publishing tools.
