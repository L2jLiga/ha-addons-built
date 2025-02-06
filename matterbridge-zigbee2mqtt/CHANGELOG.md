Changes in this Release

<details><summary>de1142a chore: bump matterbridge from 2.1.2 to 2.1.3 in /matterbridge-zigbee2mqtt (#107)</summary>
chore: bump matterbridge from 2.1.2 to 2.1.3 in /matterbridge-zigbee2mqtt (#107)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 2.1.2
to 2.1.3.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.3</h2>
<h3>Breaking Changes</h3>
<p>Starting from v. 2.0.0, Matterbridge is running only in mode edge (no
parameter needed and no badge in the frontend).</p>
<p>Starting from v. 2.1.0, the legacy old api of matter.js have been
completely removed from Matterbridge and from all plugins.</p>
<p>For this reason there is no compatibility with the old versions of
the plugins.</p>
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
<h2>[2.1.3] - 2025-02-04</h2>
<h3>Added</h3>
<ul>
<li>[matter.js]: Added temporary solution to prevent serverNode.close()
not returning.</li>
</ul>
<h3>Changed</h3>
<ul>
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
<h2>[2.1.3] - 2025-02-04</h2>
<h3>Added</h3>
<ul>
<li>[matter.js]: Added temporary solution to prevent serverNode.close()
not returning.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/bac12da59a4c76ff3c14a30531a8d3e4a8030d61"><code>bac12da</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/218">#218</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/50ffe411ff5a923f8d4b6f9ae02c24de0cc77054"><code>50ffe41</code></a>
Release 2.1.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b5486252d23053e5f375c5718a80c0c360f80baa"><code>b548625</code></a>
Moved frontend.stop() after serverNode.close()</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/0cc1818dd64773c4e5d1b31c5e7d6c49fdf76399"><code>0cc1818</code></a>
Dev 2.1.3-dev.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e4ffd0ff43172355271ffc2786d1c96a38052c73"><code>e4ffd0f</code></a>
Implement timeout for server node closure to prevent hanging
operations</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c845c5d569c6f88c2634b8dd692197f3bc4d2548"><code>c845c5d</code></a>
Update CHANGELOG.md for version 2.1.0: clarify removal of legacy API and
enha...</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge/compare/2.1.2...2.1.3">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=2.1.2&new-version=2.1.3)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>2a22946 chore: bump matterbridge-zigbee2mqtt from 2.4.4 to 2.4.5 in /matterbridge-zigbee2mqtt (#106)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.4.4 to 2.4.5 in /matterbridge-zigbee2mqtt (#106)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.4.4 to 2.4.5.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.4.5</h2>
<h2>[2.4.5] - 2025-02-05</h2>
<h3>Added</h3>
<ul>
<li>[thermostat]: Added fan_only mode (tested by <a
href="https://github.com/robvanoostenrijk">https://github.com/robvanoostenrijk</a>).
No controllers seem to support this mode in UI right now.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Updated dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[thermostat]: Fix thermostat bug (thanks <a
href="https://github.com/robvanoostenrijk">https://github.com/robvanoostenrijk</a>).</li>
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
<h2>[2.4.5] - 2025-02-05</h2>
<h3>Added</h3>
<ul>
<li>[thermostat]: Added fan_only mode (tested by <a
href="https://github.com/robvanoostenrijk">https://github.com/robvanoostenrijk</a>).
No controllers seem to support this mode in UI right now.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Updated dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[thermostat]: Fix thermostat bug (thanks <a
href="https://github.com/robvanoostenrijk">https://github.com/robvanoostenrijk</a>).</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/a12987871650176e9303b1b280efedc1a7fe98f7"><code>a129878</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/99">#99</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/4b9dc775c9317c93ffd4c89e4cf23005f4568eb2"><code>4b9dc77</code></a>
Release 2.4.5</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/6f3ceafef9eae6d45aceba8e2c86e671b34d2cf4"><code>6f3ceaf</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/98">#98</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/1865b5c1866b257d0795a45f7090276456373b66"><code>1865b5c</code></a>
Release 2.4.5</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/46cb48b49ab276eb30fbf8678d5bb7cbfacf6ea4"><code>46cb48b</code></a>
Add fan_only mode to thermostat and update version to 2.4.5-dev.4</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/1aa71261be8ea8ac9daed8d9c179d00bf08b3dba"><code>1aa7126</code></a>
Changed validateDeviceWhiteBlackList in validateDevice</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/44ab5073643879d96ad6d3b0a2c0c67f306cabe3"><code>44ab507</code></a>
Dev 2.4.5-dev.2</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/a58ab5c61432fe0fdbbfcb0aab392d04789f0ac0"><code>a58ab5c</code></a>
Fix thermostat current_heating_setpoint</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.4.4...2.4.5">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.4.4&new-version=2.4.5)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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