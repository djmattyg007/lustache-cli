lustache-cli

lustache-cli is a command-line interface to lustache, the mustache templating
engine for lua. It is developed and tested against lua 5.3, but it may work
just fine with 5.1 and 5.2. It depends on the following libraries:

- lustache (obviously)
- argparse
- luajson

lustache-cli does not currently support partials. Support for this may come in
a future release.

To learn more about lustache, visit the following URL:
https://github.com/Olivine-Labs/lustache
To learn more about mustache templates in general, visit the following URL:
https://mustache.github.io/

A summary of the parameters accepted by the program:

- "-i <input_file>, --input-file <input_file>"

  Supply the input template from a text file.

- "--input-stdin"

  Accept the input template as a string from STDIN.

- "--json-stdin"

  Accept the context for the template as a JSON string from STDIN.

- "-j <json_data>, --json-data <json_data>"

  Used to pass the context as a JSON string from the command line.

- "-J <json_file>, --json-file <json_file>"

  Supply the context as a JSON string from a file.

- "-o <output_file>, --output-file <output_file>"

  Save the render result to a file.

- "-O, --output-stdout"

  When saving the render result to a file, also output the result to STDOUT.

- "-v --version"

  Display version information about lustache-cli and lustache, then exit
  immediately.

- "-h --help"

  Display help text, then exit immediately.


If "--output-file" is not passed, the render result will be output on STDOUT.

Contributions are welcome.

This software is released into the public domain without any warranty.
