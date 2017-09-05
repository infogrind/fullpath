# fullpath

## Syntax:

    fullpath <file>

Returns the absolute path of `<file>`, where `<file>` can be any relative path
(or absolute path, but that would be rather pointless). The command does not do
any explicit checking if a file actually exists, so

    fullpath asdfsdfiosf

will work perfectly well. If `<file>` contains directory elements, though, the
command will fail if the given path doesn’t exist, because of how the script is
implemented.

## Options:

    Options:
    -h  Display usage instructions
