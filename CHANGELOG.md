# CHANGELOG


## v0.1.0 (2024-12-20)

### Bug Fixes

* fix(Leaderboard): #9 Removed logging for Leaderboard

Logging was not required (nor set up) for the Leaderboard class as all the logging messages are handled in Credits ([`c3ff490`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/c3ff4908c0d4b305952b8eab9e7cfcc0091e81c1))

* fix(Leaderboard): #9 Corrected method decorators

@classmethod was the required decorator for these functions, not @staticmethod. ([`e1810c1`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/e1810c1920c93819aa2892308db9c2c0d3c6ca49))

* fix(credits): #6 Made stored credits private

Denoted the "store_credits" variable in the Credits class with an underscore, which indicates that it's a private variable for any other developers, as we don't want people accessing this outside of the class ([`e3f7591`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/e3f759178d62f9b0c6ec0c1a391fc719a01812fb))

* fix(Project): #4 Add .gitignore

Added a .gitignore for python files ([`7b8b9e7`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/7b8b9e757c65c9183c15c193780b88072bdbcc14))

* fix(Project): #4 Add requirements.txt ([`b2c876d`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/b2c876d35315af498c14949b985f121a4dd0be4d))

### Continuous Integration

* ci(auto documentation): #15 Added auto-deploy

Added a workflow file that automatically builds and deploys documentation to github pages. ([`3b53c45`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3b53c45675b40153ba0ec24995f46cbb3847c663))

* ci(unittest): #4 Created python test workflow

Added a workflow that will run all python tests using unittest when a pull request is opened on the main branch. ([`9aec665`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/9aec665c72652306dbd6967642b22cda0acd8510))

* ci(dependabot): #3 Add Dependabot

Adds Dependabot alerts for Python's pip ecosystem.

Closes: #3 ([`87b3511`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/87b3511017b84b496bc562d1af6bff71caa674ac))

### Documentation

* docs(Leaderboard): #9 Add Leaderboard documentation ([`3a6e587`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3a6e58787cfc13780e04e4087988444245ddc03f))

* docs(credits): #15 Add Credits documentation ([`7791fe7`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/7791fe75f8d0393004af3ec64152af615f1a126f))

* docs(auto documentation): #15 Created mkdocs

Installed mkdocs and created a mkdocs.yml file that'll be used to serve the documentation server ([`4a66663`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/4a666633d0febcb4dc0843e48bb727e356c6d25a))

* docs(legal): #2 Added Security Policy

Adds a security policy to the project ([`1455558`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/1455558155e182e13db7218fb9edd2b6c4eefe15))

* docs(legal): #1 Added Code of Conduct ([`223e694`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/223e69419663691a861badd213dd5c6dbf0b862f))

### Features

* feat(Releases): Create Auto Releases.

Automatically generates CHANGELOG.md and creates a GitHub release. ([`9bf4259`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/9bf425909912a48a5fb3e3b83746636feb02a078))

* feat(Cloudformation): #21 Added IaC files

Closes: #21 ([`80e94af`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/80e94af83249e0566d969cef31a5f6ba2e0fed35))

* feat(Leaderboard): #9 Added leaderboard bonus to Credits ([`5f10bd3`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/5f10bd31445b70d0d4c7c31baee026497a5f9af2))

* feat(Leaderboard): #9 Added leaderboard class

Implemented a leaderboard class which has methods for calculating the bonus received  if the new time is within the top scores ([`28eaf44`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/28eaf44cc4dc7d1ab9a8ef74e0ae91e0d5cdd451))

* feat(credits): #8 Added logging for credit changes

Added logging info to the functions that alter credits for the user ([`e99334d`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/e99334d478dc3264b8d1792d02c9e101efb5c4be))

* feat(credits): #6 Updated the unit testing

Updated the unit testing to reflect the new credit logic.

This commit fixes the main branch's failing tests for this branch due to this feature no longer supporting negative balances ([`92616cc`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/92616ccf8461f5e4a93312d6596d5771cf5a1ad9))

* feat(credits): #5 Added Credits testing

Added unit testing for the Credits class ([`6ff2835`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/6ff2835ffbcc3db1441494766cfd2ab765c04df3))

* feat(credits): #5 Created Credits class

Created a credits class that can add/remove/get credits ([`3d45307`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3d4530774d4aeaa0c914eda06af6dd6b532751c3))

* feat(Project): #4 Add initial files

Created initial files required for the project ([`3f3e682`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/3f3e68260b24d36d3dfa295c4a9b34b50c7d3291))

### Testing

* test(Leaderboard): #9 Added Leaderboard class unit testing ([`5c91293`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/5c91293cfc867629e95d08b7e509f9d64f3a5bf3))

* test(credits): #9 Update testing for leaderboard ([`04a5da5`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/04a5da5003e0ffd5e562fe3ab801882bc1a94308))

* test(credits): #7 Implemented unit testing

Added unit testing for the new awards credits function ([`06871c2`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/06871c2ea744fd4fb663dea1649ed6e1314e227f))

### Unknown

* feature(credits): #7 Added an award credits function

Added a function that calculates how many credits should be awarded based on the time taken and adds them to the current class's _stored_credits ([`4d10efc`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/4d10efc5009cb9b26b32afcbd1e40462cf483a1c))

* feature(credits): #6 Added credits spending logic

Added validation to credits that ensures that you cannot remove more credits than are there, and can't add negative credits. ([`6dbce49`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/6dbce49b95d32df6f571cae40f554ba8f9f2bb09))

* Initial commit ([`d59141d`](https://github.com/FuriaPaladins/SpeedrunningLeagueBadges/commit/d59141d310a2ab049ea7058c5e500ae771f6cfed))
