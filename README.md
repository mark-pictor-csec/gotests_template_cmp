Templates for `gotests`. Pass in using `-template_dir`.

### enable in vscode

this can be added in the gui or by editing the json

in the gui, add two args: `-template_dir` `/path/to/gotests_template_cmp`

or in json:
```json
    "go.generateTestsFlags": [
        "-template_dir","/path/to/gotests_template_cmp"
    ],
```

