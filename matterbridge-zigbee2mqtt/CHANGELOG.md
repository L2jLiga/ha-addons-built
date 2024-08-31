Changes in this Release

<details><summary>cff1ce9 chore: bump matterbridge from 1.5.1 to 1.5.2 in /matterbridge-zigbee2mqtt (#63)</summary>
chore: bump matterbridge from 1.5.1 to 1.5.2 in /matterbridge-zigbee2mqtt (#63)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.5.1
to 1.5.2.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.5.2</h2>
<h2>[1.5.2] - 2024-08-30</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Added a confirmation message for removing and disabling
plugins.</li>
<li>[matterbridge cli]: Added the parameter <code>-sudo</code> to force
the use of sudo when installing or updating a package (this is useful
when the internal logic is not working in your setup).</li>
<li>[matterbridge cli]: Added the parameter <code>-nosudo</code> to
force not using sudo when installing or updating a package (this is
useful when the internal logic is not working in your setup).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[spawn]: Modified the install or update function to add more info in
the log.</li>
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
<h2>[1.5.2] - 2024-08-30</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Added a confirmation message for removing and disabling
plugins.</li>
<li>[matterbridge cli]: Added the parameter <code>-sudo</code> to force
the use of sudo when installing or updating a package (this is useful
when the internal logic is not working in your setup).</li>
<li>[matterbridge cli]: Added the parameter <code>-nosudo</code> to
force not using sudo when installing or updating a package (this is
useful when the internal logic is not working in your setup).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[spawn]: Modified the install or update function to add more info in
the log.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f088173647e6cce3649f05673b16806c50c30744"><code>f088173</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/115">#115</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d77cd3dab42a4c6b81a95813b11b3d214309e4ed"><code>d77cd3d</code></a>
Release 1.5.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3f6c11115d764082d791ffa4873accc805b4ab55"><code>3f6c111</code></a>
Release 1.5.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a2c4fd7c50ccb0a817908d073e6ed83c75628eb0"><code>a2c4fd7</code></a>
1.5.2-beta2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/9d271a4a085222f8d64a031fe048f6e1f2b9666f"><code>9d271a4</code></a>
1.5.2-beta2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e2f850bd21b473e00c3669b150881b0ba88c9a23"><code>e2f850b</code></a>
1.5.2-beta2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/447dffe5e413d005818349c4d3ff491381085ce7"><code>447dffe</code></a>
1.5.2-beta2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c753a03455964730f9317653b4807106c2506ca1"><code>c753a03</code></a>
1.5.2-beta2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/eb8553ae160f833b0ab5e4c9e668df66ac1d6d94"><code>eb8553a</code></a>
1.5.2-beta2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e8f5f0660690b336687eb767692e09dd2f1d30c4"><code>e8f5f06</code></a>
1.5.2-beta2</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.5.1...1.5.2">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.5.1&new-version=1.5.2)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>0a68488 chore: bump matterbridge-zigbee2mqtt from 2.1.13 to 2.1.14 in /matterbridge-zigbee2mqtt (#62)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.1.13 to 2.1.14 in /matterbridge-zigbee2mqtt (#62)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.1.13 to 2.1.14.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.14</h2>
<h2>[2.1.14] - 2024-08-29</h2>
<h3>Added</h3>
<ul>
<li>[config]: Added parameter postfixHostname (default true). If you
change it, the controllers will remove and recreate all the devices! (<a
href="https://github.com/L2jLiga">https://github.com/L2jLiga</a>)</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Updated dependencies.</li>
<li>[package]: Updated imports.</li>
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
<h2>[2.1.14] - 2024-08-29</h2>
<h3>Added</h3>
<ul>
<li>[config]: Added parameter postfixHostname (default true). If you
change it, the controllers will remove and recreate all the devices! (<a
href="https://github.com/L2jLiga">https://github.com/L2jLiga</a>)</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Updated dependencies.</li>
<li>[package]: Updated imports.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/85c2898940107b35805fa8bb752abadb163e8cac"><code>85c2898</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/64">#64</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/0cb220332d456320961a341d979fd596a0b91181"><code>0cb2203</code></a>
Release 2.1.14</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/53697e96b2f2755d5eae6a7b054122caca48d96c"><code>53697e9</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/56">#56</a>
from L2jLiga/feature/hostname-configuration</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/4917f8b948a4f9bcb497c4b6510882d612a042cd"><code>4917f8b</code></a>
Update dependencies</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/be32a50659467d3e5418df2e847ca55115d0d1cb"><code>be32a50</code></a>
Update cluster imports</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/fa1e9084ae601072fd497c1ba185067e2347eefc"><code>fa1e908</code></a>
feat: added option to specify unique postfix</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.1.13...2.1.14">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.1.13&new-version=2.1.14)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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