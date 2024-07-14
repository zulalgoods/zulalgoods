# Tips

run `npx prettier . --check` after making any changes to see if there are files that will fail the prettier check in GHA

run `npx prettier --write $file` to have prettier correct changes to files that have issues

For instance, when updating this readme, prettier found errors. To address:

- `npx prettier . --check`
- `npx prettier --write README.md`
