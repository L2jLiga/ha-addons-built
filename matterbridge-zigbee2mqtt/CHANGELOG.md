Changes in this Release

<details><summary>005a813 chore: bump matterbridge from 1.3.10 to 1.3.11 in /matterbridge-zigbee2mqtt (#41)</summary>
chore: bump matterbridge from 1.3.10 to 1.3.11 in /matterbridge-zigbee2mqtt (#41)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.10
to 1.3.11.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.11</h2>
<h2>[1.3.11] - 2024-07-08</h2>
<h3>Added</h3>
<ul>
<li>[device]: Added addRequiredClusterServers and
addOptionalClusterServers methods.</li>
<li>[frontend]: Added separated settings for the two logging systems
(Matterbridge and Matter.js).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[device]: Refactor contructor and loadInstance to accept
DeviceTypeDefinition | AtLeastOne<!-- raw HTML omitted -->.</li>
<li>[frontend]: Update to 1.2.0 (initial optimization for mobile)</li>
<li>[dependencies]: Update dependencies.</li>
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
<h2>[1.3.11] - 2024-07-08</h2>
<h3>Added</h3>
<ul>
<li>[device]: Added addRequiredClusterServers and
addOptionalClusterServers methods.</li>
<li>[frontend]: Added separated settings for the two logging systems
(Matterbridge and Matter.js).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[device]: Refactor contructor and loadInstance to accept
DeviceTypeDefinition | AtLeastOne<!-- raw HTML omitted -->.</li>
<li>[frontend]: Update to 1.2.0 (initial optimization for mobile)</li>
<li>[dependencies]: Update dependencies.</li>
</ul>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/20cb6332dfd39a005784bcb4872f20bc4c3ff8cd"><code>20cb633</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/80">#80</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/121796744ed5e304256eda6afe62d2e72602fe98"><code>1217967</code></a>
Release 1.3.11</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1fd0a2ef3c71c903b005e91dee6c8cbba698c801"><code>1fd0a2e</code></a>
Release 1.3.11</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e6f70d3fa3293ec8b5f3550f5fcd39d0eebd6641"><code>e6f70d3</code></a>
Release 1.3.11</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7b052fd096cba880cb2a4932ad64a50a71fd35f6"><code>7b052fd</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a06862b9effefb38eeb884cafafd067a8794aeda"><code>a06862b</code></a>
Release 1.3.11</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a7231afe332a73ecb691f016e002b928909062b8"><code>a7231af</code></a>
Update dependencies.</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d9ae514c29143951cf19a07a07d3e236f671adb1"><code>d9ae514</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f9ee753ba0f46acf4e77a2699e42007c240649fd"><code>f9ee753</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/31f335a4318471363241d78fe4e3702e50b907be"><code>31f335a</code></a>
Jest</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.10...1.3.11">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.10&new-version=1.3.11)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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