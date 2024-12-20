# CHANGELOG


## v1.1.0 (2024-12-20)

### Bug Fixes

- **Version**: Updated version changelog
  ([`14347d6`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/14347d6a3484b7d0aa806d2786275230bcad6c37))


## v0.1.0 (2024-12-20)

### Bug Fixes

- **Releases**: Fixed Releases
  ([`d0134a3`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/d0134a3defc7df4a05739a47f84c119bb17bae10))

- **Releases**: Fixed Releases!
  ([`3390706`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3390706850a6c0d9abee2763aa0ae0d44aeac5c0))

### Features

- **Releases**: Added Auto Release
  ([`a029948`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/a029948406ac614d65db438ef96039f44a9d0b61))


## v1.0.0 (2024-12-20)

### Bug Fixes

- **credits**: #6 Made stored credits private
  ([`e3f7591`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/e3f759178d62f9b0c6ec0c1a391fc719a01812fb))

Denoted the "store_credits" variable in the Credits class with an underscore, which indicates that
  it's a private variable for any other developers, as we don't want people accessing this outside
  of the class

- **Leaderboard**: #9 Corrected method decorators
  ([`e1810c1`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/e1810c1920c93819aa2892308db9c2c0d3c6ca49))

@classmethod was the required decorator for these functions, not @staticmethod.

- **Leaderboard**: #9 Removed logging for Leaderboard
  ([`c3ff490`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/c3ff4908c0d4b305952b8eab9e7cfcc0091e81c1))

Logging was not required (nor set up) for the Leaderboard class as all the logging messages are
  handled in Credits

- **Project**: #4 Add .gitignore
  ([`7b8b9e7`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/7b8b9e757c65c9183c15c193780b88072bdbcc14))

Added a .gitignore for python files

- **Project**: #4 Add requirements.txt
  ([`b2c876d`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/b2c876d35315af498c14949b985f121a4dd0be4d))

### Continuous Integration

- **auto documentation**: #15 Added auto-deploy
  ([`3b53c45`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3b53c45675b40153ba0ec24995f46cbb3847c663))

Added a workflow file that automatically builds and deploys documentation to github pages.

- **dependabot**: #3 Add Dependabot
  ([`87b3511`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/87b3511017b84b496bc562d1af6bff71caa674ac))

Adds Dependabot alerts for Python's pip ecosystem.

Closes: #3

- **unittest**: #4 Created python test workflow
  ([`9aec665`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/9aec665c72652306dbd6967642b22cda0acd8510))

Added a workflow that will run all python tests using unittest when a pull request is opened on the
  main branch.

### Documentation

- **auto documentation**: #15 Created mkdocs
  ([`4a66663`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/4a666633d0febcb4dc0843e48bb727e356c6d25a))

Installed mkdocs and created a mkdocs.yml file that'll be used to serve the documentation server

- **credits**: #15 Add Credits documentation
  ([`7791fe7`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/7791fe75f8d0393004af3ec64152af615f1a126f))

- **Leaderboard**: #9 Add Leaderboard documentation
  ([`3a6e587`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3a6e58787cfc13780e04e4087988444245ddc03f))

- **legal**: #1 Added Code of Conduct
  ([`223e694`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/223e69419663691a861badd213dd5c6dbf0b862f))

- **legal**: #2 Added Security Policy
  ([`1455558`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/1455558155e182e13db7218fb9edd2b6c4eefe15))

Adds a security policy to the project

### Features

- **Cloudformation**: #21 Added IaC files
  ([`80e94af`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/80e94af83249e0566d969cef31a5f6ba2e0fed35))

Closes: #21

- **credits**: #5 Added Credits testing
  ([`6ff2835`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/6ff2835ffbcc3db1441494766cfd2ab765c04df3))

Added unit testing for the Credits class

- **credits**: #5 Created Credits class
  ([`3d45307`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3d4530774d4aeaa0c914eda06af6dd6b532751c3))

Created a credits class that can add/remove/get credits

- **credits**: #6 Updated the unit testing
  ([`92616cc`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/92616ccf8461f5e4a93312d6596d5771cf5a1ad9))

Updated the unit testing to reflect the new credit logic.

This commit fixes the main branch's failing tests for this branch due to this feature no longer
  supporting negative balances

- **credits**: #8 Added logging for credit changes
  ([`e99334d`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/e99334d478dc3264b8d1792d02c9e101efb5c4be))

Added logging info to the functions that alter credits for the user

- **Leaderboard**: #9 Added leaderboard bonus to Credits
  ([`5f10bd3`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/5f10bd31445b70d0d4c7c31baee026497a5f9af2))

- **Leaderboard**: #9 Added leaderboard class
  ([`28eaf44`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/28eaf44cc4dc7d1ab9a8ef74e0ae91e0d5cdd451))

Implemented a leaderboard class which has methods for calculating the bonus received if the new time
  is within the top scores

- **Project**: #4 Add initial files
  ([`3f3e682`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3f3e68260b24d36d3dfa295c4a9b34b50c7d3291))

Created initial files required for the project

### Testing

- **credits**: #7 Implemented unit testing
  ([`06871c2`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/06871c2ea744fd4fb663dea1649ed6e1314e227f))

Added unit testing for the new awards credits function

- **credits**: #9 Update testing for leaderboard
  ([`04a5da5`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/04a5da5003e0ffd5e562fe3ab801882bc1a94308))

- **Leaderboard**: #9 Added Leaderboard class unit testing
  ([`5c91293`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/5c91293cfc867629e95d08b7e509f9d64f3a5bf3))
