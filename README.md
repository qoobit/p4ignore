# A collection of useful .p4ignore files for use with Helix Core from Perforce

`.p4ignore` is our collected catch all ignore file that we use for our UE projects

The other corresponding `*.p4ignore` files are snippets for each individual program.

To use these files, first check that you do not have any existing `P4IGNORE` environment variable set by running:

`p4 set`

in command prompt to view your existing environment variables.

To set the value to use the `.p4ignore` file, enter the following in your command prompt:

`p4 set P4IGNORE=.p4ignore`