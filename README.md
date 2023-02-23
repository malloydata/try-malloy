# Try Malloy!

### Click [here](https://github.dev/malloydata/try-malloy/blob/main/airports.malloy#L13) to try Malloy instantly in your browser

This repository contains a quick start for trying Malloy in VS Code. It can be used directly on [Github's online editor](https://github.dev/malloydata/try-malloy/blob/main/airports.malloy#L13), on [vscode.dev](https://vscode.dev/github/malloydata/try-malloy), or inside a local VS Code instance.

All that is required is an instance of VS Code and the Malloy extenion - the extension can be installed by clicking on the Extensions section in the left sidebar and searching for "Malloy".

This repository contains two important files:

* A CSV file with information about US airports
* An `airports.malloy` file that contains a simple Malloy model that operates on the CSV file.

When `airports.malloy` is opened, the Malloy extension reads the model, which tells it to load `airports.csv` into a local instance of DuckDB, which is embedded in the Malloy extenion. Once the data is loaded into DuckDB, the schema is read, and the model is ready to be used. Click the "run" button above any query to execture the query.
