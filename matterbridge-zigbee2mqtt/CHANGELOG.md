Changes in this Release

<details><summary>5a8c878 chore: bump matterbridge-zigbee2mqtt from 2.4.2 to 2.4.3 in /matterbridge-zigbee2mqtt (#100)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.4.2 to 2.4.3 in /matterbridge-zigbee2mqtt (#100)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.4.2 to 2.4.3.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.4.3</h2>
<h2>[2.4.3] - 2025-01-20</h2>
<h3>Fixed</h3>
<ul>
<li>[plugin]: Requires Matterbridge 1.7.3.</li>
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
<h2>[2.4.3] - 2025-01-20</h2>
<h3>Fixed</h3>
<ul>
<li>[plugin]: Requires Matterbridge 1.7.3.</li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/3d9b9cbbf3fd8785113e738d71fb2a4d3ca78e11"><code>3d9b9cb</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/94">#94</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/fa593b3fce1bcccf6d64a3ed6b239b9fc021879e"><code>fa593b3</code></a>
Release 2.4.3</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.4.2...2.4.3">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.4.2&new-version=2.4.3)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>bc214e7 chore: bump matterbridge from 1.7.3 to 2.0.0 in /matterbridge-zigbee2mqtt (#101)</summary>
chore: bump matterbridge from 1.7.3 to 2.0.0 in /matterbridge-zigbee2mqtt (#101)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.7.3
to 2.0.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.0.0</h2>
<h3>Breaking Changes</h3>
<p>Starting from v. 2.0.0 Matterbridge is running only in mode edge (no
parameter needed).
The legacy old api have been removed.</p>
<p>The frontend has a new dark and light mode. The dark mode is now the
default mode.
It is possible to change the mode (Classic, Dark or Light) in Settings,
Matterbridge settings.</p>
<h2>[2.0.0] - 2025-01-20</h2>
<h3>Added</h3>
<ul>
<li>[behavior]: Added MatterbridgeValveConfigurationAndControlServer
behavior with open close command.</li>
<li>[matterbridge]: Added /memory endpoint for debugging memory
use.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[legacy]: Removed MatterbridgeDevice and MatterbridgeEdge
classes.</li>
<li>[factoryreset]: Now it deletes also the backup files and backup
directories.</li>
<li>[mattebridge]: Restyled the Matterbridge class and created the
Frontend class that manages the frontend express and websocket api
calls.</li>
<li>[frontend]: Frontend v.2.3.12.</li>
<li>[iconView]: Improved render for energySensor adding voltage, current
and power.</li>
<li>[iconView]: Improved render for PowerSource adding battery
voltage.</li>
<li>[jest]: Refactor all tests for edge.</li>
<li>[frontend]: WebSocketProvider added a startTimeout of 300 sec. to
start ping.</li>
<li>[frontend]: WebSocketProvider changed pingIntervalSeconds to 60 sec.
and offlineTimeoutSeconds to 50 sec.</li>
<li>[frontend]: Search on select is no more case sensitive.</li>
<li>[matterbridge]: Deferred memory intensive tasks after
initialization.</li>
<li>[package]: Optimized all imports from matter.js.</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[sessions]: Fixed the case when Active session was not reporting
correctly.</li>
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
<h2>[2.0.0] - 2025-01-20</h2>
<h3>Added</h3>
<ul>
<li>[behavior]: Added MatterbridgeValveConfigurationAndControlServer
behavior with open close command.</li>
<li>[matterbridge]: Added /memory endpoint for debugging memory
use.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[legacy]: Removed MatterbridgeDevice and MatterbridgeEdge
classes.</li>
<li>[factoryreset]: Now it deletes also the backup files and backup
directories.</li>
<li>[mattebridge]: Restyled the Matterbridge class and created the
Frontend class that manages the frontend express and websocket api
calls.</li>
<li>[frontend]: Frontend v.2.3.12.</li>
<li>[iconView]: Improved render for energySensor adding voltage, current
and power.</li>
<li>[iconView]: Improved render for PowerSource adding battery
voltage.</li>
<li>[jest]: Refactor all tests for edge.</li>
<li>[frontend]: WebSocketProvider added a startTimeout of 300 sec. to
start ping.</li>
<li>[frontend]: WebSocketProvider changed pingIntervalSeconds to 60 sec.
and offlineTimeoutSeconds to 50 sec.</li>
<li>[frontend]: Search on select is no more case sensitive.</li>
<li>[matterbridge]: Deferred memory intensive tasks after
initialization.</li>
<li>[package]: Optimized all imports from matter.js.</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[sessions]: Fixed the case when Active session was not reporting
correctly.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a1e3167ff5531d139d26533ac5b1f84de1f3770b"><code>a1e3167</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/212">#212</a>
from Luligu/edge</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d6852276cd774b2f4a3fcdc3d1867aac3650ddef"><code>d685227</code></a>
Release 2.0.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e9e7088fece35e790d090df3a7e67448eadd4d32"><code>e9e7088</code></a>
Release 2.0.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/92c8f875af40125b20973b28d720eb2f0495875d"><code>92c8f87</code></a>
Bump version to 2.0.0-edge.6 and update changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/96d2a8b7e6780f76c3653a5c6310aabb9bd03fd5"><code>96d2a8b</code></a>
Bump version to 2.0.0-edge.5 and update changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/2d73263c90bfccbd30758b9e540f6982ec79f408"><code>2d73263</code></a>
Bump version to 2.0.0-edge.4 and update changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b588a72716fd91d7f6d8b5ca8f9686098a8b36d2"><code>b588a72</code></a>
Bump version to 2.0.0-edge.3 and update changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/83e3ec7ccb1e4875bd2c2c3180911a3cf728bbd1"><code>83e3ec7</code></a>
Bump version to 2.0.0-edge.3 and update changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/921b32cae433864a4d5dcb25787f982401528f7e"><code>921b32c</code></a>
Removed plugin.connected</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a69b8119365250bff9e3a712dbcb9f412f993de5"><code>a69b811</code></a>
Removed matterbridgeConnected</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.7.3...2.0.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.7.3&new-version=2.0.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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