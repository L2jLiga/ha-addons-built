Changes in this Release

<details><summary>40587b9 chore: bump matterbridge from 2.2.4 to 2.2.7 in /matterbridge-zigbee2mqtt (#125)</summary>
chore: bump matterbridge from 2.2.4 to 2.2.7 in /matterbridge-zigbee2mqtt (#125)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 2.2.4
to 2.2.7.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.2.7</h2>
<h2>[2.2.7] - 2025-04-06</h2>
<h3>Added</h3>
<ul>
<li>[package]: Process author, homepage, repository, funding, README.md
and CHANGELOG.md for third-party plugins. If the default implementation
doesn't fit, it is possible to add a custom property &quot;help&quot;
and &quot;changelog&quot; to the package.json.</li>
<li>[frontend]: Added a link to the plugin homepage (click on the plugin
name or on the plugin description).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[frontend]: Frontend v.2.6.1.</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[author]: Fixed case when author is an object in the
package.json.</li>
<li>[platform]: Fix getSelectDevices and getSelectEntities on node &lt;
22.</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 2.2.6</h2>
<h2>[2.2.6] - 2025-04-01</h2>
<h3>Added</h3>
<ul>
<li>[matterbridge]: New plugin matterbridge-webhooks.</li>
<li>[ipv4address]: The ipv4address entered by the user on the command
line or on the frontend is validated on startup. If the value is not
correct an error message is logged and the parameter is discarded.</li>
<li>[ipv6address]: The ipv6address entered by the user on the command
line or on the frontend is validated on startup. If the value is not
correct an error message is logged and the parameter is discarded.</li>
<li>[shelly-board]: For Shelly board only: added Network configuration
reset and Factory reset.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[commissionig]: If the bridge is not paired, when the advertising
stops (after 15 minutes from start) the QR code is hidden and a
notification is displayed.</li>
<li>[package]: Update dependencies.</li>
<li>[package]: Update matter.js to 0.12.6.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[ipv6address]: The ipv6address can be entered in the frontend with
the scopeid. On Windows the format is ipv6%scopeid (i.e.
fe80::5a71:b2f6:7bc8:d00b%8). On Linux the format is ipv6%interfaceName
(i.e. fe80::5a71:b2f6:7bc8:d00b%eth0)</li>
<li>[onOff]: The onOff cluster created from createOnOffClusterServer()
is now correct (no Lighting feature).</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 2.2.5</h2>
<h2>[2.2.5] - 2025-03-19</h2>
<!-- raw HTML omitted -->
</blockquote>
<p>... (truncated)</p>
</details>
<details>
<summary>Changelog</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/blob/main/CHANGELOG.md">matterbridge's
changelog</a>.</em></p>
<blockquote>
<h2>[2.2.7] - 2025-04-06</h2>
<h3>Added</h3>
<ul>
<li>[package]: Process author, homepage, repository, funding, README.md
and CHANGELOG.md for third-party plugins. If the default implementation
doesn't fit, it is possible to add a custom property &quot;help&quot;
and &quot;changelog&quot; to the package.json.</li>
<li>[frontend]: Added a link the plugin homepage (click on the plugin
name or on the plugin description).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[frontend]: Frontend v.2.6.1.</li>
<li>[package]: Update dependencies.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[author]: Fixed case when author is an object in the
package.json.</li>
<li>[platform]: Fix getSelectDevices and getSelectEntities on node &lt;
22.</li>
</ul>
<!-- raw HTML omitted -->
<h2>[2.2.6] - 2025-04-01</h2>
<h3>Added</h3>
<ul>
<li>[matterbridge]: New plugin matterbridge-webhooks.</li>
<li>[ipv4address]: The ipv4address entered by the user on the command
line or on the frontend is validated on startup. If the value is not
correct an error message is logged and the parameter is discarded.</li>
<li>[ipv6address]: The ipv6address entered by the user on the command
line or on the frontend is validated on startup. If the value is not
correct an error message is logged and the parameter is discarded.</li>
<li>[shelly-board]: For Shelly board only: added Network configuration
reset and Factory reset.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[commissionig]: If the bridge is not paired, when the advertising
stops (after 15 minutes from start) the QR code is hidden and a
notification is displayed.</li>
<li>[package]: Update dependencies.</li>
<li>[package]: Update matter.js to 0.12.6.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[ipv6address]: The ipv6address can be entered in the frontend with
the scopeid. On Windows the format is ipv6%scopeid (i.e.
fe80::5a71:b2f6:7bc8:d00b%8). On Linux the format is ipv6%interfaceName
(i.e. fe80::5a71:b2f6:7bc8:d00b%eth0)</li>
<li>[onOff]: The onOff cluster created from createOnOffClusterServer()
is now correct (no Lighting feature).</li>
</ul>
<!-- raw HTML omitted -->
<h2>[2.2.5] - 2025-03-19</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Frontend v.2.6.0.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
<p>... (truncated)</p>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c19d5e1e312b4c6bfeca7793d380134f99211d70"><code>c19d5e1</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/256">#256</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c4e194c3e9310aeed229316bcbab6be69b69ff8f"><code>c4e194c</code></a>
Release 2.2.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8c0e87fb1b327c28d5de2305f516a5efe7a10589"><code>8c0e87f</code></a>
Release 2.2.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d26cf5b4ee408e7a5458f8dd87b56126e6c2644a"><code>d26cf5b</code></a>
Frontend v.2.6.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/eb161c714e2a61affb3d3412513a16cca9c049fd"><code>eb161c7</code></a>
Process author, homepage, repository, funding, README.md and
CHANGELOG.md for...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/95e1236440f1b463f85899256e780c1bb0fd4810"><code>95e1236</code></a>
Fix getSelectDevices and getSelectEntities</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c00ed697e6d0db8ca53778fa12b1b728b8abc702"><code>c00ed69</code></a>
Fix author object in packageJson</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/16615c83f6a7e6056169f81fce2a2de1d13bafe4"><code>16615c8</code></a>
Update CHANGELOG for version 2.2.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3f19f571cfdda8a2755065124395a41efdc5ec2c"><code>3f19f57</code></a>
Fix author object in packageJson</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/2e85d7c09c17e56cade114470e6c92601fe812ea"><code>2e85d7c</code></a>
Update device and entity icon parameter descriptions in
MatterbridgePlatform</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/2.2.4...2.2.7">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=2.2.4&new-version=2.2.7)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>c8ad085 chore: bump matterbridge-zigbee2mqtt from 2.4.6 to 2.4.7 in /matterbridge-zigbee2mqtt (#121)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.4.6 to 2.4.7 in /matterbridge-zigbee2mqtt (#121)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.4.6 to 2.4.7.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.4.7</h2>
<h2>[2.4.7] - 2025-03-19</h2>
<h3>Added</h3>
<ul>
<li>[select]: Added the possibility to whitelist or blacklist with the
device serial (i.e. 0x187a3efffe357548) or the group serial (i.e.
group-1).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Updated package.</li>
<li>[package]: Updated dependencies.</li>
<li>[plugin]: Requires Matterbridge 2.2.5.</li>
<li>[config]: Added parameter postfix (3 characters max) to be
consistent with the other plugins. This parameter works with the Devices
panel in the home page.</li>
<li>[config]: The old postfixHostname will be removed in the next
release. If you were using postfixHostname, please change it with
postfix, the controllers will likely remove and recreate all the devices
so make a backup of configurations (i.e. room assignements) and
automations on the controller!</li>
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
<h2>[2.4.7] - 2025-03-19</h2>
<h3>Added</h3>
<ul>
<li>[select]: Added the possibility to whitelist or blacklist with the
device serial (i.e. 0x187a3efffe357548) or the group serial (i.e.
group-1).</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Updated package.</li>
<li>[package]: Updated dependencies.</li>
<li>[plugin]: Requires Matterbridge 2.2.5.</li>
<li>[config]: Added parameter postfix (3 characters max) to be
consistent with the other plugins. This parameter works with the Devices
panel in the home page.</li>
<li>[config]: The old postfixHostname will be removed in the next
release. If you were using postfixHostname, please change it with
postfix, the controllers will likely remove and recreate all the devices
so make a backup of configurations (i.e. room assignements) and
automations on the controller!</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/5372266e7e3c691a5191ab84af0fef823409b475"><code>5372266</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/103">#103</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/55c3420809e9df3087bcd2d2e00b2cb7c3ebbaea"><code>55c3420</code></a>
Add scenes scanner</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/7f5b213f742791bf513d116029fde3660c63a558"><code>7f5b213</code></a>
Refactor: Comment out debug log statements and improve cluster server ID
hand...</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/23c199f7cccc35da602a527bc9b0ce364c8110b5"><code>23c199f</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/102">#102</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/5b7b67abe979f5beb9963626d59a72c3bcf76653"><code>5b7b67a</code></a>
Update Node.js version matrix in CI workflow to include 23.x</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/a34adf26f09c54954a7327f7a7e394eea0c30f31"><code>a34adf2</code></a>
Requires Matterbridge 2.2.5.</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/7981f7538d0f1853e580fe450139d6e86f1df369"><code>7981f75</code></a>
Release 2.4.7</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/650d8e633c33cd7cfcb25a42b42e16f109393487"><code>650d8e6</code></a>
Automator: update package</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.4.6...2.4.7">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.4.6&new-version=2.4.7)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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