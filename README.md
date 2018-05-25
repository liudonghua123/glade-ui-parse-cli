# glade-ui-parse-cli
This is a simple cli tool for generating corresponding initial code of glade file. 

### Install
Install globally with [npm](https://www.npmjs.com/):
```bash
npm i -g glade-ui-parse-cli
```

### Usage
Once installed globally, simply run `glade-ui-parse-cli`.

The following are some examples.

```bash
# parse main.glade and generate the same named source code. This is the same as next command.
glade-ui-parse-cli -s main.glade

# parse main.glade and generate source code named main.c.
glade-ui-parse-cli -s main.glade -d main.c

# parse main.glade and just print the generated code.
glade-ui-parse-cli -s main.glade -p
```

##### command Options
Options: -s | --source
Set the source glade ui file.

Options: -d | --destination
Set the destination generated code file.

Options: -p | --print
Do not write to file, just print to screen.

### License
Copyright (c) 2018 Liu.D.H, contributors.
[](LICENSE-MIT)


