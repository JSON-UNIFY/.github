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
|    | name               | type   | description                                      |
|---:|:-------------------|:-------|:-------------------------------------------------|
|  0 | ID                 | string | ID of the superhuman                             |
|  1 | First name         | string | The first name of the superhuman                 |
|  2 | Last name          | string | The last name of the superhuman                  |
|  3 | Birth year         | string | The birth year of the superhuman                 |
|  4 | Identity if secret | string | Whether the identity of the superhuman is secret |
|  5 | Can fly            | string | Whether the superhuman can fly                   |
|  6 | Alignment          | string | The moral alignment of the superhuman            |
|  7 | Wears cape         | string | Whether the superhuman wears a cape              |
```
## Concepts - Values

```

```
## Data

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
|  1 | data       | init    | data initialized       | 11/17/2022, 16:55:57 |
|  2 | concepts   | init    | concepts initialized   | 11/17/2022, 16:55:57 |
|  3 | meta       | init    | meta initialized       | 11/17/2022, 16:55:57 |
|  4 | governance | init    | governance initialized | 11/17/2022, 16:55:57 |
```
## Meta

```
|    | Key         | Value                                                             |
|---:|:------------|:------------------------------------------------------------------|
|  0 | contract    | https://github.com/JSON-UNIFY/table                               |
|  1 | source      | https://www.youtube.com/watch?v=jSaseNL8RDE                       |
|  2 | description | This dataset uses Brandon Rohrer's example of cleaning data @9:56 |
|  3 | table       |                                                                   |
|  4 | query       |                                                                   |
|  5 | tags        |                                                                   |
|  6 | authors     |                                                                   |
|  7 | id          |                                                                   |
|  8 | contact     |                                                                   |
|  9 | name        |                                                                   |
```
## JSON

```
{
    "meta": {
        "contract": "https://github.com/JSON-UNIFY/table",
        "source": "https://www.youtube.com/watch?v=jSaseNL8RDE",
        "description": "This dataset uses Brandon Rohrer's example of cleaning data @9:56 ",
        "table": null,
        "query": null,
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
        "headers": [
            {
                "name": "ID",
                "type": "string",
                "description": "ID of the superhuman"
            },
            {
                "name": "First name",
                "type": "string",
                "description": "The first name of the superhuman"
            },
            {
                "name": "Last name",
                "type": "string",
                "description": "The last name of the superhuman"
            },
            {
                "name": "Birth year",
                "type": "string",
                "description": "The birth year of the superhuman"
            },
            {
                "name": "Identity if secret",
                "type": "string",
                "description": "Whether the identity of the superhuman is secret"
            },
            {
                "name": "Can fly",
                "type": "string",
                "description": "Whether the superhuman can fly"
            },
            {
                "name": "Alignment",
                "type": "string",
                "description": "The moral alignment of the superhuman"
            },
            {
                "name": "Wears cape",
                "type": "string",
                "description": "Whether the superhuman wears a cape"
            }
        ],
        "values": {}
    },
    "compute": [],
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
            "11/17/2022, 16:55:57"
        ],
        [
            "concepts",
            "init",
            "concepts initialized",
            "11/17/2022, 16:55:57"
        ],
        [
            "meta",
            "init",
            "meta initialized",
            "11/17/2022, 16:55:57"
        ],
        [
            "governance",
            "init",
            "governance initialized",
            "11/17/2022, 16:55:57"
        ]
    ],
    "custom": {}
}
```
