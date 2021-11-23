# Changelog

Changelogs are separated by release type for better overview.

## ✅ [Stable Releases][log_release]

> ### “Stable for production!”

These are the official, stable releases that you can use in your production environments.

__BREAKING CHANGES:__
- NEW: Added a OAuth 2.0 method to authentication. [#7248](https://github.com/parse-community/parse-server/issues/7248).
- NEW: Added file upload restriction. File upload is now only allowed for authenticated users by default for improved security. To allow file upload also for Anonymous Users or Public, set the `fileUpload` parameter in the [Parse Server Options](https://parseplatform.org/parse-server/api/master/ParseServerOptions.html). [#7071](https://github.com/parse-community/parse-server/pull/7071). Thanks to [dblythy](https://github.com/dblythy), [Manuel Trezza](https://github.com/mtrezza).
___
Details:
- Stability: *stable*
- NPM channel: `@latest`
- Branch: [release][branch_release]
- Purpose: official release
- Suitable environment: production

## ⚠️ [Beta Releases][log_beta]

> ### “Please try out, we’d love your feedback!”

These are releases that are pretty stable, but may have still some bugs to be fixed before official release.

Details:
- Stability: *pretty stable*
- NPM channel: `@beta`
- Branch: [beta][branch_beta]
- Purpose: feature maturation
- Suitable environment: development

## 🔥 [Alpha Releases][log_alpha]

> ### “If you are curious to see what's next!”

These releases contain the latest development changes, but you should be prepared for anything, including sudden breaking changes or code refactoring. Use this branch to contribute to the project and open pull requests.

Details:
- Stability: *unstable*
- NPM channel: `@alpha`
- Branch: [alpha][branch_alpha]
- Purpose: product development
- Suitable environment: experimental


[log_release]: https://github.com/parse-community/parse-server/blob/release/CHANGELOG.md
<!--[log_release]: https://github.com/parse-community/parse-server/blob/release/changelogs/CHANGELOG_release.md -->
[log_beta]: https://github.com/parse-community/parse-server/blob/beta/changelogs/CHANGELOG_beta.md
[log_alpha]: https://github.com/parse-community/parse-server/blob/alpha/changelogs/CHANGELOG_alpha.md
[branch_release]: https://github.com/parse-community/parse-server/tree/release
[branch_beta]: https://github.com/parse-community/parse-server/tree/beta
[branch_alpha]: https://github.com/parse-community/parse-server/tree/alpha
