# Truffle Teams<sup> **beta**</sup>

## Overview

Truffle Teams is a new service from TruffleSuite!

Our initial offering is a (free) __zero config__ continuous integration service designed explicitly for your truffle projects!  We've added some natural chocolate polish too, of course :chocolate_bar:

Seamlessly attach your Truffle project to Truffle Teams using GitHub and we'll handle running your automated tests with every commit. It's like Travis CI, but with no additional work by you! You can get started at https://truffleframework.com/teams.

## Getting Started

1. Visit [Truffle Teams](https://my.truffleteams.com/) to sign up with GitHub. You will be automatically redirected to your [dashboard](https://my.truffleteams.com).
2. On your [dashboard](https://my.truffleteams.com), you will be prompted to "Add a repository". This will initiate the installation of Truffle Teams on one or more GitHub repositories.
3. Commit to any truffle project you've added to Truffle Teams! We'll automatically run all of your truffle tests!

## This builds fine on my machine but fails on Truffle Teams! What gives??!

**Q:** Are you using a version of Truffle less than the **v5.x**?  
**A:** Unless your project has a `package.json` file which installs a specific version of Truffle, we'll always try to build with the latest Truffle version.  If your project requires a specific Truffle version, make sure that version is included as a `dependency` or `devDependency` in your project's `package.json` file.

**Q:** Is your build dependent on an external ganache instance?  
 **A:** Currently, Truffle Teams only supports the native truffle development network.

## Support

1. Our Truffle Teams Spectrum chat: https://spectrum.chat/trufflesuite/truffle-teams?tab=posts
2. Our GitHub repository for tracking issues with Truffle Teams: https://github.com/trufflesuite/truffle-teams/issues

Please reach out and let us know what you think!
