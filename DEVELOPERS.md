# Developer Notes

## Publishing New Releases

Each merge to the `main` branch will create a new release using the format `<major>.<minor>.<build number>`.

The `<major>` and `<minor>` need to be updated in any PR which introduces changes beyond simply bug fixes. If the change
is not backwards-compatible, bump "major". Otherwise (this should be most of the time), bump "minor".

The `<build number>` is an always-increasing number from the "publish" GitHub Actions workflow.