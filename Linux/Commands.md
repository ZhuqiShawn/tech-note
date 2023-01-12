## echo
Display line of text/string, mostly used in shell scripts and batch files to output status text to the screen or a file.

**Syntax**:
```bash
echo [option] [string]`
```

**Options**: 
| Option |                   Description                   |                        example |
|:------ |:-----------------------------------------------:| ------------------------------:|
| `-n`   |          omit echoing trailing newline          |    `echo -n "Geeks for Geeks"` |
| `*`    |             print all files/folders             |                   `echo *` |
| `-e`   | enables the interpretation of backslash escapes | `echo -e "Geeks \nfor \nGeeks"` |
