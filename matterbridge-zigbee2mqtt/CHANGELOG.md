Changes in this Release

<details><summary>dbdd4ef chore: bump matterbridge from 1.5.10 to 1.6.0 in /matterbridge-zigbee2mqtt (#78)</summary>
chore: bump matterbridge from 1.5.10 to 1.6.0 in /matterbridge-zigbee2mqtt (#78)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.5.10
to 1.6.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.6.0</h2>
<h2>[1.6.0] - 2024-10-28</h2>
<h3>Added</h3>
<ul>
<li>[matterbridge]: Added WebSocket for the Matetrbridge cockpit
dashboard (Shelly gateway).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[discord]: Discord group link: <a
href="https://discord.gg/QX58CDe6hd">https://discord.gg/QX58CDe6hd</a>.</li>
<li>[matterbridge]: Completed phase 1 of transition to edge (matter.js
new API).</li>
<li>[matterbridgeDevice]: Refactor Thermostat cluster method to accept
minHeatSetpointLimit, maxHeatSetpointLimit, minCoolSetpointLimit and
maxCoolSetpointLimit.</li>
<li>[config]: The plugins config is rewritten only after onStart and no
more after onConfigure (after the plugin starts is possible to change
the plugins config and it will not be rewritten after the plugin
configuration).</li>
<li>[matterbridgeDevice]: Removed deprecated methods of ColorControl
cluster.</li>
<li>[package]: Removed EveHistory (it will be used only by single
plugins).</li>
<li>[package]: Update dependencies.</li>
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
<h2>[1.6.0] - 2024-10-28</h2>
<h3>Added</h3>
<ul>
<li>[matterbridge]: Added WebSocket for the Matetrbridge cockpit
dashboard (Shelly gateway).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[discord]: Discord group link: <a
href="https://discord.gg/QX58CDe6hd">https://discord.gg/QX58CDe6hd</a>.</li>
<li>[matterbridge]: Completed phase 1 of transition to edge (matter.js
new API).</li>
<li>[matterbridgeDevice]: Refactor Thermostat cluster method to accept
minHeatSetpointLimit, maxHeatSetpointLimit, minCoolSetpointLimit and
maxCoolSetpointLimit.</li>
<li>[config]: The plugins config is rewritten only after onStart and no
more after onConfigure (after the plugin starts is possible to change
the plugins config and it will not be rewritten after the plugin
configuration).</li>
<li>[matterbridgeDevice]: Removed deprecated methods of ColorControl
cluster.</li>
<li>[package]: Removed EveHistory (it will be used only by single
plugins).</li>
<li>[package]: Update dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c005936d73c37a7a840491b2f4d19df138807e9b"><code>c005936</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/152">#152</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/925dd3678ae2826a4f757e0c1fd666ce68bb45c0"><code>925dd36</code></a>
Release 1.6.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/cb8762c80308cbaa37b5e7393c8ca5eac6012974"><code>cb8762c</code></a>
Dev 1.6.0-dev.17</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b01f916c2b2b670bef1297a472e7713db6c6a222"><code>b01f916</code></a>
Dev 1.6.0-dev.17</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/cc7e42d3af696632b81f568eb406ef94401e2961"><code>cc7e42d</code></a>
Dev 1.6.0-dev.16</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f040119c8d1faafe523fc4470d9c4534c66b2e89"><code>f040119</code></a>
Dev 1.6.0-dev.16</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/ef23e7985c20cde51fdbe8d897b35bc5c01d5da2"><code>ef23e79</code></a>
Dev 1.6.0-dev.16</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3ddc53d77078f817b4a7227d856c9029e83fc223"><code>3ddc53d</code></a>
Dev 1.6.0-dev.15</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c620083e2244c822a99634c1d328f41af836b1f0"><code>c620083</code></a>
Websocket api</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3e83119a4df7b944c00e2e238413506f14ce86a1"><code>3e83119</code></a>
Dev 1.6.0-dev.14</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.5.10...1.6.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.5.10&new-version=1.6.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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