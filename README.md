# Node.js with Git Dockerfile

A minimal Dockerfile based on Node.js 16 LTS (Gallium), Node.js 18 LTS (Hydrogen) or Node.js 20 (Iron) alpine with Git, Github CLI and ssh installed.

## What's included

- Node.js 16 LTS (Gallium), 18 LTS (Hydrogen) or 20 (Iron)
- npm 8 (Node.js 16) or npm 9 (Node.js >= 18)
- yarn
- Git
- Github CLI
- ssh

### Available platforms

These Dockerfiles leverage the new `buildx` functionality and offer the following platforms:

- linux/amd64
- linux/arm64
- linux/arm/v7
- linux/arm/v6
- linux/ppc64le
- linux/s390x

---

Released under the MIT license.
