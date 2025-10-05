# lid.idutils

> Search an identifier database created by `mkid` (from GNU IDUtils 4.6).
> Quickly find where functions, variables, or symbols are defined or referenced in source files.
> More information: <https://www.gnu.org/software/idutils/manual/html_node/lid-invocation.html>.

- Search for identifiers matching a pattern:

`lid {{pattern}}`

- Perform a case-insensitive search:

`lid -i {{pattern}}`

- Show only filenames that contain a matching identifier:

`lid -f {{pattern}}`

- Search using an extended regular expression:

`lid -R {{regex_pattern}}`

- Display each match with its line number:

`lid -l {{pattern}}`

- Use a specific ID database file (default is `ID` in the current directory):

`lid -d {{path/to/ID}} {{pattern}}`

- List all identifiers stored in the database:

`lid -S`

- Display help for all available options:

`lid --help`
