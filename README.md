# tabularis-jdbc-derby

Apache Derby driver for [Tabularis](https://tabularis.dev), powered by JDBC and [JBang](https://jbang.dev).

Part of the [tabularis-jdbc](https://github.com/tabularis-jdbc/tabularis-jdbc) family — a single generic JDBC engine packaged per database with the right Tabularis capabilities.

## Install

Download the latest release zip from [Releases](https://github.com/tabularis-jdbc/tabularis-jdbc-derby/releases), extract into the Tabularis plugins folder:

| Platform | Path |
|----------|------|
| macOS    | `~/Library/Application Support/tabularis/plugins/jdbc-derby/` |
| Linux    | `~/.local/share/tabularis/plugins/jdbc-derby/` |
| Windows  | `%APPDATA%\tabularis\plugins\jdbc-derby\` |

Restart Tabularis. **Apache Derby** appears in the connection catalogue.

## Connection

Use the database field with a JDBC URL (the `jdbc:` prefix is optional):

```
derby:/path/to/database
```

## Requirements

- Java 17+ (JBang bootstraps itself)

## Development

This plugin is generated from [tabularis-jdbc](https://github.com/tabularis-jdbc/tabularis-jdbc). To modify the core JDBC engine, contribute there.
