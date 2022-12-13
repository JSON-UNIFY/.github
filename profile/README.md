# JSON-Unify - An Open-Source Data Contract Specification 
A simple specification for open-source data contracts to unify agreement, understanding, and expectations

### Simply, a data contract is a declarative agreement between a sender and receiver of information in a communication event (API payload for example).
### A data contract has a functional purpose of reducing ambiguity and errors, and increasing trust and efficiency.
### The JSON-UNIFY specification has three requirements: @meta, @data, and @concepts

## WHY THERE IS A NEED FOR AN OPEN-SOURCE DATA CONTRACT SPECIFICATION
- JSON-schema manages structure of data 
- JSON-LD & JSON-RDF have a learning curve and can require significant changes in how teams operate, tools they need to use, and this can result in friction and non-action.
- In years of user experience research with data science, software, and business intelligence teams, the lowest common denominator was that people didn't have metadata included in the data, and they didn't know what columns/keys meant, which can create a lot of confusion and waste a ton of time.
- A minimal solution was necessary that anyone can use, requiring no infrastructure and almost no learning curve. Simply have three sections in your JSON payload: "@data", "@meta", and "@concepts", so that metadata and semantic definitions are included in the payload itself. This prevents individuals from having to hunt things down.
- Adittional sections, like "@lineage", "@governance", "@features" are optional sections.

## DESIGNED FOR SIMPLICITY, CONFIGURABILITY, AND SCALABILITY:
By making the entire data contract a JSON specification, it has maximum flexibility for customization, including industry-specific templates and standards.

## LEGEND:
Any key with an "@" symbol means it is required. If the parent has no "@" symbol, it means that it is required only if the parent (optional) is added. For example, if you are going to add the key "values" to your "@semantics" block, then "@description" must be included for each property listed.

## BENEFITS:
Ensure that metadata is included with the data, so that users don't have to waste time trying to understand what a column definition really means.
Allow for any format / data representation (CSV, JSON, Relational Table using SQL, etc.)
Allow for any industry to have 3rd party reference frames for data contracts, for federated computing
Enable sequential / temporal agreements

REQUIRED PAYLOAD PROPERTIES
## @meta
- contract - specification for the contract, so receivers and senders have an agreement on the format
- description - any info
- etc...

## @data
- Simply the data

## @concepts
- A semantic reference MUST be included for any table columns and/or JSON keys
- A semantic reference MAY be included for any table row values and/or JSON values



