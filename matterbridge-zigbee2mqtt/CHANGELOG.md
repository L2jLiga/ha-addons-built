Changes in this Release

<details><summary>75a66e2 chore: bump matterbridge from 1.3.5 to 1.3.6 in /matterbridge-zigbee2mqtt (#34)</summary>
chore: bump matterbridge from 1.3.5 to 1.3.6 in /matterbridge-zigbee2mqtt (#34)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.5
to 1.3.6.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.6</h2>
<h2>[1.3.6] - 2024-06-28</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Unified the http server port for the frontend and
the WebSockerServer.</li>
<li>[matterbridge]: Unified the https server port for the frontend and
the WebSockerServer.</li>
<li>[certificates]: The certificates for https connections are imported
from the directory ~/.matterbridge/certs with these names: cert.pem,
key.pem and ca.pem (optional). Use the -ssl command line parameter to
activate https for both frontend and WebSocketServer.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed exports</li>
<li>[matterbridgeDevice]: Fixed ElectricalEnergyMeasurement and
ElectricalPowerMeasurement</li>
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
<h2>[1.3.6] - 2024-06-28</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Unified the http server port for the frontend and
the WebSockerServer.</li>
<li>[matterbridge]: Unified the https server port for the frontend and
the WebSockerServer.</li>
<li>[certificates]: The certificates for https connections are imported
from the directory ~/.matterbridge/certs with these names: cert.pem,
key.pem and ca.pem (optional). Use the -ssl command line parameter to
activate https for both frontend and WebSocketServer.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed exports</li>
<li>[matterbridgeDevice]: Fixed ElectricalEnergyMeasurement and
ElectricalPowerMeasurement</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/182dc6d50f1aa8731e37f98226d464aa9c9d9e73"><code>182dc6d</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/68">#68</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/fd5621c6d5783c742c7285b3dc97b72151ca20f2"><code>fd5621c</code></a>
Release 1.3.6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f05047429752e33c7197047792ee6d0cdd0e6dd4"><code>f050474</code></a>
Release 1.3.6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/edccde525cc6db9860a5c7fa60ef24a7eaee33fd"><code>edccde5</code></a>
Release 1.3.6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/d9be2cb667c48d243c7ee067a727c0a583b3827b"><code>d9be2cb</code></a>
Release 1.3.6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4eeba3d6f8dadf09760a7dc675cac8ff528acd25"><code>4eeba3d</code></a>
Release 1.3.6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1230f46a38531b5473cf6a6bc38b2633e655ef1e"><code>1230f46</code></a>
Unified the https server port for the frontend and the
WebSockerServer</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c96c04a1163d24ffb60b536288a82177ac053fc4"><code>c96c04a</code></a>
Unified the frontend and the WebSockerServer on the same port of the
http server</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/7d8276c207f5f67a8c6fe41e83ee1ce47529fbdf"><code>7d8276c</code></a>
Fixed ElectricalEnergyMeasurement and ElectricalPowerMeasurement</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.5...1.3.6">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.5&new-version=1.3.6)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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