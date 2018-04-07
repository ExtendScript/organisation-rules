# Contributing Guide

Thank you for considering to contribute and donate your time to our projects. This guide outlines how to contribute in a way that is efficient for everyone. All contributions are welcome.

## Submitting a pull request

We have adopted [GitHub flow](https://help.github.com/articles/github-flow/) way of working.

  * Fork the project into your personal space
  * Create a feature branch away from the master
  * Write tests and code
  * Generate change-log entries where applicable
  * If you have multiple commits please combine them into a few logically organised commits by [squashing](https://gist.github.com/patik/b8a9dc5cd356f9f6f980) them. Do NOT squash file renames together with file edits. You will end up with lost ancestry history.
  * Someone else reviews & merges your (squashed) commit to origin/master.

Make sure you tested your changes and describe thoroughly what you changed.


## Versioning

Use semantic versioning (semver) as described by [npm](https://docs.npmjs.com/getting-started/semantic-versioning).

In summary, the **first release** is always v1.0.0 and the next update depends on what has changed:

  * **Patch Release** (1.0.1) For bug fixes and other minor changes increment the third digit
  * **Minor Release** (1.1.0) For new features that don't break existing features increment the middle digit
  * **Major Release** (2.0.0) For new features that break backward compatibility increment the first digit 

Thanks!
