Changes in this Release

<details><summary>f740dcc chore: bump docker/setup-buildx-action from 3.3.0 to 3.6.1 (#50)</summary>
chore: bump docker/setup-buildx-action from 3.3.0 to 3.6.1 (#50)

Bumps
[docker/setup-buildx-action](https://github.com/docker/setup-buildx-action)
from 3.3.0 to 3.6.1.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/docker/setup-buildx-action/releases">docker/setup-buildx-action's
releases</a>.</em></p>
<blockquote>
<h2>v3.6.1</h2>
<ul>
<li>Check for malformed docker context by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/setup-buildx-action/pull/347">docker/setup-buildx-action#347</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/setup-buildx-action/compare/v3.6.0...v3.6.1">https://github.com/docker/setup-buildx-action/compare/v3.6.0...v3.6.1</a></p>
<h2>v3.6.0</h2>
<ul>
<li>Create temp docker context if default one has TLS data loaded before
creating a container builder by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/setup-buildx-action/pull/341">docker/setup-buildx-action#341</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/setup-buildx-action/compare/v3.5.0...v3.6.0">https://github.com/docker/setup-buildx-action/compare/v3.5.0...v3.6.0</a></p>
<h2>v3.5.0</h2>
<ul>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.31.0 to 0.35.0 in
<a
href="https://redirect.github.com/docker/setup-buildx-action/pull/340">docker/setup-buildx-action#340</a>
<a
href="https://redirect.github.com/docker/setup-buildx-action/pull/344">docker/setup-buildx-action#344</a>
<a
href="https://redirect.github.com/docker/setup-buildx-action/pull/345">docker/setup-buildx-action#345</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/setup-buildx-action/compare/v3.4.0...v3.5.0">https://github.com/docker/setup-buildx-action/compare/v3.4.0...v3.5.0</a></p>
<h2>v3.4.0</h2>
<ul>
<li>Throw error message instead of exit code by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/setup-buildx-action/pull/315">docker/setup-buildx-action#315</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.20.0 to 0.31.0 in
<a
href="https://redirect.github.com/docker/setup-buildx-action/pull/321">docker/setup-buildx-action#321</a>
<a
href="https://redirect.github.com/docker/setup-buildx-action/pull/338">docker/setup-buildx-action#338</a></li>
<li>Bump braces from 3.0.2 to 3.0.3 in <a
href="https://redirect.github.com/docker/setup-buildx-action/pull/329">docker/setup-buildx-action#329</a></li>
<li>Bump undici from 5.28.3 to 5.28.4 in <a
href="https://redirect.github.com/docker/setup-buildx-action/pull/312">docker/setup-buildx-action#312</a></li>
<li>Bump uuid from 9.0.1 to 10.0.0 in <a
href="https://redirect.github.com/docker/setup-buildx-action/pull/326">docker/setup-buildx-action#326</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/setup-buildx-action/compare/v3.3.0...v3.4.0">https://github.com/docker/setup-buildx-action/compare/v3.3.0...v3.4.0</a></p>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/988b5a0280414f521da01fcc63a27aeeb4b104db"><code>988b5a0</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/setup-buildx-action/issues/347">#347</a>
from crazy-max/skip-malformed-context</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/2c215620b8bfc319fa4c45228e004e292677fd33"><code>2c21562</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/3382292cd51ea1cda5852caf2e65d8e7b3f1c2ca"><code>3382292</code></a>
check for malformed docker context</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/3d68780484996aa9d417bb9016193885cdf1f299"><code>3d68780</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/setup-buildx-action/issues/341">#341</a>
from crazy-max/docker-context-tls</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/d069e98648dcd5f11d3f726983a778dcf30aeca0"><code>d069e98</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/8b850f86dc46ba7eb11e02c7d3db66aeb2b0f022"><code>8b850f8</code></a>
create docker context if default one has TLS data loaded</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/aa33708b10e362ff993539393ff100fa93ed6a27"><code>aa33708</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/setup-buildx-action/issues/345">#345</a>
from docker/dependabot/npm_and_yarn/docker/actions-to...</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/2d99e3412d2dd2b9c7e2fcca49d01b924c1ab21c"><code>2d99e34</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/4dab43650b8b8c84737d78c3cc36b01bb089fd0c"><code>4dab436</code></a>
build(deps): bump <code>@​docker/actions-toolkit</code> from 0.34.0 to
0.35.0</li>
<li><a
href="https://github.com/docker/setup-buildx-action/commit/49a04d68900b1d260da9b3f06f52638d56cd8ad1"><code>49a04d6</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/setup-buildx-action/issues/344">#344</a>
from docker/dependabot/npm_and_yarn/docker/actions-to...</li>
<li>Additional commits viewable in <a
href="https://github.com/docker/setup-buildx-action/compare/v3.3.0...v3.6.1">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=docker/setup-buildx-action&package-manager=github_actions&previous-version=3.3.0&new-version=3.6.1)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>5ea23df chore: bump docker/login-action from 3.2.0 to 3.3.0 (#51)</summary>
chore: bump docker/login-action from 3.2.0 to 3.3.0 (#51)

Bumps [docker/login-action](https://github.com/docker/login-action) from
3.2.0 to 3.3.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/docker/login-action/releases">docker/login-action's
releases</a>.</em></p>
<blockquote>
<h2>v3.3.0</h2>
<ul>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.24.0 to 0.35.0 in
<a
href="https://redirect.github.com/docker/login-action/pull/754">docker/login-action#754</a></li>
<li>Bump https-proxy-agent from 7.0.4 to 7.0.5 in <a
href="https://redirect.github.com/docker/login-action/pull/741">docker/login-action#741</a></li>
<li>Bump braces from 3.0.2 to 3.0.3 in <a
href="https://redirect.github.com/docker/login-action/pull/730">docker/login-action#730</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/login-action/compare/v3.2.0...v3.3.0">https://github.com/docker/login-action/compare/v3.2.0...v3.3.0</a></p>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/docker/login-action/commit/9780b0c442fbb1117ed29e0efdff1e18412f7567"><code>9780b0c</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/741">#741</a>
from docker/dependabot/npm_and_yarn/proxy-agent-depen...</li>
<li><a
href="https://github.com/docker/login-action/commit/2fa130caf4961ac37a295018c0f97fa9da3e1f52"><code>2fa130c</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/login-action/commit/5e87b2aca7d49b75a206090eca3b79f40316332b"><code>5e87b2a</code></a>
build(deps): bump https-proxy-agent</li>
<li><a
href="https://github.com/docker/login-action/commit/e0394952cebdc98290d4844a810ce80c18a05e48"><code>e039495</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/754">#754</a>
from docker/dependabot/npm_and_yarn/docker/actions-to...</li>
<li><a
href="https://github.com/docker/login-action/commit/9af18aa7d8432fc31be2d1180f4bd68f162efb1c"><code>9af18aa</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/login-action/commit/668190adc5b80f56970e2513a4c8783c3b738c80"><code>668190a</code></a>
switch to Docker exec</li>
<li><a
href="https://github.com/docker/login-action/commit/be5150d9fe8f63dc1e2f68759894be69bac660c3"><code>be5150d</code></a>
build(deps): bump <code>@​docker/actions-toolkit</code> from 0.24.0 to
0.35.0</li>
<li><a
href="https://github.com/docker/login-action/commit/e80ebcad716081acf5e6f0df3180e53a003ee605"><code>e80ebca</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/730">#730</a>
from docker/dependabot/npm_and_yarn/braces-3.0.3</li>
<li><a
href="https://github.com/docker/login-action/commit/75ee3eaf5349e1d9e6aae6b1969b8a30368dd421"><code>75ee3ea</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/733">#733</a>
from docker/dependabot/github_actions/docker/bake-act...</li>
<li><a
href="https://github.com/docker/login-action/commit/793c19c8fc1a0a6e836dc7ff6d64f331d131a3fb"><code>793c19c</code></a>
build(deps): bump docker/bake-action from 4 to 5</li>
<li>Additional commits viewable in <a
href="https://github.com/docker/login-action/compare/v3.2.0...v3.3.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=docker/login-action&package-manager=github_actions&previous-version=3.2.0&new-version=3.3.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>a9acfcb chore: bump docker/build-push-action from 6.2.0 to 6.5.0 (#52)</summary>
chore: bump docker/build-push-action from 6.2.0 to 6.5.0 (#52)

Bumps
[docker/build-push-action](https://github.com/docker/build-push-action)
from 6.2.0 to 6.5.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/docker/build-push-action/releases">docker/build-push-action's
releases</a>.</em></p>
<blockquote>
<h2>v6.5.0</h2>
<ul>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.33.0 to 0.35.0 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1186">docker/build-push-action#1186</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1191">docker/build-push-action#1191</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.4.1...v6.5.0">https://github.com/docker/build-push-action/compare/v6.4.1...v6.5.0</a></p>
<h2>v6.4.1</h2>
<ul>
<li>revert &quot;Set <code>repository</code> and <code>ghtoken</code>
attributes for <a
href="https://docs.docker.com/build/cache/backends/gha/#avoid-github-actions-cache-api-throttling">GitHub
Actions cache backend</a>&quot; by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1183">docker/build-push-action#1183</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.4.0...v6.4.1">https://github.com/docker/build-push-action/compare/v6.4.0...v6.4.1</a></p>
<h2>v6.4.0</h2>
<ul>
<li>Set <code>repository</code> and <code>ghtoken</code> attributes for
<a
href="https://docs.docker.com/build/cache/backends/gha/#avoid-github-actions-cache-api-throttling">GitHub
Actions cache backend</a> by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1133">docker/build-push-action#1133</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.31.0 to 0.33.0 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1179">docker/build-push-action#1179</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.3.0...v6.4.0">https://github.com/docker/build-push-action/compare/v6.3.0...v6.4.0</a></p>
<h2>v6.3.0</h2>
<ul>
<li><code>DOCKER_BUILD_RECORD_UPLOAD</code> environment variable to
enable/disable build record upload by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1172">docker/build-push-action#1172</a></li>
<li><code>DOCKER_BUILD_NO_SUMMARY</code> has been deprecated. Set
<code>DOCKER_BUILD_SUMMARY</code> to <code>false</code> instead by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/build-push-action/pull/1170">docker/build-push-action#1170</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1173">docker/build-push-action#1173</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.28.0 to 0.31.0 in
<a
href="https://redirect.github.com/docker/build-push-action/pull/1171">docker/build-push-action#1171</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1159">docker/build-push-action#1159</a>
<a
href="https://redirect.github.com/docker/build-push-action/pull/1169">docker/build-push-action#1169</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/build-push-action/compare/v6.2.0...v6.3.0">https://github.com/docker/build-push-action/compare/v6.2.0...v6.3.0</a></p>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/docker/build-push-action/commit/5176d81f87c23d6fc96624dfdbcd9f3830bbe445"><code>5176d81</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1191">#1191</a>
from docker/dependabot/npm_and_yarn/docker/actions-t...</li>
<li><a
href="https://github.com/docker/build-push-action/commit/ec10ae8f9620b3ff186577a79d805aba55e6f189"><code>ec10ae8</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/build-push-action/commit/597e8fc4142a1a043ae022afc9184006fc25d448"><code>597e8fc</code></a>
chore(deps): Bump <code>@​docker/actions-toolkit</code> from 0.34.0 to
0.35.0</li>
<li><a
href="https://github.com/docker/build-push-action/commit/e050dfa622d93dfcc095192a984db567cb14f0f0"><code>e050dfa</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1186">#1186</a>
from docker/dependabot/npm_and_yarn/docker/actions-t...</li>
<li><a
href="https://github.com/docker/build-push-action/commit/d1fcdb6ee033b0415f4dc6ce5c6ea4475008f6e7"><code>d1fcdb6</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/build-push-action/commit/a6067b9a1aaf9ff2710b9ddae4948955d83cd3dd"><code>a6067b9</code></a>
chore(deps): Bump <code>@​docker/actions-toolkit</code> from 0.33.0 to
0.34.0</li>
<li><a
href="https://github.com/docker/build-push-action/commit/1ca370b3a9802c92e886402e0dd88098a2533b12"><code>1ca370b</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1183">#1183</a>
from crazy-max/revert-gha-cache-to</li>
<li><a
href="https://github.com/docker/build-push-action/commit/2c95ebed5c303261a63c148b68f4ce3023814acc"><code>2c95ebe</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/build-push-action/commit/d189d0ef33a3269ad4a3c50511f63fb7b6d63809"><code>d189d0e</code></a>
Revert &quot;set repository and ghtoken attributes for gha cache
type&quot;</li>
<li><a
href="https://github.com/docker/build-push-action/commit/a254f8ca60a858f3136a2f1f23a60969f2c402dd"><code>a254f8c</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/build-push-action/issues/1179">#1179</a>
from docker/dependabot/npm_and_yarn/docker/actions-t...</li>
<li>Additional commits viewable in <a
href="https://github.com/docker/build-push-action/compare/v6.2.0...v6.5.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=docker/build-push-action&package-manager=github_actions&previous-version=6.2.0&new-version=6.5.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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

<details><summary>48f4c65 chore: bump docker/setup-qemu-action from 3.0.0 to 3.2.0 (#53)</summary>
chore: bump docker/setup-qemu-action from 3.0.0 to 3.2.0 (#53)

Bumps
[docker/setup-qemu-action](https://github.com/docker/setup-qemu-action)
from 3.0.0 to 3.2.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/docker/setup-qemu-action/releases">docker/setup-qemu-action's
releases</a>.</em></p>
<blockquote>
<h2>v3.2.0</h2>
<ul>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.31.0 to 0.35.0 in
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/154">docker/setup-qemu-action#154</a>
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/155">docker/setup-qemu-action#155</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/setup-qemu-action/compare/v3.1.0...v3.2.0">https://github.com/docker/setup-qemu-action/compare/v3.1.0...v3.2.0</a></p>
<h2>v3.1.0</h2>
<ul>
<li>Set <code>docker.io</code> domain for default binfmt image by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/setup-qemu-action/pull/151">docker/setup-qemu-action#151</a></li>
<li>Throw error message instead of exit code by <a
href="https://github.com/crazy-max"><code>@​crazy-max</code></a> in <a
href="https://redirect.github.com/docker/setup-qemu-action/pull/129">docker/setup-qemu-action#129</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.12.0 to 0.31.0 in
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/115">docker/setup-qemu-action#115</a>
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/128">docker/setup-qemu-action#128</a>
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/131">docker/setup-qemu-action#131</a>
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/134">docker/setup-qemu-action#134</a>
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/149">docker/setup-qemu-action#149</a></li>
<li>Bump <code>@​babel/traverse</code> from 7.20.13 to 7.23.2 in <a
href="https://redirect.github.com/docker/setup-qemu-action/pull/109">docker/setup-qemu-action#109</a></li>
<li>Bump braces from 3.0.2 to 3.0.3 in <a
href="https://redirect.github.com/docker/setup-qemu-action/pull/142">docker/setup-qemu-action#142</a></li>
<li>Bump undici from 5.28.2 to 5.28.4 in <a
href="https://redirect.github.com/docker/setup-qemu-action/pull/118">docker/setup-qemu-action#118</a>
<a
href="https://redirect.github.com/docker/setup-qemu-action/pull/127">docker/setup-qemu-action#127</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/setup-qemu-action/compare/v3.0.0...v3.1.0">https://github.com/docker/setup-qemu-action/compare/v3.0.0...v3.1.0</a></p>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/49b3bc8e6bdd4a60e6116a5414239cba5943d3cf"><code>49b3bc8</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/setup-qemu-action/issues/155">#155</a>
from docker/dependabot/npm_and_yarn/docker/actions-to...</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/9dec05bc9dfb7b51fa07d2f370b0cbfb1a40a90b"><code>9dec05b</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/73387bcb62f14c182fa1cbcd58127009845eb8d1"><code>73387bc</code></a>
build(deps): bump <code>@​docker/actions-toolkit</code> from 0.34.0 to
0.35.0</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/fcfabe005416080c2016468f7082c2a191cdeea3"><code>fcfabe0</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/setup-qemu-action/issues/154">#154</a>
from docker/dependabot/npm_and_yarn/docker/actions-to...</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/948a83825363200656d0cf01e42682735ca3d654"><code>948a838</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/31629f69bf239348b7cdb36f0d9a054bed2fca00"><code>31629f6</code></a>
switch to Docker exec</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/6ae1d4dea8f84ff62b32f84a66722136ef7e68e7"><code>6ae1d4d</code></a>
build(deps): bump <code>@​docker/actions-toolkit</code> from 0.31.0 to
0.34.0</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/5927c834f5b4fdf503fca6f4c7eccda82949e1ee"><code>5927c83</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/setup-qemu-action/issues/149">#149</a>
from docker/dependabot/npm_and_yarn/docker/actions-to...</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/32ea29b3c9ea9a9fa2e79ca2107cf67f2751c47f"><code>32ea29b</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/setup-qemu-action/commit/92ac892047a708260a813e992acf5f54679f8950"><code>92ac892</code></a>
build(deps): bump <code>@​docker/actions-toolkit</code> from 0.23.0 to
0.31.0</li>
<li>Additional commits viewable in <a
href="https://github.com/docker/setup-qemu-action/compare/v3.0.0...v3.2.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=docker/setup-qemu-action&package-manager=github_actions&previous-version=3.0.0&new-version=3.2.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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