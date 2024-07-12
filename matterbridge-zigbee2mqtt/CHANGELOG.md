Changes in this Release

<details><summary>934f55a chore: bump matterbridge from 1.3.12 to 1.3.13 in /matterbridge-zigbee2mqtt (#44)</summary>
chore: bump matterbridge from 1.3.12 to 1.3.13 in /matterbridge-zigbee2mqtt (#44)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.12
to 1.3.13.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.13</h2>
<h2>[1.3.13] - 2024-07-11</h2>
<h3>Added</h3>
<h3>Changed</h3>
<ul>
<li>[frontend]: The Logs window in the Home page has the same filter as
the Logs page.</li>
<li>[matterbridge]: The plugins debug is now indipendent from
matterbridge debug and matter.js log level. It can be set from the
plugin config.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fix Home page for mobile (the page doesn't
&quot;jump&quot; anymore with touchscreens).</li>
<li>[matterbridge]: Fixed npm ignore for exports.</li>
<li>[matterbridge]: Fixed load plugin when the don't have author and
description.</li>
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
<h2>[1.3.13] - 2024-07-11</h2>
<h3>Added</h3>
<h3>Changed</h3>
<ul>
<li>[frontend]: The Logs window in the Home page has the same filter as
the Logs page.</li>
<li>[matterbridge]: The plugins debug is now indipendent from
matterbridge debug and matter.js log level. It can be set from the
plugin config.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[frontend]: Fix Home page for mobile (the page doesn't
&quot;jump&quot; anymore with touchscreens).</li>
<li>[matterbridge]: Fixed npm ignore for exports.</li>
<li>[matterbridge]: Fixed load plugin when the don't have author and
description.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/eb520d1d9149a9fbfab1b264afc11e9cd746c961"><code>eb520d1</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/86">#86</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/437ac437e21a0a6e439a4daa740fa356d8417ca9"><code>437ac43</code></a>
Release 1.3.13</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1b8e9177c35b72434ba895554fca25369ad8c0b9"><code>1b8e917</code></a>
Release 1.3.13</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7945341e9be1c999fb2278a99ed8d2329376a49c"><code>7945341</code></a>
Fixed load plugin when the don't have author and description</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f2169e0ee331b838bf954d03cc5cf1e6f0f9e945"><code>f2169e0</code></a>
Fixed load plugin when the don't have author</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e9b5a46f2822a51aa43241ff253952f7d582b671"><code>e9b5a46</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/85">#85</a>
from dlo9/patch-1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/270d6b795981f115a4ef913c01e3b54666780aee"><code>270d6b7</code></a>
Changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/336dd3affab8da23ce04d857caaf2a60b7e17ff1"><code>336dd3a</code></a>
Fixed npm ignore for exports</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8f389d83ed99238ac9bb8a70fdf6fa96e3c0e990"><code>8f389d8</code></a>
Release 1.3.13</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3860f359e0b2bed2fc6d7e900428be18865134ed"><code>3860f35</code></a>
Changed filter logger</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.12...1.3.13">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.12&new-version=1.3.13)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>23cd293 chore: bump matterbridge-zigbee2mqtt from 2.1.6 to 2.1.7 in /matterbridge-zigbee2mqtt (#45)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.1.6 to 2.1.7 in /matterbridge-zigbee2mqtt (#45)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.1.6 to 2.1.7.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.7</h2>
<h2>[2.1.7] - 2024-07-11</h2>
<h3>Fixed</h3>
<ul>
<li>[z2m]: Fixed trigger when the endpoint is undefined.</li>
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
<h2>[2.1.7] - 2024-07-11</h2>
<h3>Fixed</h3>
<ul>
<li>[z2m]: Fixed trigger when the endpoint is undefined.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/fca046a26dd5f4b9e8eac95a69ac234b7a5ed84f"><code>fca046a</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/45">#45</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/a943c8973b7ab0f36e635eb167364e5831e804dd"><code>a943c89</code></a>
Release 2.1.7</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/542c41a7fdebf9f42579f952f3890241d75b82d2"><code>542c41a</code></a>
Fixed trigger when the endpoint is undefined</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/4bc0daa5d519e089882bc6d276d3613f15079cfe"><code>4bc0daa</code></a>
Fix action when the enpoint is undefined</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.1.6...2.1.7">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.1.6&new-version=2.1.7)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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