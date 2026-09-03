Minecraft modding environment inspector.

`modID` scans your Minecraft directory and provides information about your installed mods and modding environment.

## Usage
```bash
modID <minecraft_directory>
```
Example:
```bash
modID "C:\Users\<you>\.minecraft"
```
### Options
```text
--verbose    Generate detailed mod information -> Coming soon
--json       Output scan results as JSON -> Coming soon
--help       Show help -> Since version 1.0
```
Examples usages(Not implemented):
```bash
modID "C:\Users\banana\.minecraft" --verbose
modID "C:\Users\banana\.minecraft" --json
```
## What it does
- Scans the Minecraft directory
- Detects installed mods
- Reads mod metadata
- Provides detailed information when requested
- Can output machine-readable JSON
## Status
**Current version:** 1.0

This project is still being developed.
## License

All Rights Reserved.
See [`LICENSE`](LICENSE) for details.

## Author
[**Request Timeout**](https://github.com/RequestTimeout)

GitHub: https://github.com/RequestTimeout
