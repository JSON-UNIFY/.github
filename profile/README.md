# JSON-Unify is an Open-Source Data Contract Specification 
The bare minimal specification for open-source data contracts to unify agreement, understanding, and expectations

The purpose of JSON-Unify is to unite the data, concept/semantic information, metadata, lineage, governance, etc. into one singular object, thereby eliminating common sources of ambiguity and time-wasted in wanting to understand and use data.

# Exciting News! JSON-Unify is currently being developed as a JSON-Schema vocabulary proposal to officially become part of JSON-Schema!
https://github.com/JSON-UNIFY/vocab-dataset/blob/main/spec/v1.markdown

Has the details for the JSON-Schema implementation of the JSON-Unify meta-schema.

# A JSON-Unify object requires that "meta" (search for data), "concepts" (search in data), and "data" (or data reference) are all in one object. 

A JSON-Unify vocabulary is being developed as a proposal for JSON-Unify to formally join the official JSON-Schema specification
https://github.com/JSON-UNIFY/vocab-dataset/blob/main/spec/v1.markdown

### Example JSON-Unify structure:

```
let json = {
    concepts: {
      headers: {
        name:[],
        type:[],
        description:[]
      },
      values: {
        entity:[],
        header:[],
        type:[],
        description:[]
      },
      features: {
        row:[],
        column:[],
        feature:[],
        relation:[]
      }
    },
    data: {},
    meta: {
      key:["specification", "description", "source", "authors", "contact", "name", "markdown"],
      value: ["https://github.com/JSON-UNIFY", null, null, null, null, null, null]
    },
    governance: {
      sla: {
        category:[],
        provider:[],
        customer:[],
        requirement:[]
      },
      requirements: {
        header:[],
        minimum:[],
        maximum:[],
        exclusiveMinimum:[],
        exclusiveMaximum:[],
        options:[],
        options_default_selected:[]
      }
    },
    lineage: {
      command:[],
      params:[],
      date:[]
    }
  };

```

# UnifyQL: a query language for JSON-Unify objects

Organizations can create custom JSON-Schema vocabulary specifications for queries so that they can use JSON to standardize queries across various databases, query languages, and cloud platforms. Additional metadata can be added to UnifyQL, such as the role, name, application, business purpose, etc., of the query, so that high quality data about data source, purpose, query, query results, destination, and documentation can be unified into a single data object. 

### INSERT

```
{ "headers": { "insert": [ {"name":"Buy Signal", "type":"boolean", "description":"whether this price is predicted to be a good time to buy"} ] } }
```

### UPDATE

```
{ "headers": { "update": [ { "row":6, "col": "description", "set": "This is an updated row using unifyQL" } ] } }
```

### DELETE

```
{ "headers": { "delete": { "rows": [2, 3, 4] } } }
```

Motivation
The top findings from User Experience Research of data scientist and business intelligence analysts were that the most frequent and the most impactful pain points in their workflows stemmed from working with what we define as incomplete data products.

We define a data product, at its most fundamental unit, as simply as one would define a can of soup as a product. The can of soup comes with a Nutrition Label, making it easy to search for ingredients within the canned product, as well as a UPC Label, brand, and product name, making the can of soup easy to find, and finally the soup itself.

Likewise, when we get a data product, we want to define a singular object that contains:

The dataset, what we will refer to as the 'data'.
Data for how to search in the dataset, what we will refer to as 'schema' data.
Data for how to search for the dataset, what we will refer to as 'meta' data.
These three elements need to exist in order for a data product to be considered complete, and need to be together as one object.

Why Data Products Are Essential
Data teams often report not knowing where data comes from, or complex 3rd party tools that require licenses or experience to use in order to get important and often critical information on data. The result of a lack of a standard means that hundreds, even thousands of data sets are throwin in storage, and then left to others to sort through, with no understanding of where data came from, or what terms in columns mean.

This lack of understanding about the data can result in wasted time in meetings, or worse, in wrong knowledge being created, which often can result in real-world negative consequences with deadlines missed, or at its worst, products that may be harmful to health because of a lack of knowledge about other existing data that could have prevented errors.

Combining data, metadata, and schema is essential because it saves time, prevents errors, reduces ambiguity, and having a singular extensible object that can be used by others enhances productivity and innovative capabilities. Most importantly to businesses, it saves businesses time, money, and risk.

Data Contracts vs Data Products vs Schemas
There is a lot of debate between terms such as 'data products', and 'data contracts', and the proposed definitions have one goal: the simplest, least friction, and easiest definitions to learn and begin using, independent of any commercial product, in a generalizable fashion.

Data Products have the data, the schema, and the meta data all in one object.

A Data Contract contains the information that specifies what is a complete Data Product given a specific business need beyond the simple definition of a Data Product. There may be a set of compliance, requirements, and/or governance features for a data product. Federal Regulations may require (for example) data lineage for medical data, then defining how that will be captured, and whether it is captured in the data product can be added in an SLA (service level agreement). A Data Contract may alter of define a Data Contract so that data is a third party reference versus being included in the data product itself (the data may be exceptionally large, there might be legal or privacy rules, etc.). The country of origin (lineage), UPC label, and the nutrition label are all part of contractual requirement for a grocery store to sell a can of soup. However, for FDA submission to sell a new product, a modified data contract may be required, even though the contents might be the same.

When thinking of a schema vs data contract it is helpful to have clear boundaries. While colloquially a schema can often be referred to as a 'contract', and while that a schema as a contract certainly makes sense, there are clear and simple differing definitions in this vocabulary specification proposal. A schema does not necessarily require a data product definition, and can be be completely independent of containing business relationships that define which schema to use with which data products, for which problems, and which regulatory needs. A new language definition to define these emerging and important needs in the data community is required. Therefore, a data contract can be thought of as the meta-schema that requires grocery stores to have canned soup (data products) that have nutrition labels (schema).




