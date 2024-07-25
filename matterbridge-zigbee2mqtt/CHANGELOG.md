Changes in this Release

<details><summary>8ffacc3 chore: bump matterbridge-zigbee2mqtt from 2.1.7 to 2.1.8 in /matterbridge-zigbee2mqtt (#47)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.1.7 to 2.1.8 in /matterbridge-zigbee2mqtt (#47)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.1.7 to 2.1.8.
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/blob/main/CHANGELOG.md">matterbridge-zigbee2mqtt's
changelog</a>.</em></p>
<blockquote>
<h2>[2.1.8] - 2024-07-12</h2>
<h3>Changed</h3>
<ul>
<li>[z2m]: Updated matterbridge imports.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commits">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.1.7&new-version=2.1.8)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>3b9f470 chore: bump matterbridge from 1.3.13 to 1.4.0 in /matterbridge-zigbee2mqtt (#46)</summary>
chore: bump matterbridge from 1.3.13 to 1.4.0 in /matterbridge-zigbee2mqtt (#46)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.13
to 1.4.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.4.0</h2>
<h2>[1.4.0] - 2024-07-23</h2>
<h3>Added</h3>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[matterbridge]: Added PluginsManager.ts.</li>
<li>[matterbridge]: Removed timeout on cleanup.</li>
<li>[matterbridge]: Removed write cache and expired interval for node
storage.</li>
<li>[matterbridge]: Added matterbridgeTypes.ts</li>
<li>[frontend]: The frontend reconnects to WebSocket when the connection
is closed.</li>
<li>[frontend]: Removed QR button for plugins in error and not
enabled.</li>
<li>[frontend]: The Logs page and the log in the Home page persist till
you close or reload the frontend (the last 1000 lines are
available).</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed utils export</li>
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
<h2>[1.4.0] - 2024-07-23</h2>
<h3>Added</h3>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[matterbridge]: Added PluginsManager.ts.</li>
<li>[matterbridge]: Removed timeout on cleanup.</li>
<li>[matterbridge]: Removed write cache and expired interval for node
storage.</li>
<li>[matterbridge]: Added matterbridgeTypes.ts</li>
<li>[frontend]: The frontend reconnects to WebSocket when the connection
is closed.</li>
<li>[frontend]: Removed QR button for plugins in error and not
enabled.</li>
<li>[frontend]: The Logs page and the log in the Home page persist till
you close or reload the frontend (the last 1000 lines are
available).</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed utils export</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d22fccc034628d5b9aae23c4334ffa641d8539bb"><code>d22fccc</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/89">#89</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/48562b25bd848e856c4b1224310af70ff072c939"><code>48562b2</code></a>
Release 1.4.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3deee7f7f8d3c578d6453c00d89d6221ad37c8c7"><code>3deee7f</code></a>
Release 1.3.28</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/2e5bf19f6dc0a47da222e7f68a733fffd318abc0"><code>2e5bf19</code></a>
Release 1.3.27</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/924e4b5bfd775eb0f7559954b40fd69409e780b2"><code>924e4b5</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b45103d94e8761367ea9ce6a77bec376a90c2b2e"><code>b45103d</code></a>
Release 1.3.27</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e9288d0b3954d8fdae2e74565b8051900feafca7"><code>e9288d0</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8e68f6115d8a5c0762f2168d809f8920267f018e"><code>8e68f61</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/674ee740037153f3c246d13e58c29f0d576c6c0b"><code>674ee74</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3dc3037416951d1b8af3c482756d77d54fc4de1c"><code>3dc3037</code></a>
Jest</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.13...1.4.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.13&new-version=1.4.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>411753d feat: update base image</summary>
feat: update base image
</details>

<details><summary>cebf160 feat: update base addon image</summary>
feat: update base addon image
</details>

<details><summary>4c48517 chore: improved docker caching</summary>
chore: improved docker caching
</details>