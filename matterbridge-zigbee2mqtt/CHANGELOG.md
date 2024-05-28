Changes in this Release

<details><summary>301eb74 chore: bump matterbridge from 1.2.17 to 1.2.18 in /matterbridge-zigbee2mqtt (#20)</summary>
chore: bump matterbridge from 1.2.17 to 1.2.18 in /matterbridge-zigbee2mqtt (#20)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.2.17
to 1.2.18.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.2.18</h2>
<h2>[1.2.18] - 2024-05-28</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridgeDevice]: bridgedNode and powerSource device types as
conformance to Matter 1.3</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed /api/settings error after resetting
commissioning server</li>
<li>[matterbridge]: Added error message and clean shutdown when
WebSocketServer or ExpressServer ports are already in use</li>
</ul>
<h3>Added</h3>
<ul>
<li>[frontend]: Added a dropdown menu in Add Remove plugin to select the
plugins</li>
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
<h2>[1.2.18] - 2024-05-28</h2>
<h3>Changed</h3>
<ul>
<li>[matterbridgeDevice]: bridgedNode and powerSource device types as
conformance to Matter 1.3</li>
</ul>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed /api/settings error after resetting
commissioning server</li>
<li>[matterbridge]: Added error message and clean shutdown when
WebSocketServer or ExpressServer ports are already in use</li>
</ul>
<h3>Added</h3>
<ul>
<li>[frontend]: Added a dropdown menu in Add Remove plugin to select the
plugins</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/2d995bacac97c4496fc4196503f000908c7297c3"><code>2d995ba</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/33">#33</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/14931132926a89f358e39f1e20efe21aa5cfb205"><code>1493113</code></a>
Release candidate 1.2.18</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4b1e570dc3f4806764a39768792e3fda913b1811"><code>4b1e570</code></a>
Release candidate 1.2.18</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/5d61b93276df23a8e3c01188f31ca6fa34e58f29"><code>5d61b93</code></a>
Fixed bug in drop down list</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/f353168efca968b8418b983a0982c1e749b0fe2c"><code>f353168</code></a>
Added error message and clean shutdown when WebSocketServer or
ExpressServer ...</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/b9d8925c0f21ec163dde50dd5cebc6baedcff931"><code>b9d8925</code></a>
Added error listener for port already in use</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/e0a02bc116f2f22269747a0d26653d94bd28d36f"><code>e0a02bc</code></a>
Added a dropdown menu to Add Remove plugin to select the plugins</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/772b61a3cfca9e5646c313ef3850b1a957444126"><code>772b61a</code></a>
Added a dropdown menu to Add Remove plugin</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/75cb90b89a599b802315b69d0cb4773f52b2c2ae"><code>75cb90b</code></a>
Prerelease 1.2.18</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/80b0318ef4abcfca3282962b988a4d464f28c8d8"><code>80b0318</code></a>
Fixed error /api/settings after resetting commissioning server</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.2.17...1.2.18">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.2.17&new-version=1.2.18)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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