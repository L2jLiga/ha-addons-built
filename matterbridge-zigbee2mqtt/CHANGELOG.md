Changes in this Release

<details><summary>d3d454a chore: bump matterbridge from 2.1.3 to 2.1.4 in /matterbridge-zigbee2mqtt (#108)</summary>
chore: bump matterbridge from 2.1.3 to 2.1.4 in /matterbridge-zigbee2mqtt (#108)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 2.1.3
to 2.1.4.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.4</h2>
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
<h2>[2.1.4] - 2025-02-07</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Added memorycheck before cleanup.</li>
<li>[platform]: Added a check for not latin characters.</li>
<li>[platform]: Added a check for already registered device names.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter.js to 0.12.3.</li>
<li>[matter.js]: Since matter.js storage cannot properly encode non
latin names, they are encoded before passing them to matter.js.</li>
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
<h2>[2.1.4] - 2025-02-07</h2>
<h3>Added</h3>
<ul>
<li>[frontend]: Added memorycheck before cleanup.</li>
<li>[platform]: Added a check for not latin characters.</li>
<li>[platform]: Added a check for already registered device names.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[package]: Update matter.js to 0.12.3.</li>
<li>[matter.js]: Since matter.js storage cannot properly encode non
latin names, they are encoded before passing them to matter.js.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/bf3f9be85c57f26b3ca32726d19c47f947963e63"><code>bf3f9be</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/220">#220</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/892efc83c0681d9268e1e5c9dacac6df2e88a786"><code>892efc8</code></a>
Release 2.1.4</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/c7891cf87069b047c8a5f281a4840133ad0bb641"><code>c7891cf</code></a>
Update README-DOCKER.md to specify user directory paths for Docker
volumes</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/61f91f2be786b2bbdca4cf734d03f421c0571306"><code>61f91f2</code></a>
Release check for non-Latin character in device name</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/60faa0d2499f0f35e1a1127c56650c342126dae9"><code>60faa0d</code></a>
Add getNpmPackageVersion utility function and corresponding tests</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/4fd2ad1289ddcebcb8ffac2d6c1e2c327971d58c"><code>4fd2ad1</code></a>
Dev 2.1.4-dev.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/fed67f7aed7004f505f752e09da6626949275fe2"><code>fed67f7</code></a>
Dev 2.1.4-dev.2</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/1b7edd1b1709b9dddbd34cab2f4b72b11d38c740"><code>1b7edd1</code></a>
Add checkNotLatinCharacters in Endpoint constructor.</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/36b37ee3baf66c62e1ba2720f1f50fcf630ca29b"><code>36b37ee</code></a>
Jest tests</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/007be9c549b0b9cda4bb73737bee7a64708ef223"><code>007be9c</code></a>
Enhance MatterbridgePlatform: add hasDeviceName</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/2.1.3...2.1.4">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=2.1.3&new-version=2.1.4)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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