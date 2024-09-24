Changes in this Release

<details><summary>5801d06 chore: bump matterbridge-zigbee2mqtt from 2.1.16 to 2.1.17 in /matterbridge-zigbee2mqtt (#72)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.1.16 to 2.1.17 in /matterbridge-zigbee2mqtt (#72)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.1.16 to 2.1.17.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.17</h2>
<h2>[2.1.17] - 2024-09-21</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Removed Matterbridge deprecated method to get the
child endpoints.</li>
<li>[package]: Updated dependencies.</li>
<li>[plugin]: Moved trigger code to matterbridge
triggerSwitchEvent.</li>
</ul>
<h3>Added</h3>
<ul>
<li>[matterbridge]: Added a check of the current Matterbridge version
(required v1.5.5).</li>
<li>[plugin]: Added configuration of ColorControl cluster features (HS,
XY, CT).</li>
<li>[plugin]: Removed the superset device types.</li>
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
<h2>[2.1.17] - 2024-09-21</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Removed Matterbridge deprecated method to get the
child endpoints.</li>
<li>[package]: Updated dependencies.</li>
<li>[plugin]: Moved trigger code to matterbridge
triggerSwitchEvent.</li>
</ul>
<h3>Added</h3>
<ul>
<li>[matterbridge]: Added a check of the current Matterbridge version
(required v1.5.5).</li>
<li>[plugin]: Added configuration of ColorControl cluster features (HS,
XY, CT).</li>
<li>[plugin]: Removed the superset device types.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/79f6d9280fd3e123dd48e3cb49be4114824294d3"><code>79f6d92</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/69">#69</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/6a7a2677bec1cbb54c75fd803b41124d8ed0b83f"><code>6a7a267</code></a>
Release 2.1.17</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/21f90549cec7678aca019e130140081fe50b6d94"><code>21f9054</code></a>
Release 2.1.17</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/cc176188e07119ae10de771ce0842738fc148b49"><code>cc17618</code></a>
2.1.17-dev.4</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c8df9970da34600fb3ade1484f47f3a994b7661b"><code>c8df997</code></a>
Removed the superset device types.</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/7e91095827e6ffa03e29fdcb6f2f78ade521e305"><code>7e91095</code></a>
2.1.17-dev.3</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/e776b30cc361b411d7a558711571e9c9830c64e8"><code>e776b30</code></a>
Added endpoint name in the updateHandler</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/58161790b2c17c45f1a6d04fdddf20f6ee7c371f"><code>5816179</code></a>
Moved to uniqueStorageKey to identificate childs</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c9698fb58f952bef0a69681f052ed003debf63a5"><code>c9698fb</code></a>
Added configuration of ColorControl cluster features (HS, XY, CT)</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/86d0cf034d5c3194aaba0670961169322129469d"><code>86d0cf0</code></a>
Moved to matterbridge triggerSwitchEvent</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.1.16...2.1.17">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.1.16&new-version=2.1.17)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>1463c5a chore: bump matterbridge from 1.5.7 to 1.5.9 in /matterbridge-zigbee2mqtt (#71)</summary>
chore: bump matterbridge from 1.5.7 to 1.5.9 in /matterbridge-zigbee2mqtt (#71)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.5.7
to 1.5.9.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.5.9</h2>
<h2>[1.5.9] - 2024-09-23</h2>
<h3>Fixed</h3>
<ul>
<li>[ingress]: Fixed download routes with Ingress from the ha addon. The
add-on <a
href="https://github.com/Luligu/matterbridge-home-assistant-addon">https://github.com/Luligu/matterbridge-home-assistant-addon</a>
has been updated to v. 1.0.4.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter-node.js to 0.10.6.</li>
<li>[package]: Update matter-history to 1.1.16.</li>
<li>[package]: Update dependencies.</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 1.5.8</h2>
<h2>[1.5.8] - 2024-09-21</h2>
<h3>Added</h3>
<ul>
<li>[readme]: Added podman guidelines to the README.md</li>
<li>[readme]: Added instructions for setting permanent journalctl
settings in service mode to prevent journal to grow</li>
<li>[readme]: Added instructions for removing sudo password for npm
install in service mode</li>
<li>[readme]: Refactor systemd instructions for Matterbridge
service</li>
<li>[readme]: Added link to install matterbridge like ha addon <a
href="https://github.com/Luligu/matterbridge-home-assistant-addon">https://github.com/Luligu/matterbridge-home-assistant-addon</a></li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter-node.js to 0.10.5.</li>
<li>[package]: Update matter-history to 1.1.15.</li>
<li>[package]: Update dependencies.</li>
<li>[matterbridge]: Reset session informations when the controllers are
not connected.</li>
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
<h2>[1.5.9] - 2024-09-23</h2>
<h3>Fixed</h3>
<ul>
<li>[ingress]: Fixed download routes with Ingress from the ha addon. The
add-on <a
href="https://github.com/Luligu/matterbridge-home-assistant-addon">https://github.com/Luligu/matterbridge-home-assistant-addon</a>
has been updated to v. 1.0.4.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter-node.js to 0.10.6.</li>
<li>[package]: Update matter-history to 1.1.16.</li>
<li>[package]: Update dependencies.</li>
</ul>
<!-- raw HTML omitted -->
<h2>[1.5.8] - 2024-09-21</h2>
<h3>Added</h3>
<ul>
<li>[readme]: Added podman guidelines to the README.md</li>
<li>[readme]: Added instructions for setting permanent journalctl
settings in service mode to prevent journal to grow</li>
<li>[readme]: Added instructions for removing sudo password for npm
install in service mode</li>
<li>[readme]: Refactor systemd instructions for Matterbridge
service</li>
<li>[readme]: Added link to install matterbridge like ha addon <a
href="https://github.com/Luligu/matterbridge-home-assistant-addon">https://github.com/Luligu/matterbridge-home-assistant-addon</a></li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter-node.js to 0.10.5.</li>
<li>[package]: Update matter-history to 1.1.15.</li>
<li>[package]: Update dependencies.</li>
<li>[matterbridge]: Reset session informations when the controllers are
not connected.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4581c31af70c862e1de87703443927f91e19c44d"><code>4581c31</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/142">#142</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/aea8cfa2af86186ae797f737d0425a929dcb46c0"><code>aea8cfa</code></a>
Release 1.5.9</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/14c5c919ba25c417db8cd8e26aa5c580452be86b"><code>14c5c91</code></a>
Updated service guidelines</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/23d723c800dd795561ac8016eec7a15eba23c69b"><code>23d723c</code></a>
1.5.9-dev.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/111e021f63e72f6a077d7e4be780a3b7881d97d5"><code>111e021</code></a>
1.5.9-dev.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/2bed0ed1d3624ac29fd50bc61ecdc3f7fcb90b20"><code>2bed0ed</code></a>
Changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/04bea61f9460801e7c7d61794cfb651081077ec2"><code>04bea61</code></a>
Fix download with Ingress</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f43ff0a7c0fcdb652a08928572b3cda7c173a3e0"><code>f43ff0a</code></a>
Ingress</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a2ab595adaaf551f17bede8bb64c887e022798d1"><code>a2ab595</code></a>
Ingress</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4f46b2e9b471e623f0b50929f5e110acd8cbdaf1"><code>4f46b2e</code></a>
Ingress</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.5.7...1.5.9">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.5.7&new-version=1.5.9)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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