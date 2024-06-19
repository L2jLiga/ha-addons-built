Changes in this Release

<details><summary>2f5552f chore: bump matterbridge-zigbee2mqtt from 2.0.17 to 2.1.0 in /matterbridge-zigbee2mqtt (#27)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.0.17 to 2.1.0 in /matterbridge-zigbee2mqtt (#27)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.0.17 to 2.1.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.0</h2>
<h2>[2.1.0] - 2024-06-19</h2>
<h3>Added</h3>
<ul>
<li>[dependencies]: Update dependencies.</li>
<li>[schema]: Added schema to the root directory of the plugin.</li>
<li>[z2m]: Added soil_moisture property as humidity sensor.</li>
<li>[z2m]: Added transition if the zigbee device supports it and the
controller sends it. You can disable this globally adding transition to
the featureBlackList or only for the single device adding transition to
the deviceFeatureBlackList. (Thanks Stefan Schweiger).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matter]: Removed PowerSourceConfiguration cluster that is
deprecated in Matter 1.3.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[schema]: Username and password are no more required fields (Thanks
Stefan Schweiger).</li>
<li>[LevelControl]: Fixed the commandHandler for LevelControl in child
endpoint (Thanks jpadie).</li>
<li>[availability]: Fixed the issue that caused the availability event
sent before the start to be ignored.</li>
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
<h2>[2.1.0] - 2024-06-19</h2>
<h3>Added</h3>
<ul>
<li>[dependencies]: Update dependencies.</li>
<li>[schema]: Added schema to the root directory of the plugin.</li>
<li>[z2m]: Added soil_moisture property as humidity sensor.</li>
<li>[z2m]: Added transition if the zigbee device supports it and the
controller sends it. You can disable this globally adding transition to
the featureBlackList or only for the single device adding transition to
the deviceFeatureBlackList. (Thanks Stefan Schweiger).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matter]: Removed PowerSourceConfiguration cluster that is
deprecated in Matter 1.3.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[schema]: Username and password are no more required fields (Thanks
Stefan Schweiger).</li>
<li>[LevelControl]: Fixed the commandHandler for LevelControl in child
endpoint (Thanks jpadie).</li>
<li>[availability]: Fixed the issue that caused the availability event
sent before the start to be ignored.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c4b49c41d573a43973bb3b203980b40c21732680"><code>c4b49c4</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/29">#29</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/621aeec941714821f9c56ee8bf2bad06933673a7"><code>621aeec</code></a>
Release 2.1.0</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/bfe112b14c7f494586af99160719a0c86dacecdd"><code>bfe112b</code></a>
Release 2.1.0</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/aea1b26a4b4f2ab13df4f0cece029e7d046ccff3"><code>aea1b26</code></a>
Release 2.0.18</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/b5f98fc5f8db3446f6f2e21622d7a2412430dc44"><code>b5f98fc</code></a>
Refactor BridgeDevice to use methods from MatterbridgeDevice</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/9de8622a39d7a449346b2ea0defb2503727d1ed1"><code>9de8622</code></a>
Release 2.0.18</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/8e0a6b9b9a5a2358735a48beacd2509905b40fa1"><code>8e0a6b9</code></a>
Release 2.0.18</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/3b78c7e675ca70bb3e566e1e25f868c30da1d03b"><code>3b78c7e</code></a>
Added soil_moisture as humidity sensor</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/ac021486e2c59a1d8efab47d42714d4daff34103"><code>ac02148</code></a>
Update dependencies</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c4028d63d1988910a7eac9b4af4b5dfa9180b98c"><code>c4028d6</code></a>
Create matterbridge-zigbee2mqtt.schema.json</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.0.17...2.1.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.0.17&new-version=2.1.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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