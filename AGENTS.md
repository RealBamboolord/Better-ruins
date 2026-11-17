# Better ruins

- Preserve Unciv/GDX's lenient JSON syntax and existing gameplay names.
- No separate build, lint or test runner is defined in this repository.

## Checks

- Run `git diff --check`.
- For native validation, copy the entire mod to a disposable directory, change into that directory, and run `java -jar /absolute/path/Unciv.jar mod-ci` using Java 21 and the official Unciv 4.22.16 JAR.
- Never run `mod-ci` in the working checkout: it repacks images and rewrites JSON.
