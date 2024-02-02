### Changeset not respecting .npmrc

Note, this package has an .npmrc file with the registry pointing to a local verdaccio instance

current behavior:
When I run `pnpm changeset publish` it uses npmjs.org

expected:
When I run `pnpm changeset publish` I would expect it to respect the value in the .npmrc file and publish to my local verdaccio instance

note:
When I run `pnpm publish` it uses the verdaccio instance 