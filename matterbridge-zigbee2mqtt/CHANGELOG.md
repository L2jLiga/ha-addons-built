Changes in this Release

<details><summary>7d30a0e chore: bump matterbridge from 2.1.4 to 2.1.5 in /matterbridge-zigbee2mqtt (#109)</summary>
chore: bump matterbridge from 2.1.4 to 2.1.5 in /matterbridge-zigbee2mqtt (#109)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 2.1.4
to 2.1.5.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.5</h2>
<h3>Breaking Changes</h3>
<p>Starting from v. 2.0.0, Matterbridge is running only in mode edge (no
parameter needed and no badge in the frontend).</p>
<p>Starting from v. 2.1.0, the legacy old api of matter.js have been
completely removed from Matterbridge and from all plugins.</p>
<p>For this reason there is no compatibility with the old versions of
the plugins.</p>
<p>You need to update all plugins you use and Matterbridge in the same
moment.</p>
<p>I suggest to first update all plugins without restarting and then to
update Matterbridge so when it restarts, all versions will be the
latest.</p>
<p>If you use docker, all plugins are already installed in the image so
you just need to pull the new image.</p>
<p>Compatibility list:
matterbridge-shelly v. 1.1.5
matterbridge-zigbee2mqtt v. 2.4.4
matterbridge-somfy-tahoma v. 1.2.3
matterbridge-hass v. 0.0.8</p>
<h2>[2.1.5] - 2025-02-11</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Frontend v.2.4.1.</li>
<li>[frontend]: Optimized rendering of all pages.</li>
<li>[frontend]: Added cpuUsed, rss and heapUsed to
SystemInformation.</li>
<li>[frontend]: Added UiProvider.</li>
<li>[frontend]: Added wssSendCpuUpdate, wssSendMemoryUpdate and
wssSendSnackbarMessage.</li>
<li>[docker]: Added health check to docker images. See README-DOCKER.md
with the updated configuration.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Calls getNpmPackageVersion() instead of npm to get
latest version to optimize memory and cpu usage.</li>
<li>[matterbridge]: Memory optimization on MatterbridgeEndpoint.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Refactor shutdown sequences for reset and factory
reset.</li>
<li>[matterbridge]: Refactor reset devices adding a wait of 1 sec to
allow matter to deliver all messages before shutting down.</li>
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
<h2>[2.1.5] - 2025-02-11</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Frontend v.2.4.1.</li>
<li>[frontend]: Optimized rendering of all pages.</li>
<li>[frontend]: Added cpuUsed, rss and heapUsed to
SystemInformation.</li>
<li>[frontend]: Added UiProvider.</li>
<li>[frontend]: Added wssSendCpuUpdate, wssSendMemoryUpdate and
wssSendSnackbarMessage.</li>
<li>[docker]: Added health check to docker images. See README-DOCKER.md
with the updated configuration.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[matterbridge]: Calls getNpmPackageVersion() instead of npm to get
latest version to optimize memory and cpu usage.</li>
<li>[matterbridge]: Memory optimization on MatterbridgeEndpoint.</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Refactor shutdown sequences for reset and factory
reset.</li>
<li>[matterbridge]: Refactor reset devices adding a wait of 1 sec to
allow matter to deliver all messages before shutting down.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/338f34cf7abcbf2166f4c12cb16b746f902ad360"><code>338f34c</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/221">#221</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a20618a4f5d2641a936dd5feeee7ba4bc6ce6132"><code>a20618a</code></a>
Release 2.1.5</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/41be055bd82ba53560028690e3f88aa5759249d5"><code>41be055</code></a>
Add curl installation to Dockerfile for docker health on latest</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/6f25a2aef66785e95008bd524cf699bf9e06da81"><code>6f25a2a</code></a>
Add curl installation to Dockerfile for docker health</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/998ccdadc6313a6ab74471662141266c6b5099d5"><code>998ccda</code></a>
Dev 2.1.5-dev.8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4f4566117c83af24ba5afc05b81bc4d19e7e19cf"><code>4f45661</code></a>
Set logger global callback to loger and matterlogger level</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/088ba1eabdb9a946b953d51a417189b3c4455717"><code>088ba1e</code></a>
Dev 2.1.5-dev.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/47d0ae79b3d77d5e7438959a313b1630d3639d9f"><code>47d0ae7</code></a>
Dev 2.1.5-dev.6</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/336ef647310c4b4d97f14efefc88f0adf7a53768"><code>336ef64</code></a>
Frontend 2.4.1</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/22f095d3729e4d95730e2f84bbdc607fc9a26a15"><code>22f095d</code></a>
Dev 2.1.5-dev.5</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/2.1.4...2.1.5">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=2.1.4&new-version=2.1.5)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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