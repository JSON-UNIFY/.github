# JSON-Unify is an Open-Source Data Contract Specification 
The bare minimal specification for open-source data contracts to unify agreement, understanding, and expectations

The purpose of JSON-Unify is to unite the data, concept/semantic information, metadata, lineage, governance, etc. into one singular object, thereby eliminating common sources of ambiguity and time-wasted in wanting to understand and use data.

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

# unifyQL: a query language for JSON-Unify objects

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




