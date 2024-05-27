Changes in this Release

<details><summary>1619f1f chore: bump matterbridge from 1.2.16 to 1.2.17 in /matterbridge-zigbee2mqtt (#19)</summary>
chore: bump matterbridge from 1.2.16 to 1.2.17 in /matterbridge-zigbee2mqtt (#19)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.2.16
to 1.2.17.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.2.17</h2>
<h2>[1.2.17] - 2024-05-22</h2>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed the issue causing the commissioning reset for
all fabrics when only one is removed. (Apple uses 2 fabrics: Home app
and Key chain).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Preliminary integration for the new
matterbridge-shelly plugin (still not published)</li>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: Moved eslint to
<code>@​typescript-eslint/strict</code> and
<code>@​typescript-eslint/stylistic</code></li>
</ul>
<h3>Added</h3>
<ul>
<li>[frontend]: Fetch data in Home page every minute</li>
<li>[device]: Added new method addClusterServerFromList</li>
<li>[device]: Added ModeSelectClusterServer (only for testing)</li>
<li>[matterbridge]: Added fabric info in the log on startup</li>
<li>[matterbridge]: Added vendorId for Alexa</li>
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
<h2>[1.2.17] - 2024-05-25</h2>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed the issue causing the commissioning reset for
all fabrics when only one is removed. (Apple uses 2 fabrics: Home app
and Key chain).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Preliminary integration for the new
matterbridge-shelly plugin (still not published)</li>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: Moved eslint to
<code>@​typescript-eslint/strict</code> and
<code>@​typescript-eslint/stylistic</code></li>
</ul>
<h3>Added</h3>
<ul>
<li>[frontend]: Fetch data in Home page every minute</li>
<li>[device]: Added new method addClusterServerFromList</li>
<li>[device]: Added ModeSelectClusterServer (only for testing)</li>
<li>[matterbridge]: Added fabric info in the log on startup</li>
<li>[matterbridge]: Added vendorId for Alexa</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge/commits/1.2.17">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.2.16&new-version=1.2.17)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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