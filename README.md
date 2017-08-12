# shark

A bad replacement for cabal/stack, with the goals of speed and simplicity, aimed more towards applications than libraries. To use:

* Install `shark`.
* Compile your program with `stack`.
* Now run `shark run name_of_exe -- my arguments` or `shark run Name.Of.Module -- my arguments`

Compared to `stack build project --exec="name_of_exe my arguments"` you should notice that it's faster.
