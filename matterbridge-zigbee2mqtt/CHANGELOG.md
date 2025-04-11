Changes in this Release

<details><summary>67f95f3 chore: bump matterbridge from 2.2.7 to 2.2.8 in /matterbridge-zigbee2mqtt (#126)</summary>
chore: bump matterbridge from 2.2.7 to 2.2.8 in /matterbridge-zigbee2mqtt (#126)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 2.2.7
to 2.2.8.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.2.8</h2>
<h2>[2.2.8] - 2025-04-10</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added stack to error messages.</li>
<li>[endpoint]: Added createLevelControlClusterServer()</li>
<li>[endpoint]: Added createLevelTvocMeasurementClusterServer()</li>
<li>[frontend]: Added a restart button on the QRCode panel when the
advertising for a not paired node is expired.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[package]: Use node:https.</li>
<li>[endpoint]: Modified createOnOffClusterServer().</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[homepage]: Fixed warning log for homepage property in
package.json.</li>
<li>[DevicesIcon]: Fixed rendering of rain, freeze and leak
sensors.</li>
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
<h2>[2.2.8] - 2025-04-10</h2>
<h3>Added</h3>
<ul>
<li>[platform]: Added stack to errors messages.</li>
<li>[endpoint]: Added createLevelTvocMeasurementClusterServer()</li>
<li>[frontend]: Added a restart button on the QRCode panel when the
advertising for a not paired node is expired.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[package]: Use node:https.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[homepage]: Fixed warning log for homepage property in
package.json.</li>
<li>[DevicesIcon]: Fixed rendering of rain, freeze and leak
sensors.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/925c41f041a25d98dff3a65b86da9e81344be71c"><code>925c41f</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/265">#265</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d972034b9b6fd455a09cf4cc646ded8f3c010ee6"><code>d972034</code></a>
Release 2.2.8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a88e3e5cdb934c3b5a4930c31a7c521f76f54873"><code>a88e3e5</code></a>
Release 2.2.8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/041f844319c5e4fd4349171e6fbaec024a980c50"><code>041f844</code></a>
Increase timeout for childbridge Jest test</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/00496b2839c0acb608e5fa0008be9a973a81e7b0"><code>00496b2</code></a>
Dev 2.2.8-dev.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/dc888d477f0fd0a341ec58f145d8a56b66dc955e"><code>dc888d4</code></a>
Release 2.2.8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b6eb4c6da1a5153c62d47d1a2ffb7f7a760bb215"><code>b6eb4c6</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/259">#259</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d29690be5b667d41f69665cb0dcab44a15088905"><code>d29690b</code></a>
Release 2.2.8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/ad3ea8205da2a6add5bd8a43adec8bba8ca53417"><code>ad3ea82</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/258">#258</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f557898760887a6bb6f571ce4f7cf1b1a2d14362"><code>f557898</code></a>
Merge branch 'dev' of <a
href="https://github.com/Luligu/matterbridge">https://github.com/Luligu/matterbridge</a>
into dev</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/2.2.7...2.2.8">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=2.2.7&new-version=2.2.8)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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