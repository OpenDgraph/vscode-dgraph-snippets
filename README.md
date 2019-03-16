# Dgraph snippets for vscode.

This extension for Visual Studio Code adds snippets for Dgraph's Query lang and Mutation lang for RDF files, JSON files e other supported extensions.

e.g:

![Prefixes](/images/cap3.png)

## Installation

Launch *Quick Open*
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```
ext install MichelDiz.vscode-dgraph-snippets
```

## Usage

Simple usage is start to write "RDF" or "dgraph" as they are kind of Prefixes.

![Prefixes](/images/cap1.png)

![Prefixes](/images/cap2.png)

### Supported languages
* JSON(.JSON)
* RDF(.RDF)
* javascript(.js)
* typescript(.ts)

## Graphql +- Snippets

|        Snippet          |         Description         |
| ----------------------- | --------------------------- |
| `D-GraphQL-brackets`    | Create curly brackets       |
| `D-GraphQL`             | Query base for all func     |
| `D-GraphQL_ExpandEdges` | Expand All and expand edges |
| `D-GraphQL-Recurse`     | Query base for all func     |

## RDF Snippets

|        Snippet          |         Description            |
| ----------------------- | ------------------------------ |
| `RDF-D`                 | Basic estructure w/ Blank Node |
| `RDF-D_UID`             | Triples to update existing data|
| `RDF-DELETE-SINGLE`     | basic estructure for Delete    |
| `RDF-DELETE-Multiple`   | Delete S P * in RDF            |
| `RDF-DELETE-CLEAN`      | Clean the whole Node - S * *   |
| `RDF-GEO`               | Basic estructure for GEO       |

## JSON-Dgraph Snippets

|           Snippet           |           Description           |
| --------------------------- | ------------------------------- |
| `Dgraph-JSON-Edges-btNodes` | Edges between nodes             |
| `Dgraph-JSON-Add-1Edge`     | Add one Edge with Blank node    |
| `Dgraph-JSON-Facet`         | Add a single Facet              |
| `Dgraph-JSON-Predicate`     | Add a single Predicate          |
| `Dgraph-JSON-Delete-Edge`   | For delete a Edge               |
| `Dgraph-JSON-Delete-S_P_*`  | Delete a Edge for a single pred |
| `Dgraph-JSON-Delete-S_*_*`  | For delete a whole Node         |
| `Dgraph-JSON-1EdgeFacet`    | Add Edge and Facet              |
| `Dgraph-JSON-List`          | Basic JSON list in Dgraph       |
| `Dgraph-JSON-BlanKNode`     | Add just a Blank Node           |
| `Dgraph-JSON-MutationBase`  | Dgraph JSON Base mutation       |
| `Dgraph-JSON-DeleteBase`    | Dgraph JSON Base delete         |


## Known Issues

N/A

## Release Notes


### 0.0.1

Initial release of vscode-dgraph-snippets

### 0.0.2

Added language support for .schema file extension.

-----------------------------------------------------------------------------------------------------------
