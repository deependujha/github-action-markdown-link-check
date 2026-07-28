# Maintainer Instructions

Update `entrypoint.sh` with new `markdown-link-check` version.

Update `CHANGELOG.md`

Commit and tag release. Update v1 tag and push.

```
git tag v1.1.3
git tag --force v1 v1.1.3
git push origin --force v1
git push --tags
```
