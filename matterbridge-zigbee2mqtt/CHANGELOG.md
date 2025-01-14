Changes in this Release

<details><summary>edd6296 chore: bump matterbridge from 1.7.1 to 1.7.3 in /matterbridge-zigbee2mqtt (#99)</summary>
chore: bump matterbridge from 1.7.1 to 1.7.3 in /matterbridge-zigbee2mqtt (#99)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.7.1
to 1.7.3.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.7.3</h2>
<h2>[1.7.3] - 2025-01-11</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added selectDevice list to deviceFeatureBlackList to get
the device names from a list in the config editor.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[frontend]: Frontend v.2.3.11</li>
<li>[package]: Workflows use node 22.x.</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 1.7.2</h2>
<h2>[1.7.2] - 2025-01-11</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added selectEntity to get the entity names from a list
in the config editor.</li>
<li>[websocket]: Added api /api/select/entities.</li>
<li>[frontend]: Added the possibility to reorder the items in the config
editor lists.</li>
<li>[frontend]: Added custom error messages for ErrorListTemplate and
FieldErrorTemplate in react-jsonschema-form for validation in the config
editor.</li>
<li>[frontend]: Added filter by device name and serial number to Devices
page.</li>
<li>[frontend]: Added Icon view to the Devices page (beta).</li>
<li>[frontend]: Added the possibility to select the entities/components
from a list in the config editor.</li>
<li>[matterbridge]: Added /health endpoint for watchdog.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[frontend]: Frontend v.2.3.10</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[edge]: Fixed ValveConfigurationAndControlServer behavior.</li>
<li>[frontend]: Fixed restart that was not working correctly in
Ingress.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/blob/main/CHANGELOG.md">matterbridge's
changelog</a>.</em></p>
<blockquote>
<h2>[1.7.3] - 2025-01-11</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added selectDevice list to deviceFeatureBlackList to get
the device names from a list in the config editor.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[frontend]: Frontend v.2.3.11</li>
<li>[package]: Workflows use node 22.x.</li>
</ul>
<!-- raw HTML omitted -->
<h2>[1.7.2] - 2025-01-11</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added selectEntity to get the entity names from a list
in the config editor.</li>
<li>[websocket]: Added api /api/select/entities.</li>
<li>[frontend]: Added the possibility to reorder the items in the config
editor lists.</li>
<li>[frontend]: Added custom error messages for ErrorListTemplate and
FieldErrorTemplate in react-jsonschema-form for validation in the config
editor.</li>
<li>[frontend]: Added filter by device name and serial number to Devices
page.</li>
<li>[frontend]: Added Icon view to the Devices page (beta).</li>
<li>[frontend]: Added the possibility to select the entities/components
from a list in the config editor.</li>
<li>[matterbridge]: Added /health endpoint for watchdog.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[frontend]: Frontend v.2.3.10</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[edge]: Fixed ValveConfigurationAndControlServer behavior.</li>
<li>[frontend]: Fixed restart that was not working correctly in
Ingress.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/97d96296d42c14fa6f6072a5154b6c882c62739c"><code>97d9629</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/205">#205</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4bc2f2d651580751a0e3e018253263b38001fb49"><code>4bc2f2d</code></a>
Release 1.7.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a8a0ab54b5d419a911900d8cc4c1e589383ff9f6"><code>a8a0ab5</code></a>
Update Node.js version in build workflows</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/363a85d5e6c661fe5a31f8a9efe12638805ecb4c"><code>363a85d</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/203">#203</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8015e021ecd33e1a5256a90c2cdf4aa6d479a76c"><code>8015e02</code></a>
Release 1.7.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/28011fc650851f3a3ecc29e2d04d51d309ee4f9b"><code>28011fc</code></a>
Frontend 2.3.10</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b25b5d31f53ed3b0d3c516fdc76aa90984cabd65"><code>b25b5d3</code></a>
Bump version to 1.7.2-dev.8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d53aba011511d6e9b801c8288b0454f49576485f"><code>d53aba0</code></a>
Bump version to 1.7.2-dev.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7ad47b16f31663587f8674566afc5bf1f0ea06f7"><code>7ad47b1</code></a>
Bump version to 1.7.2-dev.6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/71e2a3f67985f7f1dbb2ceb57ebd3a087f703d78"><code>71e2a3f</code></a>
Bump version to 1.7.2-dev.6</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.7.1...1.7.3">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.7.1&new-version=1.7.3)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

Dependabot will resolve any conflicts with this PR as long as you don't
alter it yourself. You can also trigger a rebase manually by commenting
`@dependabot rebase`.

[//]: # (dependabot-automerge-start)
[//]: # (dependabot-automerge-end)

---

<details>
<summary>Dependabot commands and options</summary>
<br />

You can trigger Dependabot actions by commenting on this PR:
- `@dependabot rebase` will rebase this PR
- `@dependabot recreate` will recreate this PR, overwriting any edits
that have been made to it
- `@dependabot merge` will merge this PR after your CI passes on it
- `@dependabot squash and merge` will squash and merge this PR after
your CI passes on it
- `@dependabot cancel merge` will cancel a previously requested merge
and block automerging
- `@dependabot reopen` will reopen this PR if it is closed
- `@dependabot close` will close this PR and stop Dependabot recreating
it. You can achieve the same result by closing it manually
- `@dependabot show <dependency name> ignore conditions` will show all
of the ignore conditions of the specified dependency
- `@dependabot ignore this major version` will close this PR and stop
Dependabot creating any more for this major version (unless you reopen
the PR or upgrade to it yourself)
- `@dependabot ignore this minor version` will close this PR and stop
Dependabot creating any more for this minor version (unless you reopen
the PR or upgrade to it yourself)
- `@dependabot ignore this dependency` will close this PR and stop
Dependabot creating any more for this dependency (unless you reopen the
PR or upgrade to it yourself)


</details>

Signed-off-by: dependabot[bot] <support@github.com>
Co-authored-by: dependabot[bot] <49699333+dependabot[bot]@users.noreply.github.com></details>

<details><summary>2ebd893 chore: bump matterbridge-zigbee2mqtt from 2.4.0 to 2.4.2 in /matterbridge-zigbee2mqtt (#98)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.4.0 to 2.4.2 in /matterbridge-zigbee2mqtt (#98)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.4.0 to 2.4.2.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.4.2</h2>
<h2>[2.4.2] - 2025-01-11</h2>
<h3>Fixed</h3>
<ul>
<li>[endpoint]: Fixed blacklist of child endpoints.</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 2.4.1</h2>
<h2>[2.4.1] - 2025-01-11</h2>
<h3>Added</h3>
<ul>
<li>[selectEntity]: Added selectEntity to get the features names from a
list in the config editor.</li>
<li>[configUrl]: Added zigbeeFrontend in the config to prefix configUrl
to get a link to the zigbee2mqtt frontend from the Matterbridge frontend
Devices page. This allows to open the device configuration from the
frontend.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[plugin]: Requires Matterbridge 1.7.2.</li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/blob/main/CHANGELOG.md">matterbridge-zigbee2mqtt's
changelog</a>.</em></p>
<blockquote>
<h2>[2.4.2] - 2025-01-11</h2>
<h3>Fixed</h3>
<ul>
<li>[endpoint]: Fixed blacklist of child endpoints.</li>
</ul>
<!-- raw HTML omitted -->
<h2>[2.4.1] - 2025-01-11</h2>
<h3>Added</h3>
<ul>
<li>[selectEntity]: Added selectEntity to get the features names from a
list in the config editor.</li>
<li>[configUrl]: Added zigbeeFrontend in the config to prefix configUrl
to get a link to the zigbee2mqtt frontend from the Matterbridge frontend
Devices page. This allows to open the device configuration from the
frontend.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[plugin]: Requires Matterbridge 1.7.2.</li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/f956503990b6ed8c6fc38518d03a29ee11c3a42f"><code>f956503</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/93">#93</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/5411708ad304ef90bb410edf69b30d1b849224f0"><code>5411708</code></a>
Release version 2.4.2; fix blacklist of child endpoints and update
logging to...</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/a839a72b64c3f11d53cb64e46bca8ed20b8dca92"><code>a839a72</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/92">#92</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/b7bea34a70785f444b2b799c6d13d8478c1ed577"><code>b7bea34</code></a>
Release 2.4.1</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.4.0...2.4.2">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.4.0&new-version=2.4.2)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

Dependabot will resolve any conflicts with this PR as long as you don't
alter it yourself. You can also trigger a rebase manually by commenting
`@dependabot rebase`.

[//]: # (dependabot-automerge-start)
[//]: # (dependabot-automerge-end)

---

<details>
<summary>Dependabot commands and options</summary>
<br />

You can trigger Dependabot actions by commenting on this PR:
- `@dependabot rebase` will rebase this PR
- `@dependabot recreate` will recreate this PR, overwriting any edits
that have been made to it
- `@dependabot merge` will merge this PR after your CI passes on it
- `@dependabot squash and merge` will squash and merge this PR after
your CI passes on it
- `@dependabot cancel merge` will cancel a previously requested merge
and block automerging
- `@dependabot reopen` will reopen this PR if it is closed
- `@dependabot close` will close this PR and stop Dependabot recreating
it. You can achieve the same result by closing it manually
- `@dependabot show <dependency name> ignore conditions` will show all
of the ignore conditions of the specified dependency
- `@dependabot ignore this major version` will close this PR and stop
Dependabot creating any more for this major version (unless you reopen
the PR or upgrade to it yourself)
- `@dependabot ignore this minor version` will close this PR and stop
Dependabot creating any more for this minor version (unless you reopen
the PR or upgrade to it yourself)
- `@dependabot ignore this dependency` will close this PR and stop
Dependabot creating any more for this dependency (unless you reopen the
PR or upgrade to it yourself)


</details>

Signed-off-by: dependabot[bot] <support@github.com>
Co-authored-by: dependabot[bot] <49699333+dependabot[bot]@users.noreply.github.com></details>