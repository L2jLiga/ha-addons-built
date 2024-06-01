Changes in this Release

<details><summary>d32f32f chore: bump docker/login-action from 3.1.0 to 3.2.0 (#21)</summary>
chore: bump docker/login-action from 3.1.0 to 3.2.0 (#21)

Bumps [docker/login-action](https://github.com/docker/login-action) from
3.1.0 to 3.2.0.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a
href="https://github.com/docker/login-action/releases">docker/login-action's
releases</a>.</em></p>
<blockquote>
<h2>v3.2.0</h2>
<ul>
<li>Improve missing username/password by <a
href="https://github.com/Frankkkkk"><code>@​Frankkkkk</code></a> in <a
href="https://redirect.github.com/docker/login-action/pull/706">docker/login-action#706</a></li>
<li>Bump <code>@​docker/actions-toolkit</code> from 0.18.0 to 0.24.0 in
<a
href="https://redirect.github.com/docker/login-action/pull/715">docker/login-action#715</a>
<a
href="https://redirect.github.com/docker/login-action/pull/721">docker/login-action#721</a></li>
<li>Bump aws-sdk-dependencies to 3.583.0 in <a
href="https://redirect.github.com/docker/login-action/pull/720">docker/login-action#720</a></li>
<li>Bump undici from 5.28.3 to 5.28.4 in <a
href="https://redirect.github.com/docker/login-action/pull/694">docker/login-action#694</a></li>
</ul>
<p><strong>Full Changelog</strong>: <a
href="https://github.com/docker/login-action/compare/v3.1.0...v3.2.0">https://github.com/docker/login-action/compare/v3.1.0...v3.2.0</a></p>
</blockquote>
</details>
<details>
<summary>Commits</summary>
<ul>
<li><a
href="https://github.com/docker/login-action/commit/0d4c9c5ea7693da7b068278f7b52bda2a190a446"><code>0d4c9c5</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/722">#722</a>
from crazy-max/update-readme</li>
<li><a
href="https://github.com/docker/login-action/commit/b29e14f6a983abc16efafe71e083f4b1ba2b1e5b"><code>b29e14f</code></a>
add contributing section to README</li>
<li><a
href="https://github.com/docker/login-action/commit/218a70c516af2f25cb9fc1e5a14a5a3576e7093f"><code>218a70c</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/721">#721</a>
from docker/dependabot/npm_and_yarn/docker/actions-to...</li>
<li><a
href="https://github.com/docker/login-action/commit/b8200806cfe29e3355c44f34309b26916aae48f6"><code>b820080</code></a>
build(deps): bump <code>@​docker/actions-toolkit</code> from 0.23.0 to
0.24.0</li>
<li><a
href="https://github.com/docker/login-action/commit/27530a9fbbe988616da1dc41b4a8072f949d8042"><code>27530a9</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/720">#720</a>
from docker/dependabot/npm_and_yarn/aws-sdk-dependenc...</li>
<li><a
href="https://github.com/docker/login-action/commit/d072a60421ee5ac6ee763e9306c27f92e8ce5a20"><code>d072a60</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/login-action/commit/7c627b5124287958ac76b37cc2d94f1c9ef72aaa"><code>7c627b5</code></a>
build(deps): bump the aws-sdk-dependencies group across 1 directory with
2 up...</li>
<li><a
href="https://github.com/docker/login-action/commit/787cfc66231286ca823ebc099f52001f53aa8f42"><code>787cfc6</code></a>
Merge pull request <a
href="https://redirect.github.com/docker/login-action/issues/694">#694</a>
from docker/dependabot/npm_and_yarn/undici-5.28.4</li>
<li><a
href="https://github.com/docker/login-action/commit/8e66e916f8ed83b241171904f8e1b9e0a83070bc"><code>8e66e91</code></a>
chore: update generated content</li>
<li><a
href="https://github.com/docker/login-action/commit/5ba5e97350e175e4c4e222569e6746675408a75c"><code>5ba5e97</code></a>
build(deps): bump undici from 5.28.3 to 5.28.4</li>
<li>Additional commits viewable in <a
href="https://github.com/docker/login-action/compare/v3.1.0...v3.2.0">compare
view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility
score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=docker/login-action&package-manager=github_actions&previous-version=3.1.0&new-version=3.2.0)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

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