Changes in this Release

<details><summary>6a8e8c5 chore: bump matterbridge from 1.3.8 to 1.3.9 in /matterbridge-zigbee2mqtt (#39)</summary>
chore: bump matterbridge from 1.3.8 to 1.3.9 in /matterbridge-zigbee2mqtt (#39)

[//]: # (dependabot-start)
⚠️  **Dependabot is rebasing this PR** ⚠️ 

Rebasing might not happen immediately, so don't worry if this takes some
time.

Note: if you make any changes to this PR yourself, they will take
precedence over the rebase.

---

[//]: # (dependabot-end)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.8
to 1.3.9.
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/blob/main/CHANGELOG.md">matterbridge's
changelog</a>.</em></p>
<blockquote>
<h2>[1.3.9] - 2024-07-02</h2>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed nodeLabel in childbridge mode</li>
<li>[matterbridge]: Fixed MeasurementClusters</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge/commits">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.8&new-version=1.3.9)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>cfd8a1b chore: bump matterbridge-zigbee2mqtt from 2.1.4 to 2.1.5 in /matterbridge-zigbee2mqtt (#38)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.1.4 to 2.1.5 in /matterbridge-zigbee2mqtt (#38)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.1.4 to 2.1.5.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.5</h2>
<h2>[2.1.5] - 2024-07-01</h2>
<h3>Changed</h3>
<ul>
<li>[z2m]: Added transition to ColorControl if the zigbee device
supports it and the controller sends it. You can disable this globally
adding transition to the featureBlackList or only for the single device
adding transition to the deviceFeatureBlackList. (Thanks Stefan
Schweiger).</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[zigbee]: Fixed WindowCovering.targetPositionLiftPercent100ths
update (Thanks Nitay Ben-Zvi).</li>
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
<h2>[2.1.5] - 2024-07-01</h2>
<h3>Changed</h3>
<ul>
<li>[z2m]: Added transition to ColorControl if the zigbee device
supports it and the controller sends it. You can disable this globally
adding transition to the featureBlackList or only for the single device
adding transition to the deviceFeatureBlackList. (Thanks Stefan
Schweiger).</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[zigbee]: Fixed WindowCovering.targetPositionLiftPercent100ths
update (Thanks Nitay Ben-Zvi).</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c7a51318930624defbb1f3dff1e5ab32d1283dcf"><code>c7a5131</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/37">#37</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/e79dc0858de2a0d0a6473ff161dca04cb6a69e24"><code>e79dc08</code></a>
Release 2.1.5</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/f348ce328a26c08e0b3a81f129652cf5157617b4"><code>f348ce3</code></a>
Fix WindowCovering.targetPositionLiftPercent100ths update and add
transitionT...</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.1.4...2.1.5">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.1.4&new-version=2.1.5)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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