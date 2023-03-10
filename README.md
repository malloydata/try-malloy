# Try Malloy

### [Click here](https://github.dev/malloydata/try-malloy/blob/main/airports.malloy) to try Malloy instantly in your browser

This repository is a quick-start for playing with Malloy in VS Code. It can be used directly on [Github's online editor](https://github.dev/malloydata/try-malloy/blob/main/airports.malloy), on [vscode.dev](https://vscode.dev/github/malloydata/try-malloy), or inside a local VS Code instance. All that is required is an instance of VS Code and the Malloy extension. The extension can be installed by clicking on the Extensions section in the left sidebar and searching for "Malloy", or by opening `airports.malloy` and waiting for VS Code to suggest the Malloy extension.

The repository contains two important files:

* A CSV file, `airports.csv`, with information about US airports
* An `airports.malloy` file that contains a simple Malloy model that operates on the CSV file.

When `airports.malloy` is opened, the Malloy extension reads the file - a Malloy model - which tells the extension to load `airports.csv` into a local instance of DuckDB that is included by the extension. Once the data is loaded into DuckDB and the schema is read, the model is ready to be used.

There are instructions in the file for how to try a few things - [go check it out](https://github.dev/malloydata/try-malloy/airports.malloy)! And follow along with the [quick start](https://malloydata.github.io/documentation/user_guides/basic.html) if you'd like to learn more.

## Additional Resources:

* [Malloy Home Page](https://www.malloydata.dev)
* [Docs and Guides](https://malloydata.github.io/documentation/)
* [Malloy Github repository](https://github.com/malloydata/malloy/)
* Join our [Slack community](https://join.slack.com/t/malloy-community/shared_invite/zt-1kgfwgi5g-CrsdaRqs81QY67QW0~t_uw)
