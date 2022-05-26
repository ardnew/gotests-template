# gotests-template

Templates for use with:
 - [cweill/gotests](https://github.com/cweill/gotests)

Based on original work from:
 - [Ras96/gotests-template](https://github.com/Ras96/gotests-template)


## Usage

Specify the path to either the `parallel` or `serial` directory (from this repo) using flag `-template_dir`:

```sh
gotests -template_dir="path/to/parallel" path/to/go/sources
```

See `gotests -h` for other flags.


#### VS Code

Add the following to key `go.generateTestsFlags` in `settings.json`:

```json
  "go.generateTestsFlags": [
    "-template_dir=path/to/parallel",
  ],
```

