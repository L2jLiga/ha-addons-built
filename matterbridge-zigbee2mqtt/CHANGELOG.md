Changes in this Release

<details><summary>d187040 chore: bump matterbridge from 1.4.3 to 1.5.0 in /matterbridge-zigbee2mqtt (#60)</summary>
chore: bump matterbridge from 1.4.3 to 1.5.0 in /matterbridge-zigbee2mqtt (#60)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.4.3
to 1.5.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.5.0</h2>
<h2>[1.5.0] - 2024-08-27</h2>
<h3>Breaking Changes</h3>
<ul>
<li>[-bridge -childbridge]: You don't need anymore to add the parmeter
-bridge or -childbridge on the command line or systemctl configuration
or docker command: the default is bridge mode and if no parameter is
added, Matterbridge uses the settings from the frontend that are
saved.</li>
<li>[-logger]: You don't need anymore to add the parmeter -logger
[level]: the default is info and if no parameter is added, Matterbridge
uses the settings from the frontend that are saved.</li>
<li>[-filelogger]: You don't need anymore to add the parmeter
-filelogger: the default is false and if no parameter is added,
Matterbridge uses the settings from the frontend that are saved.</li>
<li>[-matterlogger]: You don't need anymore to add the parmeter
-matterlogger [level]: the default is info and if no parameter is added,
Matterbridge uses the settings from the frontend that are saved.</li>
<li>[-matterfilelogger]: You don't need anymore to add the parmeter
-matterfilelogger: the default is false and if no parameter is added,
Matterbridge uses the settings from the frontend that are saved.</li>
</ul>
<h3>Breaking Changes for developers</h3>
<ul>
<li>please read this <a
href="https://github.com/Luligu/matterbridge/blob/main/README-DEV.md">Development
guide lines</a></li>
</ul>
<h3>Added</h3>
<ul>
<li>[frontend]: Added menu item &quot;Update&quot;.</li>
<li>[frontend]: Added menu item &quot;Restart&quot;.</li>
<li>[frontend]: Added menu item &quot;Shutdown&quot;.</li>
<li>[frontend]: Added menu item &quot;Download&quot;.</li>
<li>[frontend]: Added menu item &quot;Backup&quot;.</li>
<li>[frontend]: Added menu item &quot;Unregister all devices&quot; with
a confirmation dialog.</li>
<li>[frontend]: Added menu item &quot;Reset commissioning&quot; with a
confirmation dialog.</li>
<li>[frontend]: Added menu item &quot;Factory reset&quot; with a
confirmation dialog.</li>
</ul>
<h3>Changed</h3>
<ul>
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
<h2>[1.5.0] - 2024-08-27</h2>
<h3>Breaking Changes</h3>
<ul>
<li>[-bridge -childbridge]: You don't need anymore to add the parmeter
-bridge or -childbridge on the command line or systemctl configuration
or docker command: the default is bridge mode and if no parameter is
added, Matterbridge uses the settings from the frontend that are
saved.</li>
<li>[-logger]: You don't need anymore to add the parmeter -logger
[level]: the default is info and if no parameter is added, Matterbridge
uses the settings from the frontend that are saved.</li>
<li>[-filelogger]: You don't need anymore to add the parmeter
-filelogger: the default is false and if no parameter is added,
Matterbridge uses the settings from the frontend that are saved.</li>
<li>[-matterlogger]: You don't need anymore to add the parmeter
-matterlogger [level]: the default is info and if no parameter is added,
Matterbridge uses the settings from the frontend that are saved.</li>
<li>[-matterfilelogger]: You don't need anymore to add the parmeter
-matterfilelogger: the default is false and if no parameter is added,
Matterbridge uses the settings from the frontend that are saved.</li>
</ul>
<h3>Breaking Changes for developers</h3>
<ul>
<li>please read this <a
href="https://github.com/Luligu/matterbridge/blob/main/README-DEV.md">Development
guide lines</a></li>
</ul>
<h3>Added</h3>
<ul>
<li>[frontend]: Added menu item &quot;Update&quot;.</li>
<li>[frontend]: Added menu item &quot;Restart&quot;.</li>
<li>[frontend]: Added menu item &quot;Shutdown&quot;.</li>
<li>[frontend]: Added menu item &quot;Download&quot;.</li>
<li>[frontend]: Added menu item &quot;Backup&quot;.</li>
<li>[frontend]: Added menu item &quot;Unregister all devices&quot; with
a confirmation dialog.</li>
<li>[frontend]: Added menu item &quot;Reset commissioning&quot; with a
confirmation dialog.</li>
<li>[frontend]: Added menu item &quot;Factory reset&quot; with a
confirmation dialog.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update dependencies.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/85131cff7745ac63fd9dfb075c717bb94f061512"><code>85131cf</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/111">#111</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/ef2745296379206b0b24a133205d90fa467e2f15"><code>ef27452</code></a>
Release 1.5.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/a76f9fc86cc7c3c9d5ca466149fbaabda497708e"><code>a76f9fc</code></a>
Refactor README.md</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1479debf3d75e360fd936f489d0fdf1343f07f79"><code>1479deb</code></a>
Release 1.5.0</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/3456b4ab7a805f261bbce4aa60f8eb32964eb19d"><code>3456b4a</code></a>
Refactor README.md</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/bd0c7d288335be68cdb0bc5bdfc3a6085ede5690"><code>bd0c7d2</code></a>
Refactor README.md</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/965daa5e404eadc34447f1377603057ce4ef51a1"><code>965daa5</code></a>
Add ipv4address and ipv6address parameters</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/dc1e5dee60e8fad83ac97162c87b2a183bc6f950"><code>dc1e5de</code></a>
1.5.0-beta10</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4cc093e8aa7492cd4c269d533a651862ebd4e976"><code>4cc093e</code></a>
1.5.0-beta10</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/35ef935ed6038f5f291403c530dde59fc4cdc23a"><code>35ef935</code></a>
1.5.0-beta10</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.4.3...1.5.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.4.3&new-version=1.5.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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