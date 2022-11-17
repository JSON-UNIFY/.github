# JSON-Unify Object As Markdown

To create a new data product using the JSON-Unify data contract specification:
- Copy the JSON code in from below in the cell named 'JSON'
- In your Python Notebook:
```
import pyunify as uf
unify = uf.JsonUnify(paste_json)
```

This markdown file was automatically generated with ```unify.md()```

The goal of JSON-Unify is to get **metadata** and **concepts**, included **with the data** itself (in a file or API payload), to improve the user experience of those who create, consume, and share data.

<em>By creating clean & rich data with JSON-Unify, you are helping the next person who needs to use it by saving them time and increasing their understanding of the data.</em>

## Concepts - Headers

```

```
## Concepts - Values

```

```
## Data

```

```
## Governance - Compliance

```
| NAME   | TYPE   | DESCRIPTION   | REQUIREMENTS   |
|--------|--------|---------------|----------------|
```
## Governance - Roles

```
| ROLE   | RESPONSIBILITIES   |
|--------|--------------------|
```
## Governance - SLA

```
| NAME   | TYPE   | DESCRIPTION   | REQUIREMENTS   |
|--------|--------|---------------|----------------|
```
## Lineage

```
|    | LISTENER   | EVENT   | DESCRIPTION            | TIMESTAMP            |
|---:|:-----------|:--------|:-----------------------|:---------------------|
|  1 | data       | init    | data initialized       | 11/17/2022, 16:51:48 |
|  2 | concepts   | init    | concepts initialized   | 11/17/2022, 16:51:48 |
|  3 | meta       | init    | meta initialized       | 11/17/2022, 16:51:48 |
|  4 | governance | init    | governance initialized | 11/17/2022, 16:51:48 |
```
## Meta

```
|    | Key         | Value                         |
|---:|:------------|:------------------------------|
|  0 | contract    | https://github.com/JSON-UNIFY |
|  1 | description |                               |
|  2 | source      |                               |
|  3 | tags        |                               |
|  4 | authors     |                               |
|  5 | id          |                               |
|  6 | contact     |                               |
|  7 | name        |                               |
```
## JSON

```
{
    "meta": {
        "contract": "https://github.com/JSON-UNIFY",
        "description": null,
        "source": null,
        "tags": null,
        "authors": null,
        "id": null,
        "contact": null,
        "name": null
    },
    "data": [],
    "concepts": {
        "headers": {},
        "values": {}
    },
    "compute": [
        [
            "STATE",
            "VALUE",
            "LISTENER",
            "EVENT",
            "DESCRIPTION"
        ],
        [
            "NUM_ROWS",
            null,
            null,
            null,
            "The number of rows in the dataset"
        ],
        [
            "NUM_COLUMNS",
            null,
            null,
            null,
            "The number of columns in the dataset"
        ],
        [
            "DATE_CREATED",
            null,
            null,
            null,
            "The date this object was created"
        ],
        [
            "DATE_MODIFIED",
            null,
            null,
            null,
            "The date his object was last modified"
        ]
    ],
    "custom": {},
    "governance": {
        "compliance": [
            [
                "NAME",
                "TYPE",
                "DESCRIPTION",
                "REQUIREMENTS"
            ]
        ],
        "sla": [
            [
                "NAME",
                "TYPE",
                "DESCRIPTION",
                "REQUIREMENTS"
            ]
        ],
        "roles": [
            [
                "ROLE",
                "RESPONSIBILITIES"
            ]
        ]
    },
    "lineage": [
        [
            "LISTENER",
            "EVENT",
            "DESCRIPTION",
            "TIMESTAMP"
        ],
        [
            "data",
            "init",
            "data initialized",
            "11/17/2022, 16:51:48"
        ],
        [
            "concepts",
            "init",
            "concepts initialized",
            "11/17/2022, 16:51:48"
        ],
        [
            "meta",
            "init",
            "meta initialized",
            "11/17/2022, 16:51:48"
        ],
        [
            "governance",
            "init",
            "governance initialized",
            "11/17/2022, 16:51:48"
        ]
    ],
    "project": {}
}
```
