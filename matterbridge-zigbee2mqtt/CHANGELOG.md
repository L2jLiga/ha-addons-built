Changes in this Release

<details><summary>5e81c7a chore: bump matterbridge from 1.2.22 to 1.3.0 in /matterbridge-zigbee2mqtt (#25)</summary>
chore: bump matterbridge from 1.2.22 to 1.3.0 in /matterbridge-zigbee2mqtt (#25)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.2.22
to 1.3.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.0</h2>
<h2>[1.3.0] - 2024-06-16</h2>
<p>This release is all about Matter 1.3</p>
<p>If you are wondering whether the controllers already support Matter
1.3, the answer is unfortunately no.</p>
<p>Only Home Automation supports:</p>
<ul>
<li>airQualitySensor (Matter 1.2)</li>
</ul>
<p>and (probably only like BooleanState cluster)</p>
<ul>
<li>waterFreezeDetector (Matter 1.3)</li>
<li>waterLeakDetector (Matter 1.3)</li>
<li>rainSensor (Matter 1.3)</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: Default config and schema for the new plugin
matterbridge-shelly (will be published after this release)</li>
</ul>
<h3>Added</h3>
<ul>
<li>[matterbridgeDevice]: Added waterFreezeDetector, waterLeakDetector,
rainSensor, smokeCoAlarm, electricalSensor and deviceEnergyManagement
device types as conformance to Matter 1.3</li>
<li>[matterbridgeDevice]: Added all clusters needed for the above Matter
1.3 device types</li>
<li>[matterbridgeDevice]: Added FanControl cluster (rev. 2) helper
methods for the Fan device type</li>
<li>[matterbridge]: Added parameter -matterlogger [debug | info | notice
| warn | error | fatal] to set the matter.js Logger separately from the
Matterbridge log</li>
<li>[frontend]: Added logger level settings to reflect -matterlogger
[debug | info | notice | warn | error | fatal]</li>
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
<h2>[1.3.0] - 2024-06-16</h2>
<p>This release is all about Matter 1.3</p>
<p>If you are wondering whether the controllers already support Matter
1.3, the answer is unfortunately no.</p>
<p>Only Home Automation supports:</p>
<ul>
<li>airQualitySensor (Matter 1.2)</li>
</ul>
<p>and (probably only like BooleanState cluster)</p>
<ul>
<li>waterFreezeDetector (Matter 1.3)</li>
<li>waterLeakDetector (Matter 1.3)</li>
<li>rainSensor (Matter 1.3)</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: Default config and schema for the new plugin
matterbridge-shelly (will be published after this release)</li>
</ul>
<h3>Added</h3>
<ul>
<li>[matterbridgeDevice]: Added waterFreezeDetector, waterLeakDetector,
rainSensor, smokeCoAlarm, electricalSensor and deviceEnergyManagement
device types as conformance to Matter 1.3</li>
<li>[matterbridgeDevice]: Added all clusters needed for the above Matter
1.3 device types</li>
<li>[matterbridgeDevice]: Added FanControl cluster (rev. 2) helper
methods for the Fan device type</li>
<li>[matterbridge]: Added parameter -matterlogger [debug | info | notice
| warn | error | fatal] to set the matter.js Logger separately from the
Matterbridge log</li>
<li>[frontend]: Added logger level settings to reflect -matterlogger
[debug | info | notice | warn | error | fatal]</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a2b0e853f412ea12ea067fc30bad1e4ecf4e841a"><code>a2b0e85</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/52">#52</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/592dba12fb4cbc062049f9f1f38f00d2fbf5542a"><code>592dba1</code></a>
Release 1.3.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1ef1c683ffda12584fd2a3a2092ecdc6543e58e3"><code>1ef1c68</code></a>
feat: Add parameter to set matter.js Logger separately from the
Matterbridge log</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1fc15e6f153e86c42205a8633a880f5c09975af6"><code>1fc15e6</code></a>
Added param matterlogger to set matter Logger</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/6fa3f2658e01567441c34243e606abc9864abb47"><code>6fa3f26</code></a>
Release 1.3.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/89b40d0dbebda6af1cf7110a62adc85ce8ca4ad8"><code>89b40d0</code></a>
feat: Deprecate deprecated methods in MatterbridgeDevice</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a3821c25f8987071e5db8130587cc536c278de8a"><code>a3821c2</code></a>
feat: Add FanControlCluster rev. 4 and getDefaultFanControlClusterServer
to M...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4b10da5b255de1a1f907316fce8edb5d8b2849d5"><code>4b10da5</code></a>
Refactor MatterbridgeV8.ts to remove commented out code and unused
imports</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/9eb95a62e4f18a0f6b5c7d542fe8675cfe863025"><code>9eb95a6</code></a>
MatterbridgeV8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3b1da70a7b7b4f4d3ecd7ba83e34120d73826461"><code>3b1da70</code></a>
New clusters for the new Matter 1.3 device types</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.2.22...1.3.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.2.22&new-version=1.3.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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