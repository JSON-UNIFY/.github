# Auto-generate JSON-Unify documentation with PyUnify


### THE JSON-Unify SPECIFICATION


JSON-Unify is a <em>minimal & simple specification</em> requiring **metadata**, **concepts**, and **data** are in one self-contained JSON object.
```
JSON-Unify = {
	concepts: {},
	data: {},
	meta: {}
}
```

### BENEFITS

No license needed, no technology to budget, buy, or implement. Anyone can use it, an obvious and simple user experience that will help entire teams.
The purpose and benefit of using JSON-Unify is to improve the user experience of those who create, consume, and share data by reducing ambiguitiy and saving time.


### PyUnify IS A WRAPPER TO MAKE WORKING WITH JSON-UNIFY EASY

- PyUnify is a Python library that auto-generates and adds recommended JSON-Unify properties, as well as helper functions like exporting .MD files.
- View the **specification** and **recommendations** to further enrich your data in the specification at: https://github.com/JSON-UNIFY.
- For example, a few 'meta' recommended fields are: a description of the data, the source of the data, the author of the data, the data contract URL.
To instantiate this JSON-Unify data contract with PyUnify:

- Copy the JSON code in this MD file below.
- In your **Python Notebook**:
```
!pip install PyUnify
import PyUnify
unify = PyUnify(paste_json_from_this_MD_file)
```

This markdown file was automatically generated with 
```
unify.md()
```

To edit the title of the documentation use: 
```
unify.md({'title':'My title here'})
```

Otherwise, the title will be auto-generated from the meta name property

## Example PyUnify .MD output when the only input is a data set

### PyUnify can guide you step-by-step to fill out empty tables and fields in order to enrich the discoverability and quality of the data experience you are creating for those that will use your data.
## Concepts - Headers
Any documentation or the concepts used in the headers of your data table.
```
|    | name               | type   | description   | wikidata   |
|---:|:-------------------|:-------|:--------------|:-----------|
|  0 | ID                 |        |               |            |
|  1 | First name         |        |               |            |
|  2 | Last name          |        |               |            |
|  3 | Birth year         |        |               |            |
|  4 | Height             |        |               |            |
|  5 | Birthplace         |        |               |            |
|  6 | Identity is secret |        |               |            |
|  7 | Can fly            |        |               |            |
|  8 | Alignment          |        |               |            |
|  9 | Wears cape         |        |               |            |
```
## Concepts - Values
Any documentation or the concepts used in the values of acolumn in your data table.
```

```
## Data
The data of your JSON-Unify object.
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
## Meta
Any documentation of the metadata used to describe and discover your data.
```
|    | Key         | Value                         |
|---:|:------------|:------------------------------|
|  0 | contract    | https://github.com/JSON-UNIFY |
|  1 | description |                               |
|  2 | source      |                               |
|  3 | table       |                               |
|  4 | query       |                               |
|  5 | tags        |                               |
|  6 | authors     |                               |
|  7 | id          |                               |
|  8 | contact     |                               |
|  9 | name        |                               |
```
## Governance - SLA
Any documentation of any SLA information.
```
| NAME   | TYPE   | DESCRIPTION   | REQUIREMENTS   |
|--------|--------|---------------|----------------|
```

## JSON-Unify Object (file)
This is the JavaScript Object Notation representation of your PyUnify Object. You could save this to a file and import it, use it in Javascript, etc.


```
{
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
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null
            ],
            "description": [
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null
            ],
            "wikidata": [
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null,
                null
            ]
        },
        "values": {}
    },
    "compute": {
        "function": [],
        "event listener description": []
    },
    "custom": {},
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
    "governance": {
        "sla": {
            "NAME": [],
            "TYPE": [],
            "DESCRIPTION": [],
            "REQUIREMENTS": []
        }
    },
    "lineage": {},
    "meta": {},
    "project": {
        "description": [],
        "status": [],
        "date": []
    }
}
```
## JSON-Unify Object (string)
Use this version to copy and paste into Jupyter Notebook to create a PyUnify Object


```
'{"concepts": {"headers": {"name": ["ID", "First name", "Last name", "Birth year", "Height", "Birthplace", "Identity is secret", "Can fly", "Alignment", "Wears cape"], "type": [null, null, null, null, null, null, null, null, null, null], "description": [null, null, null, null, null, null, null, null, null, null], "wikidata": [null, null, null, null, null, null, null, null, null, null]}, "values": {}}, "compute": {"function": [], "event listener description": []}, "custom": {}, "data": [["ID", "First name", "Last name", "Birth year", "Height", "Birthplace", "Identity is secret", "Can fly", "Alignment", "Wears cape"], ["7435", "Bruce", "Wayne", "1969*", "6\'2\\"", "Gotham", "Y", "3", "anti-villain", "black"], ["0958", "Ororo", "Munroe", "--1979--", "5\'11\\"", "Manhattan", "", "9", "good", "long"], ["9471", "Diana", "Trevor", "1618", "5\'8\\"", "Paradise Island", "Y", "Jet", "truth", "rarely"], ["9483", "Janet", "Van Dyne", "19.42", "5\'4\\"", "Cresskill", "", "tiny", "Good", "Not really"], ["0696", "Peter", "Parker", "11111983", "5\'10\\"", "Queens", "Y", "Fall", "right", "never"], ["5531", "Harleen", "Quinzell", "1981", "6\'0\\"", "Gotham", "Y", "", "evil", "no"], ["4734", "Erik", "Lehnsherr", "1-9-8-3", "5\'7\\"", "Hamburg", "", "Lev.", "mutants", "Absolutely"], ["7757", "Natasha", "Romanova", "1983", "5\'6\\"", "St. Petersburg", "", "jet", "depends", "No way"], ["0323", "Jean", "Grey", "\\"1977\\"", "6\'4\\"", "Annandale", "", "No", "good", "Mostly not"], ["3980", "Clark", "Kent", "\\"1954\\"", "6\'2\\"", "Krypton", "Y", "12", "Truth", "always"], ["3057", "Victor", "Von Doom", "\\"1943\\"", "6\'2\\"", "Latveria", "", "1", "Bad", "yes"], ["0573", "Stephen", "Strange", "1968", "6\'2\\"", "Philidelphia", "", "not", "light", "T"], ["7452", "Thor", "Odinson", "2287 BC", "6\'6\\"", "Norway", "", "10", "Good", "Of course"], ["1437", "Selina", "Kyle", "1998", "5\'7\\"", "Gotham", "Y", "NA", "Neutral", "It clashes"], ["1883", "Raven", "Darkholme", "..1911..", "5\'10\\"", "unknown", "Y", "no", "mostly bad", "Not really"], ["5830", "Kara", "Zor-el", "1961", "5\'7\\"", "Krypton", "Y", "fast", "G", "yes"]], "governance": {"sla": {"NAME": [], "TYPE": [], "DESCRIPTION": [], "REQUIREMENTS": []}}, "lineage": {}, "meta": {}, "project": {"description": [], "status": [], "date": []}}'
```
