# Contributing to ETMA
If you're reading this, you're awesome! :kissing_heart:

We really thank you for helping us make this project great and being a part of the ETMA community!

Please take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue or assessing patches and features.

## Helping Out
There are several ways to help us out further improve and develop the project:
- :computer: **[Run](https://github.com/GHNewbiee/etma/blob/master/documentation/HowTo_Run)** the application into your system and **[tell]()** us your opinion or thoughts about it; before running it, **please consider** the [Commercial License Agreement](https://github.com/GHNewbiee/etma/blob/master/COMMERCIAL_LICENSE_AGREEMENT.md)
- :earth_africa: **[Translate](https://github.com/GHNewbiee/etma/blob/master/documentation/HowTo_Translate)** the appropriate [files]() into your native language if such a translation has not been available yet
- :clipboard: **[Create](https://github.com/GHNewbiee/etma/issues/new)** a new [issue](https://github.com/GHNewbiee/etma/blob/master/.github/ISSUE_TEMPLATE.md) on GitHub, if you want to suggest a [new feature](https://github.com/GHNewbiee/etma/blob/master/.github/ISSUE_TEMPLATE.md#1) or you have found a [bug](https://github.com/GHNewbiee/etma/blob/master/.github/ISSUE_TEMPLATE.md#2)
- :book: **Enrich** the [documentation](https://github.com/GHNewbiee/etma/tree/master/documentation)
- :pencil: **Write** test cases or **provide** examples for open bug issues
- :pencil: **Write** patches for open bug/feature issues, preferably with test cases included, and finally
- :beers: **Join** the core team


There are as well a few guidelines that contributors need to follow so that we have a chance of keeping on top of things.

## Asking Questions or Telling Opinions & Thoughts
For how-to questions, opinions and thoughts, **please use** :
- [StackOverflow](http://stackoverflow.com/questions/tagged/etma) - tag "etma" is used for tagging questions
- IRC - channel "" on 
- Slack - channel "", or
- [Gitter](https://gitter.im/.../etma) chat/channel

instead of GitHub Issues.

## Coding style
Please follow the coding style of the current code base. ETMA uses eslint, so if possible, enable linting in your editor to get realtime feedback. The linting rules are also run when Webpack recompiles your changes, and can be run manually with `yarn lint`.

You can also run `yarn prettier` to reformat the code.

Finally, when you submit a pull request, they are run again by Circle CI, but hopefully by then your code is already clean!

## Translating


## GitHub Basic
- Run over [GitHub Help](https://help.github.com/) to familiarize yourself with its features and operation
- Read each time the excerpt you are interested in
- [Sign up](https://github.com/signup/free) for an [account](https://help.github.com/articles/signing-up-for-a-new-github-account)

## Branch Structure
All stable releases are tagged ([view tags](https://github.com/GHNewbiee/etma/tags)). At any given time, `develop` represents the latest development version of the application. Patches or hotfix releases are prepared on an independent branch.

### `develop` is unsafe
We will do our best to keep `develop` in good shape, with tests passing at all times. But in order to move fast, we will make API changes that your application might not be compatible with.

## Getting Started with 
- **[Create](https://github.com/GHNewbiee/etma/issues/new)** a new [issue](https://github.com/GHNewbiee/etma/blob/master/.github/ISSUE_TEMPLATE.md), assuming one does not already exist. **Please**,
  * :no_entry: don't group multiple topics into one issue; on the contrary, each topic should be on its own issue, and
  * :no_entry: don't just comment '+1' on an issue. It spams the maintainers and doesn't help move the issue forward.
- Make sure you fill in the earliest version that you know has the issue.
  * Include live link or JSFiddle/Codepen link with the issue if you want it to be discovered and resolved asap. We have few ready templates for you: iOS [JSFiddle](https://jsfiddle.net/s2n1p730/)/[Codepen](https://codepen.io/nolimits4web/pen/WRRWwN), Material [JSFiddle](https://jsfiddle.net/0ogxxcvt/)/[Codepen](https://codepen.io/nolimits4web/pen/pEPPPK)	
- Fork the repository on GitHub.

## Making Changes
- Before working on a large change, you are advised to create a new issue first to discuss it with the maintainers
- Create a topic branch from where you want to base your work.
  * This is usually the master branch.
  * Only target release branches if you are certain your fix must be on that branch.
  * To quickly create a topic branch based on master; `git branch master/my_contribution master` then checkout the new branch with `git checkout master/my_contribution`. Better avoid working directly on the `master` branch, to avoid conflicts if you pull in updates from origin.
- Make commits of logical units.
- Check for unnecessary whitespace with `git diff --check` before committing.
- Use descriptive commit messages and reference the #issue number.

## Submitting Changes
- Keep your pull requests small. To give a PR the best chance of getting accepted, don't bundle more than one feature or bug fix per pull request. It's always best to create two smaller PRs than one big one.
- When adding new features or modifying existing, please attempt to include tests to confirm the new behaviour. You can read more about our test setup here.
- Push your changes to a topic branch in your fork of the repository.
- Submit a pull request to the repository

## Editor Config
The project uses [.editorconfig](http://editorconfig.org/) to define the coding style of each file. We recommend that you install the Editor Config extension for your preferred IDE.


## Roadmap
To get a sense of where ETMA is heading, or for ideas on where you could contribute, take a look at the [ROADMAP](https://github.com/GHNewbiee/etma/blob/develop/ROADMAP.md).

## License
By contributing your code to the GHNewbiee/etma GitHub repository, you agree to license your contribution under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

:earth_africa:

:blue_heart: Many thanks to the community for the content of the current page which is obviously under MIT License.
