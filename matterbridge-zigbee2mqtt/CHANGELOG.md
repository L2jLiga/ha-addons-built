Changes in this Release

<details><summary>9568fc4 chore: bump matterbridge from 2.0.0 to 2.1.2 in /matterbridge-zigbee2mqtt (#104)</summary>
chore: bump matterbridge from 2.0.0 to 2.1.2 in /matterbridge-zigbee2mqtt (#104)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 2.0.0
to 2.1.2.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.2</h2>
<h3>Breaking Changes</h3>
<p>Starting from v. 2.0.0 Matterbridge is running only in mode edge (no
parameter needed and no badge in the frontend).</p>
<p>With this release v. 2.1.0, the legacy old api of matter.js have been
completely removed from Matterbridge and from all plugins.</p>
<p>For this reason there is no compatibility for old versions of the
plugins.</p>
<p>You need to update all plugins you use and Matterbridge in the same
moment.</p>
<p>I suggest to first update all plugins without restarting and then to
update Matterbridge so when it restarts, all versions will be the
latest.</p>
<p>Compatibility list:
matterbridge-shelly v. 1.1.5
matterbridge-zigbee2mqtt v. 2.4.4
matterbridge-somfy-tahoma v. 1.2.3
matterbridge-hass v. 0.0.8</p>
<h2>[2.1.2] - 2025-02-03</h2>
<h3>Added</h3>
<ul>
<li>[frotnend]: Add rss and heap to SystemInformation.</li>
<li>[memorydump]: Add cpu to memoryDump.</li>
<li>[memorydump]: Add memoryinterval to memoryDump.</li>
<li>[memorydump]: Add memorytimeout to memoryDump.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fixed update matterbridge.</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 2.1.1</h2>
<h3>Breaking Changes</h3>
<p>Starting from v. 2.0.0 Matterbridge is running only in mode edge (no
parameter needed and no badge in the frontend).</p>
<p>With this release v. 2.1.0, the legacy old api of matter.js have been
completely removed from Matterbridge and from all plugins.</p>
<p>For this reason there is no compatibility for old versions of the
plugins.</p>
<p>You need to update all plugins you use and Matterbridge in the same
moment.</p>
<p>I suggest to first update all plugins without restarting and then to
update Matterbridge so when it restarts, all versions will be the
latest.</p>
<p>Compatibility list:</p>
<!-- raw HTML omitted -->
</blockquote>
<p>... (truncated)</p>
</details>
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/blob/main/CHANGELOG.md">matterbridge's
changelog</a>.</em></p>
<blockquote>
<h2>[2.1.2] - 2025-02-03</h2>
<h3>Added</h3>
<ul>
<li>[frotnend]: Add rss and heap to SystemInformation.</li>
<li>[memorydump]: Add cpu to memoryDump.</li>
<li>[memorydump]: Add memoryinterval to memoryDump.</li>
<li>[memorydump]: Add memorytimeout to memoryDump.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fixed update matterbridge.</li>
</ul>
<!-- raw HTML omitted -->
<h2>[2.1.1] - 2025-02-02</h2>
<h3>Fixed</h3>
<ul>
<li>[matter.js]: Fix close server nodes.</li>
</ul>
<!-- raw HTML omitted -->
<h2>[2.1.0] - 2025-02-02</h2>
<h3>Added</h3>
<ul>
<li>[matterbridge]: Add MatterbridgeModeSelectServer.</li>
<li>[matterbridge]: Add MatterbridgeSwitchServer.</li>
<li>[frontend]: Add api/advertise to turn on matter advertising in
bridge mode.</li>
<li>[frontend]: Frontend v.2.4.0.</li>
<li>[matterbridge]: Added deep memory scan details.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Removed legacy imports.</li>
<li>[package]: Update dependencies.</li>
<li>[package]: Update matter.js to 0.12.0.</li>
<li>[package]: Update matter.js to 0.12.1.</li>
<li>[package]: Update matter.js to 0.12.2.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/858dba64b09961915ea91183d1ce643168b828c6"><code>858dba6</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/217">#217</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7de4918e0d0d77c11c8af292a12e98225b40b335"><code>7de4918</code></a>
Release 2.1.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/833a3ffea3ea1f0953fdba7c20f72606158b1da7"><code>833a3ff</code></a>
Jest tests</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/498ebb1ab50a30a244db3e6b35fabd23f33bd003"><code>498ebb1</code></a>
Jest tests</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/769f76fb9b2fe1d4f7f6729721b66488c4e7b49d"><code>769f76f</code></a>
Jest tests</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/cad83f0d3fa288050c0f66bfe47e862376beca9a"><code>cad83f0</code></a>
Jest tests</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c84cefc701b311d47080f8a03f0ddc8a086deee2"><code>c84cefc</code></a>
Jest tests</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b2582b29a8f946eee3e024d6c30cd29ad69c080c"><code>b2582b2</code></a>
Dev 2.1.2-dev.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/299f76dde324fb0533273699cbc6f199c902baa9"><code>299f76d</code></a>
Jest test pluginManager</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/608f084f3ec41f1dcee2ea74a218b515587a5a5e"><code>608f084</code></a>
Add memoryinterval and memorytimeout to memoryDump</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/2.0.0...2.1.2">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=2.0.0&new-version=2.1.2)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>4096c0c chore: bump matterbridge-zigbee2mqtt from 2.4.3 to 2.4.4 in /matterbridge-zigbee2mqtt (#105)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.4.3 to 2.4.4 in /matterbridge-zigbee2mqtt (#105)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.4.3 to 2.4.4.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.4.4</h2>
<h2>[2.4.4] - 2025-02-02</h2>
<h3>Changed</h3>
<ul>
<li>[plugin]: Requires Matterbridge 2.1.0.</li>
<li>[package]: Updated package.</li>
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
<h2>[2.4.4] - 2025-02-02</h2>
<h3>Changed</h3>
<ul>
<li>[plugin]: Requires Matterbridge 2.1.0.</li>
<li>[package]: Updated package.</li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/146ac9a9c6272bd1c471fad0efe208edec6f8fed"><code>146ac9a</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/96">#96</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/54449db2f360dcc8fb4b083eb58d3dd743931054"><code>54449db</code></a>
Release 2.4.4</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/e93135c2e009939e9798425edc47394494c9a3e8"><code>e93135c</code></a>
Release 2.4.4</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/00437a6f1f589dc5ff3a3a36a6aa170955ca1c6d"><code>00437a6</code></a>
Automator: update package</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/a3f9f7a5f67d5bd2c1972c67ebd7c3778b8b7f72"><code>a3f9f7a</code></a>
Automator: update package</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/7866392442ff3a71ab3f461cd24d626e6341fe3c"><code>7866392</code></a>
Automator: update package</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/1a9de6007ff40d33823d568766c373f199ba74ed"><code>1a9de60</code></a>
Automator: update package</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/fa89dd4408ee2f12114b503b919cf7630aee9dcf"><code>fa89dd4</code></a>
Automator: update package</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/b077f5f01ff6fd91ad8c4117d581935fcff3c8dc"><code>b077f5f</code></a>
Dev 2.4.4-dev.2</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/72741b6467fde4f8e8336d7e8f6106764a4c00c1"><code>72741b6</code></a>
Dev 2.4.4-dev.2</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.4.3...2.4.4">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.4.3&new-version=2.4.4)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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