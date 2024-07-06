Changes in this Release

<details><summary>e78c771 chore: bump matterbridge from 1.3.9 to 1.3.10 in /matterbridge-zigbee2mqtt (#40)</summary>
chore: bump matterbridge from 1.3.9 to 1.3.10 in /matterbridge-zigbee2mqtt (#40)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.9
to 1.3.10.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.10</h2>
<h2>[1.3.10] - 2024-07-05</h2>
<h3>Added</h3>
<ul>
<li>[fabrics]: Added fabricInfo to matterbridge in bridge mode and to
the plugins in childbridge mode.</li>
<li>[sessions]: Added sessionInfo to matterbridge in bridge mode and to
the plugins in childbridge mode.</li>
<li>[frontend]: Added fabricInfo in bridge mode and in childbridge mode
instead of QRCode if already paired.</li>
<li>[frontend]: Added sessionInfo in bridge mode and in childbridge mode
instead of QRCode if already paired.</li>
<li>[matterbridge]: Added parsePlugin to load the updated data from the
plugin even when is disabled.</li>
<li>[matterbridge]: Added an automatic plugin reinstall from npm when
the plugin is not found. (e.g. when the docker image is updated and the
plugin is not an official plugin)</li>
</ul>
<h3>Changed</h3>
<ul>
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
<h2>[1.3.10] - 2024-07-05</h2>
<h3>Added</h3>
<ul>
<li>[fabrics]: Added fabricInfo to matterbridge in bridge mode and to
the plugins in childbridge mode.</li>
<li>[sessions]: Added sessionInfo to matterbridge in bridge mode and to
the plugins in childbridge mode.</li>
<li>[frontend]: Added fabricInfo in bridge mode and in childbridge mode
instead of QRCode if already paired.</li>
<li>[frontend]: Added sessionInfo in bridge mode and in childbridge mode
instead of QRCode if already paired.</li>
<li>[matterbridge]: Added parsePlugin to load the updated data from the
plugin even when is disabled.</li>
<li>[matterbridge]: Added an automatic plugin reinstall from npm when
the plugin is not found. (e.g. when the docker image is updated and the
plugin is not an official plugin)</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[dependencies]: Update dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/5a9042eea94a7e1e0dd356ff8ccdf41dd4ec2aaa"><code>5a9042e</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/78">#78</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/22ed3e8571dcba4ce4a313f0a8ff367f7912fd34"><code>22ed3e8</code></a>
Frontend 1.1.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/69bf843d687738963fb195811edd6dc87a2ba3f3"><code>69bf843</code></a>
Frontend 1.1.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7aa0bc68ef7572597e0b569cec977c09910efabb"><code>7aa0bc6</code></a>
Release 1.3.10</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/cd14dc3f918524c2b06b77f8792c04c4386cc08b"><code>cd14dc3</code></a>
Added an automatic plugin reinstall from npm</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b03dbb16520adf0ae42715b0b490465fb18b7479"><code>b03dbb1</code></a>
Added an automatic plugin reinstall from npm</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d273cb56ee6ee9611fdf84dbe870a2dc6b7d6647"><code>d273cb5</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/06341e84e43a5499663f0db78a94b04192f43dba"><code>06341e8</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f2775e7d224439f17be6baf6264025960a2405ac"><code>f2775e7</code></a>
Jest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/43f5779991f1ec5254ecb033dd5faf291ce441cb"><code>43f5779</code></a>
Fix sesssions</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.9...1.3.10">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.9&new-version=1.3.10)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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