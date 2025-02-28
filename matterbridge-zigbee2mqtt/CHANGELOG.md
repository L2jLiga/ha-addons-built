Changes in this Release

<details><summary>c8ef466 chore: bump matterbridge from 2.1.5 to 2.2.0 in /matterbridge-zigbee2mqtt (#111)</summary>
chore: bump matterbridge from 2.1.5 to 2.2.0 in /matterbridge-zigbee2mqtt (#111)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 2.1.5
to 2.2.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.2.0</h2>
<h2>[2.2.0] - 2025-02-27</h2>
<h3>Added</h3>
<ul>
<li>[docker]: Added health check directly in the docker image. No need
to change configuration of docker compose.</li>
<li>[platform]: Saving in the storage the selects for faster loading of
plugins.</li>
<li>[icon]: Added matterbridge svg icon (thanks: <a
href="https://github.com/robvanoostenrijk">https://github.com/robvanoostenrijk</a>
<a
href="https://github.com/stuntguy3000">https://github.com/stuntguy3000</a>).</li>
<li>[pluginManager]: Refactor PluginManager to optimize memory and load
time.</li>
<li>[frontend]: Frontend v.2.4.6. Please refresh the frontend page after
the update.</li>
<li>[frontend]: Added processUptime to SystemInfo.</li>
<li>[frontend]: Added Share fabrics and Stop sharing to the menu. This
allows to pair other controllers without the need to share from the
first controller.</li>
<li>[frontend]: Added subscriptions to QRDiv.</li>
<li>[frontend]: Added autoScroll option for the logs. Default is
enabled.</li>
<li>[utils]: Optimized memory and loading time.</li>
<li>[shelly]: Added all shelly api to be used when matterbridge is
running on the shelly matterbridge board.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter.js to 0.12.4</li>
<li>[matterbridge]: The check for available updates now runs at restart
and each 24 hours after.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Check endpoint state in /api/devices.</li>
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
<h2>[2.2.0] - 2025-02-27</h2>
<h3>Added</h3>
<ul>
<li>[docker]: Added health check directly in the docker image. No need
to change configuration of docker compose.</li>
<li>[platform]: Saving in the storage the selects for faster loading of
plugins.</li>
<li>[icon]: Added matterbridge svg icon (thanks: <a
href="https://github.com/robvanoostenrijk">https://github.com/robvanoostenrijk</a>
<a
href="https://github.com/stuntguy3000">https://github.com/stuntguy3000</a>).</li>
<li>[pluginManager]: Refactor PluginManager to optimize memory and load
time.</li>
<li>[frontend]: Frontend v.2.4.6. Please refresh the frontend page after
the update.</li>
<li>[frontend]: Added processUptime to SystemInfo.</li>
<li>[frontend]: Added Share fabrics and Stop sharing to the menu. This
allows to pair other controllers without the need to share from the
first controller.</li>
<li>[frontend]: Added subscriptions to QRDiv.</li>
<li>[frontend]: Added autoScroll option for the logs. Default is
enabled.</li>
<li>[utils]: Optimized memory and loading time.</li>
<li>[shelly]: Added all shelly api to be used when matterbridge is
running on the shelly matterbridge board.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter.js to 0.12.4</li>
<li>[matterbridge]: The check for available updates now runs at restart
and each 24 hours after.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Check endpoint state in /api/devices.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/42ccb9405390664d79da8945e8d8d832864119f0"><code>42ccb94</code></a>
Release 2.2.0 (<a
href="https://redirect.github.com/Luligu/matterbridge/issues/233">#233</a>)</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge/compare/2.1.5...2.2.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=2.1.5&new-version=2.2.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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