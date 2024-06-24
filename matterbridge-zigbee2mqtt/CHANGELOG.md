Changes in this Release

<details><summary>fa3059b chore: bump matterbridge from 1.3.1 to 1.3.4 in /matterbridge-zigbee2mqtt (#31)</summary>
chore: bump matterbridge from 1.3.1 to 1.3.4 in /matterbridge-zigbee2mqtt (#31)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.1
to 1.3.4.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.4</h2>
<h2>[1.3.4] - 2024-06-23</h2>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed exports</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 1.3.3</h2>
<h2>[1.3.3] - 2024-06-22</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: When a plugin is in an error state, the bridge does
not start to avoid causing the controllers to delete the registered
devices and lose the configuration (e.g. room and automations).</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 1.3.2</h2>
<h2>[1.3.2] - 2024-06-22</h2>
<p>New plugin</p>
<p><a
href="https://github.com/Luligu/matterbridge-shelly">shelly</a></p>
<p>Matterbridge shelly allows you to expose Shelly Gen 1, Gen 2, and Gen
3 devices to Matter.</p>
<p>Features:</p>
<ul>
<li>Shellies are automatically discovered using mDNS.</li>
<li>Discovered shellies are stored in local storage for quick loading on
startup.</li>
<li>In this first release, the components exposed are lights (with
brightness), switches, rollers and power meters (with EveHistory
electrical measurements).</li>
<li>Shellies are controlled locally, eliminating the need for cloud or
MQTT (which can be disabled).</li>
<li>Shelly Gen 1 devices are controlled using the CoIoT protocol (see
the note below).</li>
<li>Shelly Gen 2 and Gen 3 devices are controlled using WebSocket.</li>
<li>The Matter device takes the name configured in the Shelly device's
web page.</li>
<li>A 10-minute timer checks if the device has reported in that
time.</li>
</ul>
<h3>Added</h3>
<ul>
<li>[matterbridgeDevice]: Added all clusters for airQualitySensor:
CarbonMonoxideConcentrationMeasurement,
CarbonDioxideConcentrationMeasurement,
NitrogenDioxideConcentrationMeasurement,
OzoneConcentrationMeasurement,
FormaldehydeConcentrationMeasurement,
Pm1ConcentrationMeasurement,
Pm25ConcentrationMeasurement,</li>
</ul>
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
<h2>[1.3.4] - 2024-06-23</h2>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed exports</li>
</ul>
<!-- raw HTML omitted -->
<h2>[1.3.3] - 2024-06-22</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Updated dependencies</li>
<li>[matterbridge]: When a plugin is in an error state, the bridge does
not start to avoid causing the controllers to delete the registered
devices and lose the configuration (e.g. room and automations).</li>
</ul>
<!-- raw HTML omitted -->
<h2>[1.3.2] - 2024-06-22</h2>
<p>New plugin</p>
<p><a
href="https://github.com/Luligu/matterbridge-shelly">shelly</a></p>
<p>Matterbridge shelly allows you to expose Shelly Gen 1, Gen 2, and Gen
3 devices to Matter.</p>
<p>Features:</p>
<ul>
<li>Shellies are automatically discovered using mDNS.</li>
<li>Discovered shellies are stored in local storage for quick loading on
startup.</li>
<li>In this first release, the components exposed are lights (with
brightness), switches, rollers and power meters (with EveHistory
electrical measurements).</li>
<li>Shellies are controlled locally, eliminating the need for cloud or
MQTT (which can be disabled).</li>
<li>Shelly Gen 1 devices are controlled using the CoIoT protocol (see
the note below).</li>
<li>Shelly Gen 2 and Gen 3 devices are controlled using WebSocket.</li>
<li>The Matter device takes the name configured in the Shelly device's
web page.</li>
<li>A 10-minute timer checks if the device has reported in that
time.</li>
</ul>
<h3>Added</h3>
<ul>
<li>[matterbridgeDevice]: Added all clusters for airQualitySensor:
CarbonMonoxideConcentrationMeasurement,
CarbonDioxideConcentrationMeasurement,
NitrogenDioxideConcentrationMeasurement,
OzoneConcentrationMeasurement,
FormaldehydeConcentrationMeasurement,
Pm1ConcentrationMeasurement,
Pm25ConcentrationMeasurement,
Pm10ConcentrationMeasurement,
RadonConcentrationMeasurement,</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
<p>... (truncated)</p>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e0aa39cb1f64613bacc76c247c50fb3ced729af7"><code>e0aa39c</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/59">#59</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/09a312f6aca99fcec860a996db8ec9f9156f321c"><code>09a312f</code></a>
Release 1.3.4</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c843e53cae923adf72ce176d6ea2c2c0b0c8de90"><code>c843e53</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/58">#58</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/06c9fe57ab91d2482947fb3f70e21c000b40fcaa"><code>06c9fe5</code></a>
Release 1.3.3</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c2d93b10d6c030290d7a8ff525a8319e454dcf48"><code>c2d93b1</code></a>
Changed error mode plugin behaviour</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3d87ffb8ef296bc83c3032280dcf21f14ef6e9d4"><code>3d87ffb</code></a>
chore: Add migrationV8.txt to .gitignore</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f6fd0a8840b37120d04aabd328a59ceadaeed9cd"><code>f6fd0a8</code></a>
chore: Update matter-history to latest version</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/ac38eb9e863a16161a012288280a3d9ac3845198"><code>ac38eb9</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/56">#56</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1c24ebf432efafa1640f0cfc4ebbb11d83d8b2fd"><code>1c24ebf</code></a>
Update matterbridgePlatform</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c8a0c3e156f40af16d3d92b33add97314a8926de"><code>c8a0c3e</code></a>
Update matterbridgePlatform</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.1...1.3.4">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.1&new-version=1.3.4)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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