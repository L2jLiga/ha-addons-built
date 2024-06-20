Changes in this Release

<details><summary>605adbf chore: bump matterbridge from 1.3.0 to 1.3.1 in /matterbridge-zigbee2mqtt (#28)</summary>
chore: bump matterbridge from 1.3.0 to 1.3.1 in /matterbridge-zigbee2mqtt (#28)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.0
to 1.3.1.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.1</h2>
<h2>[1.3.1] - 2024-06-20</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: Refactor the loading of schemas, now they load from
the plugin directory.</li>
<li>[matterbridge]: Moved getPluginVersion to the start also for
disabled plugins.</li>
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
<h2>[1.3.1] - 2024-06-20</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: Refactor the loading of schemas, now they load from
the plugin directory.</li>
<li>[matterbridge]: Moved getPluginVersion to the start also for
disabled plugins.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1f277fc989eccc43af69be4a36c4bb09c287af13"><code>1f277fc</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/54">#54</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a45e065cc8af38c6f14a6d89965f09141a2fa7fd"><code>a45e065</code></a>
Release 1.3.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/646cdf2eee8d84d6d17e60540db2b73abf5fe411"><code>646cdf2</code></a>
Refactor plugin schema loading logic and move getPluginVersion to the
start f...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f697c66da8579d5d7d8fee9049277fff6d615ad4"><code>f697c66</code></a>
Added getPluginLatestVersion to the start also for disabled plugins</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/fc7d0ad3f07d1a7e4fd86806f4a64d7f96c2f246"><code>fc7d0ad</code></a>
Refactor addChildDeviceTypeWithClusterServer to use uniqueStorageKey to
find ...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7ae03e83989c43ec6e4830d87f13a5708678610a"><code>7ae03e8</code></a>
Refactor plugin schema loading logic and update z2m required fields</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8356f7e2e01901264aeb0da7f3fbcf1e46ca4b67"><code>8356f7e</code></a>
Refactor plugin schema loading logic. Changed z2m required fields.</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a6c0ab47f7967d27f4ac734498638bd7762885c5"><code>a6c0ab4</code></a>
Refactor plugin schema loading logic to delete the schema file from
.matterbr...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3f47a977c0cf48eb816ec12cc9a7ee004c8a758a"><code>3f47a97</code></a>
Refactor plugin schema loading logic to support plugin directory first
and ma...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/68a97b08def1e36b0dcbd16caae04d10e98ce57b"><code>68a97b0</code></a>
feat: Update plugin configuration and schema saving and loading
logic</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.0...1.3.1">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.0&new-version=1.3.1)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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