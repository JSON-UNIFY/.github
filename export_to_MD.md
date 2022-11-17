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

## concepts - headers

```
|    | name               | type   | description                                        |
|---:|:-------------------|:-------|:---------------------------------------------------|
|  0 | ID                 | string | the unique id of the hero                          |
|  1 | First name         | string | the first name of the superhuman                   |
|  2 | Last name          | string | the last name of the superhuman                    |
|  3 | Birth year         | string | The birth year of the superhuman                   |
|  4 | Height             | string | The height of the superhuman                       |
|  5 | Birthplace         | string | The birthplace of the superhuman                   |
|  6 | Identity is secret | string | Whether the identity of the superhuman is a secret |
|  7 | Can fly            | string | Whether the superhuman can fly                     |
|  8 | Alignment          | string | The alignment of the superhuman                    |
|  9 | Wears cape         | string | Whether the superhuman wears a cape                |
```
## concepts - values

```

```
## data

```
|    |   ID | First name   | Last name   | Birth year   | Height   | Birthplace      | Identity is secret   | Can fly   | Alignment    | Wears cape   |
|---:|-----:|:-------------|:------------|:-------------|:---------|:----------------|:---------------------|:----------|:-------------|:-------------|
|  1 | 7435 | Bruce        | Wayne       | 1969*        | 6'2"     | Gotham          | Y                    | 3         | anti-villain | black        |
|  2 | 0958 | Ororo        | Munroe      | --1979--     | 5'11"    | Manhattan       |                      | 9         | good         | long         |
|  3 | 9471 | Diana        | Trevor      | 1618         | 5'8"     | Paradise Island | Y                    | Jet       | truth        | rarely       |
|  4 | 9483 | Janet        | Van Dyne    | 19.42        | 5'4"     | Cresskill       |                      | tiny      | Good         | Not really   |
|  5 | 0696 | Peter        | Parker      | 11111983     | 5'10"    | Queens          | Y                    | Fall      | right        | never        |
|  6 | 5531 | Harleen      | Quinzell    | 1981         | 6'0"     | Gotham          | Y                    |           | evil         | no           |
|  7 | 4734 | Erik         | Lehnsherr   | 1-9-8-3      | 5'7"     | Hamburg         |                      | Lev.      | mutants      | Absolutely   |
|  8 | 7757 | Natasha      | Romanova    | 1983         | 5'6"     | St. Petersburg  |                      | jet       | depends      | No way       |
|  9 | 0323 | Jean         | Grey        | "1977"       | 6'4"     | Annandale       |                      | No        | good         | Mostly not   |
| 10 | 3980 | Clark        | Kent        | "1954"       | 6'2"     | Krypton         | Y                    | 12        | Truth        | always       |
| 11 | 3057 | Victor       | Von Doom    | "1943"       | 6'2"     | Latveria        |                      | 1         | Bad          | yes          |
| 12 | 0573 | Stephen      | Strange     | 1968         | 6'2"     | Philidelphia    |                      | not       | light        | T            |
| 13 | 7452 | Thor         | Odinson     | 2287 BC      | 6'6"     | Norway          |                      | 10        | Good         | Of course    |
| 14 | 1437 | Selina       | Kyle        | 1998         | 5'7"     | Gotham          | Y                    | NA        | Neutral      | It clashes   |
| 15 | 1883 | Raven        | Darkholme   | ..1911..     | 5'10"    | unknown         | Y                    | no        | mostly bad   | Not really   |
| 16 | 5830 | Kara         | Zor-el      | 1961         | 5'7"     | Krypton         | Y                    | fast      | G            | yes          |
```
## governance_compliance

```
|    | NAME                           | TYPE                    | DESCRIPTION                                             | REQUIREMENTS                        |
|---:|:-------------------------------|:------------------------|:--------------------------------------------------------|:------------------------------------|
|  1 | legal_requirement_name_example | CATEGORY_OF_REQUIREMENT | Description of a legal requirement                      |                                     |
|  2 | Delete request                 | GDPR                    | Upon request, a user can have all of their data deleted | Email confirmation upon completeion |
```
## governance_roles

```
|    | ROLE             | RESPONSIBILITIES                                                                                                                         |
|---:|:-----------------|:-----------------------------------------------------------------------------------------------------------------------------------------|
|  1 | Data Owner       | ['Definitions of concepts', 'Management of data quality standards', 'Owns of data processes', 'Approves business rules and definitions'] |
|  2 | Data Steward     | ['Definitions of concepts', 'Management of data quality standards', 'Owns of data processes', 'Approves business rules and definitions'] |
|  3 | Data Lead        | []                                                                                                                                       |
|  4 | Data Custodian   | []                                                                                                                                       |
|  5 | Business Analyst | ['Documents data and business requirements for team review']                                                                             |
|  6 | Data Architect   | ['Manages data models bridging business and technology teams']                                                                           |
```
## governance_sla

```
|    | NAME                                        | TYPE                 | DESCRIPTION                                                                                       | REQUIREMENTS   |
|---:|:--------------------------------------------|:---------------------|:--------------------------------------------------------------------------------------------------|:---------------|
|  1 | support_agreement_name_example              | SUPPORT REQUIREMENT  | Description of a support agreement for this data the producer will give the consumer              |                |
|  2 | customer_requirement_agreement_name_example | CUSTOMER REQUIREMENT | Description of a customer requirement agreement for this data the producer will give the consumer |                |
|  3 | service_assumptions_agreement_name_example  | SERVICE ASSUMPTION   | Description of a customer requirement agreement for this data the producer will give the consumer |                |
```
## lineage

```
|    | LISTENER   | EVENT   | DESCRIPTION            | TIMESTAMP            |
|---:|:-----------|:--------|:-----------------------|:---------------------|
|  1 | data       | init    | data initialized       | 11/17/2022, 14:00:33 |
|  2 | concepts   | init    | concepts initialized   | 11/17/2022, 14:00:33 |
|  3 | meta       | init    | meta initialized       | 11/17/2022, 14:00:33 |
|  4 | governance | init    | governance initialized | 11/17/2022, 14:00:33 |
```
## meta

```
|    | Key         | Value                                                             |
|---:|:------------|:------------------------------------------------------------------|
|  0 | contract    | https://github.com/JSON-UNIFY/table                               |
|  1 | source      | https://www.youtube.com/watch?v=jSaseNL8RDE                       |
|  2 | description | This dataset uses Brandon Rohrer's example of cleaning data @9:56 |
|  3 | tags        |                                                                   |
|  4 | authors     |                                                                   |
|  5 | id          |                                                                   |
|  6 | contact     |                                                                   |
|  7 | name        |                                                                   |
```
## json

```
{
    "meta": {
        "contract": "https://github.com/JSON-UNIFY/table",
        "source": "https://www.youtube.com/watch?v=jSaseNL8RDE",
        "description": "This dataset uses Brandon Rohrer's example of cleaning data @9:56 ",
        "tags": null,
        "authors": null,
        "id": null,
        "contact": null,
        "name": null
    },
    "data": [
        [
            "ID",
            "First name",
            "Last name",
            "Birth year",
            "Height",
            "Birthplace",
            "Identity is secret",
            "Can fly",
            "Alignment",
            "Wears cape"
        ],
        [
            "7435",
            "Bruce",
            "Wayne",
            "1969*",
            "6'2\"",
            "Gotham",
            "Y",
            "3",
            "anti-villain",
            "black"
        ],
        [
            "0958",
            "Ororo",
            "Munroe",
            "--1979--",
            "5'11\"",
            "Manhattan",
            "",
            "9",
            "good",
            "long"
        ],
        [
            "9471",
            "Diana",
            "Trevor",
            "1618",
            "5'8\"",
            "Paradise Island",
            "Y",
            "Jet",
            "truth",
            "rarely"
        ],
        [
            "9483",
            "Janet",
            "Van Dyne",
            "19.42",
            "5'4\"",
            "Cresskill",
            "",
            "tiny",
            "Good",
            "Not really"
        ],
        [
            "0696",
            "Peter",
            "Parker",
            "11111983",
            "5'10\"",
            "Queens",
            "Y",
            "Fall",
            "right",
            "never"
        ],
        [
            "5531",
            "Harleen",
            "Quinzell",
            "1981",
            "6'0\"",
            "Gotham",
            "Y",
            "",
            "evil",
            "no"
        ],
        [
            "4734",
            "Erik",
            "Lehnsherr",
            "1-9-8-3",
            "5'7\"",
            "Hamburg",
            "",
            "Lev.",
            "mutants",
            "Absolutely"
        ],
        [
            "7757",
            "Natasha",
            "Romanova",
            "1983",
            "5'6\"",
            "St. Petersburg",
            "",
            "jet",
            "depends",
            "No way"
        ],
        [
            "0323",
            "Jean",
            "Grey",
            "\"1977\"",
            "6'4\"",
            "Annandale",
            "",
            "No",
            "good",
            "Mostly not"
        ],
        [
            "3980",
            "Clark",
            "Kent",
            "\"1954\"",
            "6'2\"",
            "Krypton",
            "Y",
            "12",
            "Truth",
            "always"
        ],
        [
            "3057",
            "Victor",
            "Von Doom",
            "\"1943\"",
            "6'2\"",
            "Latveria",
            "",
            "1",
            "Bad",
            "yes"
        ],
        [
            "0573",
            "Stephen",
            "Strange",
            "1968",
            "6'2\"",
            "Philidelphia",
            "",
            "not",
            "light",
            "T"
        ],
        [
            "7452",
            "Thor",
            "Odinson",
            "2287 BC",
            "6'6\"",
            "Norway",
            "",
            "10",
            "Good",
            "Of course"
        ],
        [
            "1437",
            "Selina",
            "Kyle",
            "1998",
            "5'7\"",
            "Gotham",
            "Y",
            "NA",
            "Neutral",
            "It clashes"
        ],
        [
            "1883",
            "Raven",
            "Darkholme",
            "..1911..",
            "5'10\"",
            "unknown",
            "Y",
            "no",
            "mostly bad",
            "Not really"
        ],
        [
            "5830",
            "Kara",
            "Zor-el",
            "1961",
            "5'7\"",
            "Krypton",
            "Y",
            "fast",
            "G",
            "yes"
        ]
    ],
    "concepts": {
        "headers": {
            "name": [
                "ID",
                "First name",
                "Last name",
                "Birth year",
                "Height",
                "Birthplace",
                "Identity is secret",
                "Can fly",
                "Alignment",
                "Wears cape"
            ],
            "type": [
                "string",
                "string",
                "string",
                "string",
                "string",
                "string",
                "string",
                "string",
                "string",
                "string"
            ],
            "description": [
                "the unique id of the hero",
                "the first name of the superhuman",
                "the last name of the superhuman",
                "The birth year of the superhuman",
                "The height of the superhuman",
                "The birthplace of the superhuman",
                "Whether the identity of the superhuman is a secret",
                "Whether the superhuman can fly",
                "The alignment of the superhuman",
                "Whether the superhuman wears a cape"
            ]
        },
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
    "governance": {
        "compliance": [
            [
                "NAME",
                "TYPE",
                "DESCRIPTION",
                "REQUIREMENTS"
            ],
            [
                "legal_requirement_name_example",
                "CATEGORY_OF_REQUIREMENT",
                "Description of a legal requirement",
                null
            ],
            [
                "Delete request",
                "GDPR",
                "Upon request, a user can have all of their data deleted",
                "Email confirmation upon completeion"
            ]
        ],
        "sla": [
            [
                "NAME",
                "TYPE",
                "DESCRIPTION",
                "REQUIREMENTS"
            ],
            [
                "support_agreement_name_example",
                "SUPPORT REQUIREMENT",
                "Description of a support agreement for this data the producer will give the consumer",
                null
            ],
            [
                "customer_requirement_agreement_name_example",
                "CUSTOMER REQUIREMENT",
                "Description of a customer requirement agreement for this data the producer will give the consumer",
                null
            ],
            [
                "service_assumptions_agreement_name_example",
                "SERVICE ASSUMPTION",
                "Description of a customer requirement agreement for this data the producer will give the consumer",
                null
            ]
        ],
        "roles": [
            [
                "ROLE",
                "RESPONSIBILITIES"
            ],
            [
                "Data Owner",
                [
                    "Definitions of concepts",
                    "Management of data quality standards",
                    "Owns of data processes",
                    "Approves business rules and definitions"
                ]
            ],
            [
                "Data Steward",
                [
                    "Definitions of concepts",
                    "Management of data quality standards",
                    "Owns of data processes",
                    "Approves business rules and definitions"
                ]
            ],
            [
                "Data Lead",
                []
            ],
            [
                "Data Custodian",
                []
            ],
            [
                "Business Analyst",
                [
                    "Documents data and business requirements for team review"
                ]
            ],
            [
                "Data Architect",
                [
                    "Manages data models bridging business and technology teams"
                ]
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
            "11/17/2022, 14:00:33"
        ],
        [
            "concepts",
            "init",
            "concepts initialized",
            "11/17/2022, 14:00:33"
        ],
        [
            "meta",
            "init",
            "meta initialized",
            "11/17/2022, 14:00:33"
        ],
        [
            "governance",
            "init",
            "governance initialized",
            "11/17/2022, 14:00:33"
        ]
    ],
    "custom": {}
}
```
