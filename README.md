# Node.js with Git Dockerfile

A minimal Dockerfile based on Node.js 16 LTS (Gallium), Node.js 18 LTS (Hydrogen), Node.js 20 (Iron) or Node.js 24 LTS (Krypton) alpine with Git, Github CLI and ssh installed.

## What's included

- Node.js 16 LTS (Gallium), 18 LTS (Hydrogen), 20 (Iron) or 24 LTS (Krypton)
- npm 8 (Node.js 16), npm 9 or 10 (Node.js 18 and 20) or npm 11 (Node.js 24)
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
