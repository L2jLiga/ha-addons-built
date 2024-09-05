Changes in this Release

<details><summary>2b92ca5 chore: bump matterbridge from 1.5.2 to 1.5.3 in /matterbridge-zigbee2mqtt (#65)</summary>
chore: bump matterbridge from 1.5.2 to 1.5.3 in /matterbridge-zigbee2mqtt (#65)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.5.2
to 1.5.3.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.5.3</h2>
<h2>[1.5.3] - 2024-09-04</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Added mattermdnsinterface, matteripv4address and
matteripv6address to the matter settings. If no parameters are added,
Matterbridge will use the settings from the frontend that are saved. The
default is all interfaces. If you are facing issues with pairing, I
suggest to try first to put the interfaceName (e.g eth0, WiFi) in the
MdnsInterface field. When nothing is selected, NodeJs will choose the
interface but sometimes the choice is not correct at all.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[package]: Update matter-node.js to 0.10.0 and removed the Scene
cluster to follow matter.js.</li>
<li>[package]: Update matter-history to 1.1.8.</li>
<li>[package]: Removed long deprecated exports.</li>
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
<h2>[1.5.3] - 2024-09-04</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Added mattermdnsinterface, matteripv4address and
matteripv6address to the matter settings. If no parameters are added,
Matterbridge will use the settings from the frontend that are saved. The
default is all interfaces. If you are facing issues with pairing, I
suggest to try first to put the interfaceName (e.g eth0, WiFi) in the
MdnsInterface field. When nothing is selected, NodeJs will choose the
interface but sometimes the choice is not correct at all.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
<li>[package]: Update matter-node.js to 0.10.0 and removed the Scene
cluster to follow matter.js.</li>
<li>[package]: Update matter-history to 1.1.8.</li>
<li>[package]: Removed long deprecated exports.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d3cf97f81b4cad254af251932ed4657dcd067d53"><code>d3cf97f</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/121">#121</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d6fa55586347bcd2481d6070393e392385eb5623"><code>d6fa555</code></a>
Release 1.5.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/6f9b3de863c143e0ffe17f50611fdb62fb1915d6"><code>6f9b3de</code></a>
Release 1.5.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/57363ebcf276f933805f99f4f38c58022b9931db"><code>57363eb</code></a>
Release 1.5.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8e5763101470432f720aa2cb08ab2b31b0e6d921"><code>8e57631</code></a>
Release 1.5.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7467721f19908eb28fbc6e8a2eba4f5f2862aca9"><code>7467721</code></a>
1.5.3-dev.4</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/60d34d2462d497164a4e80d509f290ae53e8db13"><code>60d34d2</code></a>
1.5.3-dev.4</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8313227af24bf432e24033e4bf85993e35d7a2e1"><code>8313227</code></a>
1.5.3-dev.4</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/ffad0676409152c451e6b4a2fbbddbdf1c0ca758"><code>ffad067</code></a>
Set info for log ipv6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1d597c80d4e47f14a461c1a37410519c99cf2d36"><code>1d597c8</code></a>
Added mattermdnsinterface, matteripv4address and matteripv6address</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.5.2...1.5.3">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.5.2&new-version=1.5.3)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>4f9a6fd chore: bump matterbridge-zigbee2mqtt from 2.1.14 to 2.1.16 in /matterbridge-zigbee2mqtt (#66)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.1.14 to 2.1.16 in /matterbridge-zigbee2mqtt (#66)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.1.14 to 2.1.16.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.16</h2>
<h3>Breaking Changes</h3>
<ul>
<li>Unless you are using docker (in that case all is already updated),
please update Matterbridge to 1.5.3 to work with
matterbridge-zigbee2mqtt 2.1.16. This is a one time issue due to the
update to matter.js 0.10.0.</li>
</ul>
<h2>[2.1.16] - 2024-09-04</h2>
<h3>Changed</h3>
<ul>
<li>[package]: Final update to matter.js 0.10.0.</li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 2.1.15</h2>
<h3>Breaking Changes</h3>
<ul>
<li>Unless you are using docker (in that case all is already updated),
please update Matterbridge to 1.5.3 to work with
matterbridge-zigbee2mqtt 2.1.15. This is a one time issue due to the
update to matter.js 0.10.0.</li>
</ul>
<h2>[2.1.15] - 2024-09-03</h2>
<h3>Changed</h3>
<ul>
<li>[package]: Updated Thermostat cluster to matter.js 0.10.0.</li>
<li>[package]: Updated dependencies.</li>
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
<h2>[2.1.16] - 2024-09-04</h2>
<h3>Changed</h3>
<ul>
<li>[package]: Final update to matter.js 0.10.0.</li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
<h2>[2.1.15] - 2024-09-03</h2>
<h3>Changed</h3>
<ul>
<li>[package]: Updated Thermostat cluster to matter.js 0.10.0.</li>
<li>[package]: Updated dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/54f5b8a854d8ff3261b71735a5f6b621edca87f8"><code>54f5b8a</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/66">#66</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/fc7d6f2283cca78bb263281a647a6cdd7141f7f9"><code>fc7d6f2</code></a>
Release 2.1.16</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/09596ec80ce82533d875a9b4082372e6d64168b5"><code>09596ec</code></a>
Release 2.1.16</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/f2c6005670dd33d360fec26ffd63c863e7b34fa7"><code>f2c6005</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/65">#65</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/b4e4036aea7d165724a7d32a89ab3061f3100c1a"><code>b4e4036</code></a>
Release 2.1.15</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/65d97711f9335936d2e4b5501c83e5ecbaba60f2"><code>65d9771</code></a>
Release 2.1.15</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/23cc6556c447470c8f3c110e52e53048f939138f"><code>23cc655</code></a>
Release 2.1.15</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.1.14...2.1.16">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.1.14&new-version=2.1.16)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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