Changes in this Release

<details><summary>66d2c68 chore: bump matterbridge from 1.6.7 to 1.7.0 in /matterbridge-zigbee2mqtt (#95)</summary>
chore: bump matterbridge from 1.6.7 to 1.7.0 in /matterbridge-zigbee2mqtt (#95)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.6.7
to 1.7.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.7.0</h2>
<h3>Breaking Changes</h3>
<p>Matterbridge edge is now released. The default mode is still the
normal mode to allow the storage conversion. See <a
href="https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md">https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md</a>
to manually switch to edge mode after the conversion is done.</p>
<p>The frontend has a new dark and light mode. The dark mode is now the
default mode.
It is possible to change the mode (Classic, Dark or Light) in Settings,
Matterbridge settings.</p>
<h2>[1.7.0] - 2025-01-04</h2>
<h3>Added</h3>
<ul>
<li>[edge]: Added guide <a
href="https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md">https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md</a>.</li>
<li>[storage]: Added conversion from old matter storage to the new api
format with fabrics, resumptionRecords, network, commissioning,
operationalCredentials, acl and parts number. The conversion is
triggered every time you shutdown or restart matterbridge till the new
storage has been used with matterbridge edge.</li>
<li>[storage]: Added conversion for child endpoint numbers.</li>
<li>[storage]: Added conversion for childbridge mode.</li>
<li>[package]: Update README.md and README-SERVICE.md to include
instructions for using SSL on port 443.</li>
<li>[platform]: Added checkEndpointNumbers() to detect endpoint numbers
changes.</li>
<li>[frontend]: Frontend v.2.3.0</li>
<li>[frontend]: Added dark and light mode to the frontend. Dark mode is
now the default mode. It is possible to change the mode in Settings,
Matterbridge settings.</li>
<li>[frontend]: Custom rfjsreact-jsonschema-form for the config
editor.</li>
<li>[frontend]: Added columns configuration to Devices.</li>
<li>[frontend]: Added clear logs button in Logs.</li>
<li>[unregister]: Added unregister for Matterbridge edge.</li>
<li>[reset]: Added reset for Matterbridge edge.</li>
<li>[factoryreset]: Added factoryreset for Matterbridge edge.</li>
<li>[websocket]: Added /api/clusters and removed all fetch calls from
frontend.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[edge]: Fixes to edge mode.</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fixed device/cluster api that was not working in
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
<h2>[1.7.0] - 2025-01-03</h2>
<h3>Added</h3>
<ul>
<li>[edge]: Added guide <a
href="https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md">https://github.com/Luligu/matterbridge/blob/dev/README-EDGE.md</a>.</li>
<li>[storage]: Added conversion from old matter storage to the new api
format with fabrics, resumptionRecords, network, commissioning,
operationalCredentials, acl and parts number. The conversion is
triggered every time you shutdown or restart matterbridge till the new
storage has been used with matterbridge edge.</li>
<li>[storage]: Added conversion for child endpoint numbers.</li>
<li>[storage]: Added conversion for childbridge mode.</li>
<li>[package]: Update README.md and README-SERVICE.md to include
instructions for using SSL on port 443.</li>
<li>[platform]: Added checkEndpointNumbers() to detect endpoint numbers
changes.</li>
<li>[frontend]: Frontend v.2.3.0</li>
<li>[frontend]: Added dark and light mode to the frontend. Dark mode is
now the default mode. It is possible to change the mode in Settings,
Matterbridge settings.</li>
<li>[frontend]: Custom rfjsreact-jsonschema-form for the config
editor.</li>
<li>[frontend]: Added columns configuration to Devices.</li>
<li>[frontend]: Added clear logs button in Logs.</li>
<li>[unregister]: Added unregister for Matterbridge edge.</li>
<li>[reset]: Added reset for Matterbridge edge.</li>
<li>[factoryreset]: Added factoryreset for Matterbridge edge.</li>
<li>[websocket]: Added /api/clusters and removed all fetch calls from
frontend.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[edge]: Fixes to edge mode.</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fixed device/cluster api that was not working in
Ingress.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/bce574ecb0e4f3c21337845decc92d323935a44d"><code>bce574e</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/198">#198</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/2ad82b4d94273e3644f5e114ba641d88895bce70"><code>2ad82b4</code></a>
Change Classic mode colors</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/bfa3267bfd3d1e4d07f4ce3d57702a042f7f0b2a"><code>bfa3267</code></a>
Refactor createMatterServer for edge</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/08c9d406cc8405af44cff0026b53bca6ee1df664"><code>08c9d40</code></a>
Release 1.7.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/150768b4645160b3826821be7e5be3bdd87b0f21"><code>150768b</code></a>
Release 1.7.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/5788eee3c70176ffd37f64462325af266e05211d"><code>5788eee</code></a>
Release 1.7.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/723f90eece0b2cfea50afe18f25176c3dc267554"><code>723f90e</code></a>
Frontend 2.2.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e5e18bd2fa313cac8d754fd392cca9ff23e1ea71"><code>e5e18bd</code></a>
Frontend 2.2.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/61dac1af42836373458c4c7be907e08c24abb9a4"><code>61dac1a</code></a>
Replace WebSocketComponent with WebSocketLogs for improved logging
functional...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e05d20e44c013011871adb15bcbf9d2f5d840481"><code>e05d20e</code></a>
Enhance WebSocketProvider to include REFRESH_NEEDED and RESTART_NEEDED
states</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.6.7...1.7.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.6.7&new-version=1.7.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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