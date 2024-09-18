Changes in this Release

<details><summary>b73d04f chore: bump matterbridge from 1.5.6 to 1.5.7 in /matterbridge-zigbee2mqtt (#70)</summary>
chore: bump matterbridge from 1.5.6 to 1.5.7 in /matterbridge-zigbee2mqtt (#70)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.5.6
to 1.5.7.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.5.7</h2>
<h2>[1.5.7] - 2024-09-17</h2>
<h3>Added</h3>
<ul>
<li>[matterbridge]: Added the <a
href="https://github.com/Luligu/matterbridge-home-assistant-addon">Official
Matterbridge Home Assistant Add-on</a></li>
</ul>
<h3>Changed</h3>
<ul>
<li>[electricalSensor]: Refactor the
getDefaultElectricalEnergyMeasurementClusterServer and
getDefaultElectricalPowerMeasurementClusterServer</li>
<li>[package]: Update matter-node.js to 0.10.3.</li>
<li>[package]: Update matter-history to 1.1.14.</li>
<li>[package]: Update dependencies.</li>
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
<h2>[1.5.7] - 2024-09-17</h2>
<h3>Added</h3>
<ul>
<li>[matterbridge]: Added the <a
href="https://github.com/Luligu/matterbridge-home-assistant-addon">Official
Matterbridge Home Assistant Add-on</a></li>
</ul>
<h3>Changed</h3>
<ul>
<li>[electricalSensor]: Refactor the
getDefaultElectricalEnergyMeasurementClusterServer and
getDefaultElectricalPowerMeasurementClusterServer</li>
<li>[package]: Update matter-node.js to 0.10.3.</li>
<li>[package]: Update matter-history to 1.1.14.</li>
<li>[package]: Update dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/9ac134c2c44a99a3bc706e0be6ae8cb170297233"><code>9ac134c</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/132">#132</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8264ce31455fcad52580e4a5b809c49403688cdc"><code>8264ce3</code></a>
Fix jsdoc</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/81582e72328fb78eb27a38599699c263563afa1f"><code>81582e7</code></a>
Fix jsdoc</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c3d40d1cca0f82c86d1389514b673907fd7c2404"><code>c3d40d1</code></a>
Release 1.5.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/776a41ffb00571040f4cdd5bbf795b349b15f2c5"><code>776a41f</code></a>
Update to docker/login-action@v3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/062f3d2628730d1c1ba3fcb7f6e09636675c455f"><code>062f3d2</code></a>
Update to docker/login-action@v3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/5b617ea2a8666e71d92f861a4f8da98f2d4da30c"><code>5b617ea</code></a>
Dev 1.5.7-dev.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e3c238a09585dfc98837f5f3f30a68134558ea66"><code>e3c238a</code></a>
Dev 1.5.7-dev.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3d524c297b8f61ad2eed60970d43c3e6d9b23a68"><code>3d524c2</code></a>
CHANGELOG.md</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/afd2f8f6cc9eea954324928209a0a01b3e218f0f"><code>afd2f8f</code></a>
Fixed default valu to null for electrical sensor</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.5.6...1.5.7">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.5.6&new-version=1.5.7)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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