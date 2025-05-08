---
name: Release
about: Use this template for release pull requests
title: "Release: [VERSION]"
---

## Summary

**Summary goes here.**

## Checklist

- [ ] Test live demo locally.
- [ ] Publish `@blankon/{common, contract}` if necessary.
- [ ] Publish `@blankon/momoka@<version>` to npm.
- [ ] Update example app to point to new version. Ensure it works.
- [ ] Update package.json to <version + 1>-dev.
