Changes in this Release

<details><summary>03d81b1 chore: bump matterbridge from 1.7.0 to 1.7.1 in /matterbridge-zigbee2mqtt (#96)</summary>
chore: bump matterbridge from 1.7.0 to 1.7.1 in /matterbridge-zigbee2mqtt (#96)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.7.0
to 1.7.1.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.7.1</h2>
<h3>Breaking Changes</h3>
<p>Matterbridge edge is now released. The default mode is still the
normal mode to allow the storage conversion. See <a
href="https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md">https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md</a>
to manually switch to edge mode after the conversion is done.</p>
<p>The frontend has a new dark and light mode. The dark mode is now the
default mode.
It is possible to change the mode (Classic, Dark or Light) in Settings,
Matterbridge settings.</p>
<h2>[1.7.1] - 2025-01-07</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added selectDevice to get the device names from a list
in the config editor.</li>
<li>[websocket]: Added api /api/select.</li>
<li>[frontend]: Added configUrl to Devices page.</li>
<li>[frontend]: Added config button to Devices page.</li>
<li>[frontend]: Added id and deviceTypes to Devices page.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[websocket]: Added params to /api/clusters.</li>
<li>[frontend]: Frontend v.2.3.3</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fixed WebSocketProvider online.</li>
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
<h2>[1.7.1] - 2025-01-07</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added selectDevice to get the device names from a list
in the config editor.</li>
<li>[websocket]: Added api /api/select.</li>
<li>[frontend]: Added configUrl to Devices page.</li>
<li>[frontend]: Added config button to Devices page.</li>
<li>[frontend]: Added id and deviceTypes to Devices page.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[websocket]: Added params to /api/clusters.</li>
<li>[frontend]: Frontend v.2.3.3</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fixed WebSocketProvider online.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/db225a5771c75f77d97f24bad2f5ef7ea5dfc6d3"><code>db225a5</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/201">#201</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/67f93a882230f1bd2cc03e7e606b232e47683e0a"><code>67f93a8</code></a>
Frontend 2.3.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/87936fb6e2d07fefc3e41beed5d96cbae4851b48"><code>87936fb</code></a>
Fix table z-index</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/263790b63fe68a705b17de524063dfbab94f0216"><code>263790b</code></a>
Update CHANGELOG.md to include new config button for Devices page</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/47d55bbfd4673c2cdc9f8ca380d7db5c5fe32eeb"><code>47d55bb</code></a>
Add config button to Devices table</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/74ab22f1627957784d75d656cceb3aec9092e5b3"><code>74ab22f</code></a>
Add debug flag to App.js</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/518857eb0ee6dd21f585b6e9d0fe48997236bd1c"><code>518857e</code></a>
Update CHANGELOG.md to include new configUrl, id, and deviceTypes for
Devices...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/6e422327674ebacb4a20545654402dedaea63d00"><code>6e42232</code></a>
Add attributeLocalValue to ApiClusters interface for enhanced data
handling</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e8931df2015eb6fda2675d6f25cd8575dc2d27a7"><code>e8931df</code></a>
Add local attribute value handling in wsMessageHandler for improved
logging</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/5883e126f88c09a8c541ed837e53409b26bf749e"><code>5883e12</code></a>
Bump frontend version to 2.3.2, enhance Settings and Header components
with o...</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.7.0...1.7.1">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.7.0&new-version=1.7.1)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>50d95f7 chore: bump matterbridge-zigbee2mqtt from 2.3.2 to 2.4.0 in /matterbridge-zigbee2mqtt (#97)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.3.2 to 2.4.0 in /matterbridge-zigbee2mqtt (#97)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.3.2 to 2.4.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.4.0</h2>
<h2>[2.4.0] - 2025-01-08</h2>
<h3>Added</h3>
<ul>
<li>[selectDevice]: Added selectDevice to get the device names from a
list in the config editor.</li>
<li>[configUrl]: Added configUrl to get a link to the zigbee2mqtt
frontend from the Matterbridge frontend Devices page.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[illuminace_lux]: Follow removal of illuminace_lux <a
href="https://redirect.github.com/Koenkk/zigbee-herdsman-converters/pull/8304">Koenkk/zigbee-herdsman-converters#8304</a></li>
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
<h2>[2.4.0] - 2025-01-08</h2>
<h3>Added</h3>
<ul>
<li>[selectDevice]: Added selectDevice to get the device names from a
list in the config editor.</li>
<li>[configUrl]: Added configUrl to get a link to the zigbee2mqtt
frontend from the Matterbridge frontend Devices page.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[illuminace_lux]: Follow removal of illuminace_lux <a
href="https://redirect.github.com/Koenkk/zigbee-herdsman-converters/pull/8304">Koenkk/zigbee-herdsman-converters#8304</a></li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/bd6c1aaef35e7ddce742ca00af0ec09e6baac229"><code>bd6c1aa</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/90">#90</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/1c7d2ee34d9c2042f65b82fecf0379d8d97c0f01"><code>1c7d2ee</code></a>
Release 2.4.0</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c53664c2a8d98c00c4d3dd573d8502415c12574c"><code>c53664c</code></a>
Add configUrl to devices and groups for frontend links in CHANGELOG</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/92d7c2fadb33aff1bdce0f27f2ca6e5d3b45123a"><code>92d7c2f</code></a>
Release 2.4.0</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.3.2...2.4.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.3.2&new-version=2.4.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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