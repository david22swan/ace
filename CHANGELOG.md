# Changelog

All significant changes to this repo will be summarized in this file.


## [v0.10.0](https://github.com/puppetlabs/ace/tree/v0.10.0) (2019-07-25)
[Full Changelog](https://github.com/puppetlabs/ace/compare/v0.9.1...v0.10.0)

**Merged pull requests:**

- fixed rubocop offenses [\#46](https://github.com/puppetlabs/ace/pull/46) ([Lavinia-Dan](https://github.com/Lavinia-Dan))
- \(FM-8106\) Workaround license\_finder issue [\#45](https://github.com/puppetlabs/ace/pull/45) ([DavidS](https://github.com/DavidS))
- \(FM-7953\) Add acceptance tests to travis [\#43](https://github.com/puppetlabs/ace/pull/43) ([da-ar](https://github.com/da-ar))
- \(maint\) making it clear on order of running the containers [\#42](https://github.com/puppetlabs/ace/pull/42) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(FM-7954\) plugin cache purge for stale environments [\#41](https://github.com/puppetlabs/ace/pull/41) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(maint\) fixing up the docker setup for executing catalogs [\#40](https://github.com/puppetlabs/ace/pull/40) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(maint\) Docker doc update [\#39](https://github.com/puppetlabs/ace/pull/39) ([willmeek](https://github.com/willmeek))
- \(FM-7927\) Update developer docs [\#38](https://github.com/puppetlabs/ace/pull/38) ([DavidS](https://github.com/DavidS))
- \(FM-7975\) Remove mock responses from /execute\_catalog endpoint [\#37](https://github.com/puppetlabs/ace/pull/37) ([da-ar](https://github.com/da-ar))

## [v0.9.1](https://github.com/puppetlabs/ace/tree/v0.9.1) (2019-04-16)
[Full Changelog](https://github.com/puppetlabs/ace/compare/v0.9.0...v0.9.1)

**Fixed bugs:**

- \(maint\) remove load\_config parameter [\#34](https://github.com/puppetlabs/ace/pull/34) ([da-ar](https://github.com/da-ar))

**Merged pull requests:**

- \(maint\) Release prep for v0.9.1 [\#36](https://github.com/puppetlabs/ace/pull/36) ([willmeek](https://github.com/willmeek))
- \(FM-7927\) Docs review [\#35](https://github.com/puppetlabs/ace/pull/35) ([clairecadman](https://github.com/clairecadman))

## [v0.9.0](https://github.com/puppetlabs/ace/tree/v0.9.0) (2019-04-16)
**Implemented enhancements:**

- \(FM-7922\) running the configuration to apply catalog to transport  [\#30](https://github.com/puppetlabs/ace/pull/30) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(FM-7893\) construct the trusted facts required for catalog requests [\#26](https://github.com/puppetlabs/ace/pull/26) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(FM-7886\) initialise remote transport for catalog apply [\#25](https://github.com/puppetlabs/ace/pull/25) ([willmeek](https://github.com/willmeek))
- \(FM-7883\) execute plugin sync from a puppetserver [\#20](https://github.com/puppetlabs/ace/pull/20) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(FM-7826\) first pass of execute catalog docs and mock API endpoint [\#16](https://github.com/puppetlabs/ace/pull/16) ([DavidS](https://github.com/DavidS))
- Utilities for environment isolation per request [\#12](https://github.com/puppetlabs/ace/pull/12) ([willmeek](https://github.com/willmeek))
- \(PE-25514\) Add docker support for ACE [\#3](https://github.com/puppetlabs/ace/pull/3) ([da-ar](https://github.com/da-ar))
- \(PE-25508\) Add JSON Schema and validation example [\#2](https://github.com/puppetlabs/ace/pull/2) ([da-ar](https://github.com/da-ar))

**Fixed bugs:**

- \(FM-7959\) Handle CA certificate bundles and CRL bundles [\#33](https://github.com/puppetlabs/ace/pull/33) ([Thomas-Franklin](https://github.com/Thomas-Franklin))

**Merged pull requests:**

- \(FM-7927\) update developer docs pre-release [\#32](https://github.com/puppetlabs/ace/pull/32) ([DavidS](https://github.com/DavidS))
- \(FM-7952\) allow reports from ACE in testing auth.conf [\#31](https://github.com/puppetlabs/ace/pull/31) ([DavidS](https://github.com/DavidS))
- \(maint\) adding block passthrough to the libdir core method [\#28](https://github.com/puppetlabs/ace/pull/28) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(maint\) additional admin endpoints from bolt-server [\#27](https://github.com/puppetlabs/ace/pull/27) ([DavidS](https://github.com/DavidS))
- \(FM-7882\) Add client for catalog retrieval [\#24](https://github.com/puppetlabs/ace/pull/24) ([da-ar](https://github.com/da-ar))
- \(maint\) Update to bolt 1.15.0 [\#22](https://github.com/puppetlabs/ace/pull/22) ([DavidS](https://github.com/DavidS))
- \(maint\) adding instructions on generating aceserver cert on docker co… [\#21](https://github.com/puppetlabs/ace/pull/21) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(maint\) adjusted the development puppetserver to no longer use custom certs [\#19](https://github.com/puppetlabs/ace/pull/19) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(FM-7869\) Implement a Remote Task [\#18](https://github.com/puppetlabs/ace/pull/18) ([da-ar](https://github.com/da-ar))
- \(maint\) copy edit API docs [\#15](https://github.com/puppetlabs/ace/pull/15) ([DavidS](https://github.com/DavidS))
- \(FM-7872\) adding in the acls for the ace service [\#14](https://github.com/puppetlabs/ace/pull/14) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(maint\) work on adding the required files for the vanagon build [\#13](https://github.com/puppetlabs/ace/pull/13) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- \(maint\) the required docker changes for puppetserver work [\#11](https://github.com/puppetlabs/ace/pull/11) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- Update README.md [\#10](https://github.com/puppetlabs/ace/pull/10) ([willmeek](https://github.com/willmeek))
- \(maint\) reworking of the configuration [\#5](https://github.com/puppetlabs/ace/pull/5) ([Thomas-Franklin](https://github.com/Thomas-Franklin))
- Update JSONSchema, and mock endpoint [\#4](https://github.com/puppetlabs/ace/pull/4) ([da-ar](https://github.com/da-ar))
- \(PE-25509\) first fake endpoint; rubocop [\#1](https://github.com/puppetlabs/ace/pull/1) ([DavidS](https://github.com/DavidS))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*