# keride

Rust library for Key Event Receipt Infrastructure.

[![keride](https://github.com/WebOfTrust/keride/actions/workflows/test.yml/badge.svg)](https://github.com/WebOfTrust/keride/actions/workflows/test.yml)
[![codecov](https://codecov.io/gh/WebOfTrust/keride/branch/main/graph/badge.svg?token=L8K7H1XXQS)](https://codecov.io/gh/WebOfTrust/keride)


### Features
* [cesr](src/cesr/README.md) - Cryptographic primitives for use with Composable Event Streaming Representation.
* `signing`
* `prefixing`
* `pathing`
* `parsing`


This library is **currently under construction**. If you want to help build, see [contributing](#contributing) below.

## Important Reference Material
- WebOfTrust/[ietf-keri](https://github.com/WebOfTrust/ietf-keri) repository - IETF draft specification for KERI
- WebOfTrust/[ietf-cesr](https://github.com/WebOfTrust/ietf-cesr) repository - IETF draft specification for CESR
- Design Assumptions, Use Cases, and ToDo list - [HackMD link](https://hackmd.io/W2Z39cuSSTmD2TovVLvAPg?view)
- Introductory articles:
    - [#1 CESR Proof Signatures](https://medium.com/happy-blockchains/cesr-proof-signatures-are-the-segwit-of-authentic-data-in-keri-e891c83e070a)
    - [#2 CESR Overview](https://medium.com/happy-blockchains/cesr-one-of-sam-smiths-inventions-is-as-controversial-as-genius-d757f36b88f8)

## Contributing

If you want to contribute, check out the [issues](https://github.com/WebOfTrust/keride/issues).
Tags provide some guidance.

When starting a new issue, ensure there are no others working on the same thing to avoid duplicated
effort (although alternative implementations are always welcome and considered):
- check that there is no open pull request
- make sure no one has assigned themselves
- look for comments on the issue
- look for development integrations ('linked an issue that may be closed by this pull request')

When you find an issue you want to take on:
- make yourself an assignee, if possible
- open a [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) against a branch you created against your fork - even if empty
- paste a link to the PR in a comment on the issue you are working on for visibility

For better coordination, join the `#cesr-dev` slack channel using the link at the bottom of
this document.


