Changes in this Release

<details><summary>d2cc077 chore: bump matterbridge from 1.3.6 to 1.3.8 in /matterbridge-zigbee2mqtt (#37)</summary>
chore: bump matterbridge from 1.3.6 to 1.3.8 in /matterbridge-zigbee2mqtt (#37)

Bumps [matterbridge](https://github.com/Luligu/matterbridge) from 1.3.6
to 1.3.8.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge/releases">matterbridge's
releases</a>.</em></p>
<blockquote>
<h2>Release 1.3.8</h2>
<h2>[1.3.8] - 2024-07-01</h2>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed crash in childbridge mode</li>
</ul>
<!-- raw HTML omitted -->
<h2>Release 1.3.7</h2>
<h2>[1.3.7] - 2024-06-30</h2>
<h3>Added</h3>
<ul>
<li>[matter.js]: Added -mdnsinterface command line parameter to limit
the MdnsBroadcaster to a single interface (e.g. matterbridge -bridge
-mdnsinterface eth0). Matterbridge will validate the given interface and
log a message if the interface is not available and will use all
available interfaces.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[dependencies]: Update dependencies.</li>
<li>[dependencies]: Update eslint to 9.6.0.</li>
<li>[dependencies]: Update matter.js to 0.9.3.</li>
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
<h2>[1.3.8] - 2024-07-01</h2>
<h3>Fixed</h3>
<ul>
<li>[matterbridge]: Fixed crash in childbridge mode</li>
</ul>
<!-- raw HTML omitted -->
<h2>[1.3.7] - 2024-06-30</h2>
<h3>Added</h3>
<ul>
<li>[matter.js]: Added -mdnsinterface command line parameter to limit
the MdnsBroadcaster to a single interface (e.g. matterbridge -bridge
-mdnsinterface eth0). Matterbridge will validate the given interface and
log a message if the interface is not available and will use all
available interfaces.</li>
</ul>
<h3>Changed</h3>
<ul>
<li>[dependencies]: Update dependencies.</li>
<li>[dependencies]: Update eslint to 9.6.0.</li>
<li>[dependencies]: Update matter.js to 0.9.3.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8651e7e29a305de51d6dc681cc7ef11a0e540006"><code>8651e7e</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/73">#73</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/eb9344bd2557f7ab5c35bfaab598071e83360f85"><code>eb9344b</code></a>
Release 1.3.8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/5a32dbb574639212b98d39dae11e66dd1fdbd452"><code>5a32dbb</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/72">#72</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8d402e5c5dbb2d74c834ef26d641f5323e32dd19"><code>8d402e5</code></a>
Fixed crash in childbridge mode</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/5d10b7f04b15633d0db9581f4422fccdbc6b01ed"><code>5d10b7f</code></a>
MatterbridgeV8</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/19c4ec1b4bb8f9f806db3a2d3e658f07e4698c97"><code>19c4ec1</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge/issues/70">#70</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/583dfa33d2f23f1b522d49b0ba03a8205ac80f5b"><code>583dfa3</code></a>
Release 1.3.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/8a180cb5531ecede0c663617096617931bb4997e"><code>8a180cb</code></a>
Release 1.3.7</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/73f710fbadb66f2299f99972c9ddf646a2883a0c"><code>73f710f</code></a>
Added -mdnsinterface command line parameter to limit the
MdnsBroadcaster</li>
<li><a
href="https://github.com/Luligu/matterbridge/commit/638f52d269dc3a3ebf00bd3e63ea997987a31d92"><code>638f52d</code></a>
Release 1.3.7</li>
<li>Additional commits viewable in <a
href="https://github.com/Luligu/matterbridge/compare/1.3.6...1.3.8">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge&package-manager=npm_and_yarn&previous-version=1.3.6&new-version=1.3.8)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>3759f06 chore: bump matterbridge-zigbee2mqtt from 2.1.3 to 2.1.4 in /matterbridge-zigbee2mqtt (#36)</summary>
chore: bump matterbridge-zigbee2mqtt from 2.1.3 to 2.1.4 in /matterbridge-zigbee2mqtt (#36)

Bumps
[matterbridge-zigbee2mqtt](https://github.com/Luligu/matterbridge-zigbee2mqtt)
from 2.1.3 to 2.1.4.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/releases">matterbridge-zigbee2mqtt's
releases</a>.</em></p>
<blockquote>
<h2>Release 2.1.4</h2>
<h2>[2.1.4] - 2024-06-30</h2>
<h3>Changed</h3>
<ul>
<li>[dependencies]: Update dependencies.</li>
<li>[dependencies]: Update eslint to 9.6.0.</li>
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
<h2>[2.1.4] - 2024-06-30</h2>
<h3>Changed</h3>
<ul>
<li>[dependencies]: Update dependencies.</li>
<li>[dependencies]: Update eslint to 9.6.0.</li>
</ul>
<!-- raw HTML omitted -->
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c1cb8878f700c874804d021b22e3f137a692d371"><code>c1cb887</code></a>
Merge pull request <a
href="https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/issues/36">#36</a>
from Luligu/dev</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/345495e423ea1d622345acff137bb920050e0e54"><code>345495e</code></a>
Release 2.1.4</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/8d17b1557421db3b31e6d27c7dcb7e2041ccea4b"><code>8d17b15</code></a>
Release 2.1.4</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c467f12cbb1b52d83fa70e4e85bff079b93ab3d3"><code>c467f12</code></a>
Release 2.1.4</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/c9eea581004568700599f18ca6978390c2e8d801"><code>c9eea58</code></a>
chore: Update matterbridge-zigbee2mqtt schema description for
switchList</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/8ec18c7fecc059e827329ecaedce3c1b04a9bb47"><code>8ec18c7</code></a>
chore: Update readme and add star and sponsor request</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/37373acc15dd8c074821363d5245b6a76ae45700"><code>37373ac</code></a>
chore: Update Matterbridge zigbee2mqtt plugin changelog</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/0a83c8626a5f22b86950c22978445725f78d5a79"><code>0a83c86</code></a>
Added separate log for start errors</li>
<li><a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/commit/abc7ab9307c2a1c0e65d3907952ed6c5a7a1724c"><code>abc7ab9</code></a>
chore: Update readme</li>
<li>See full diff in <a
href="https://github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.1.3...2.1.4">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=matterbridge-zigbee2mqtt&package-manager=npm_and_yarn&previous-version=2.1.3&new-version=2.1.4)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>9d9d5fa chore: bump docker/build-push-action from 5.3.0 to 6.2.0 (#35)</summary>
chore: bump docker/build-push-action from 5.3.0 to 6.2.0 (#35)

Bumps
[docker/build-push-action](https://github.com/docker/build-push-action)
from 5.3.0 to 6.2.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/docker/build-push-action/releases">docker/build-push-action's
releases</a>.</em></p>
<blockquote>
<h2>v6.2.0</h2>
<ul>
<li>Use default retention days for build export artifact by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1153">docker/build-push-action#1153</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.27.0 to 0.28.0 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1158">docker/build-push-action#1158</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.1.0...v6.2.0">https://github.com/docker/build-push-action/compare/v6.1.0...v6.2.0</a></p>
<h2>v6.1.0</h2>
<ul>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.26.2 to 0.27.0 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1149">docker/build-push-action#1149</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.0.2...v6.1.0">https://github.com/docker/build-push-action/compare/v6.0.2...v6.1.0</a></p>
<h2>v6.0.2</h2>
<ul>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.26.1 to 0.26.2 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1147">docker/build-push-action#1147</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.0.1...v6.0.2">https://github.com/docker/build-push-action/compare/v6.0.1...v6.0.2</a></p>
<h2>v6.0.1</h2>
<ul>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.26.0 to 0.26.1 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1142">docker/build-push-action#1142</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.0.0...v6.0.1">https://github.com/docker/build-push-action/compare/v6.0.0...v6.0.1</a></p>
<h2>v6.0.0</h2>
<ul>
<li>Export build record and generate <a
href="https://docs.docker.com/build/ci/github-actions/build-summary/">build
summary</a> by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1120">docker/build-push-action#1120</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.24.0 to 0.26.0 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1132">docker/build-push-action#1132</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1136">docker/build-push-action#1136</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1138">docker/build-push-action#1138</a></li>
<li>Bump braces from 3.0.2 to 3.0.3 in <a
href="https://redirect.github.com/docker/build-push-action/pull/1137">docker/build-push-action#1137</a></li>
</ul>
<blockquote>
<p>[!NOTE]
This major release adds support for generating <a
href="https://docs.docker.com/build/ci/github-actions/build-summary/">Build
summary</a> and exporting build record for your build. You can disable
this feature by setting <a
href="https://docs.docker.com/build/ci/github-actions/build-summary/#disable-job-summary">
<code>DOCKER_BUILD_NO_SUMMARY: true</code> environment variable in your
workflow</a>.</p>
</blockquote>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v5.4.0...v6.0.0">https://github.com/docker/build-push-action/compare/v5.4.0...v6.0.0</a></p>
<h2>v5.4.0</h2>
<ul>
<li>Show builder information before building by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1128">docker/build-push-action#1128</a></li>
<li>Handle attestations correctly with provenance and sbom inputs by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1086">docker/build-push-action#1086</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.19.0 to 0.24.0 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1088">docker/build-push-action#1088</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1105">docker/build-push-action#1105</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1121">docker/build-push-action#1121</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1127">docker/build-push-action#1127</a></li>
<li>Bump undici from 5.28.3 to 5.28.4 in <a
href="https://redirect.github.com/docker/build-push-action/pull/1090">docker/build-push-action#1090</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v5.3.0...v5.4.0">https://github.com/docker/build-push-action/compare/v5.3.0...v5.4.0</a></p>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/docker/build-push-action/commit/15560696de535e4014efeff63c48f16952e52dd1"><code>1556069</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1158">#1158</a>
from docker/dependabot/npm_and_yarn/docker/actions-t...</li>
<li><a
href="https://github.com/docker/build-push-action/commit/57e1d34ac3097d9f17c4d3cdbcb8609bf1838864"><code>57e1d34</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/build-push-action/commit/309982ebc95a96ea0ab37ce98b3b2a9e1a2497b4"><code>309982e</code></a>
chore(deps): Bump <code>@​docker/actions-toolkit</code> from 0.27.0 to
0.28.0</li>
<li><a
href="https://github.com/docker/build-push-action/commit/9476c25b2a7a4ab5171cd8f4658468d19b69d7ae"><code>9476c25</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1153">#1153</a>
from crazy-max/export-retention</li>
<li><a
href="https://github.com/docker/build-push-action/commit/97be5a4928e7b54d4f6440c616a9180d0193e9c4"><code>97be5a4</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/build-push-action/commit/9cac6c8ea04b693525a33651136a4114582823b6"><code>9cac6c8</code></a>
use default retention days for build export artifact</li>
<li><a
href="https://github.com/docker/build-push-action/commit/31159d49c0d4756269a0940a750801a1ea5d7003"><code>31159d4</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1149">#1149</a>
from docker/dependabot/npm_and_yarn/docker/actions-t...</li>
<li><a
href="https://github.com/docker/build-push-action/commit/07e1c3e148c1973f78a15cef24eae4371e57280d"><code>07e1c3e</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/build-push-action/commit/f7febd621d13a78cf2751da16b38233f0e819581"><code>f7febd6</code></a>
chore(deps): Bump <code>@​docker/actions-toolkit</code> from 0.26.2 to
0.27.0</li>
<li><a
href="https://github.com/docker/build-push-action/commit/f6010ea70151369b06f0194be1051fbbdff851b2"><code>f6010ea</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1147">#1147</a>
from docker/dependabot/npm_and_yarn/docker/actions-t...</li>
<li>Additional commits viewable in <a
href="https://github.com/docker/build-push-action/compare/v5.3.0...v6.2.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=docker/build-push-action&package-manager=github_actions&previous-version=5.3.0&new-version=6.2.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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