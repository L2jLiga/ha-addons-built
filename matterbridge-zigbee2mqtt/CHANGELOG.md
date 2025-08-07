Changes in this Release

<details><summary>0b891ea ⬆️ Update matterbridge to v3.2.0 (#159)</summary>
⬆️ Update matterbridge to v3.2.0 (#159)

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.2.0`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#320---2025-08-01)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/fb1e4d04034fe4504350dad96cde1b10942035bd...3.2.0)

##### Breaking Changes

Removed node 18 support.
Please install Node.js 22 LTS.
Don't use Node.js Current but always the Node.js LTS.
Node.js 23, like all odd-numbered versions, is not supported.

##### Added

- \[update]: Added a Snackbar message for available updates from npm. It
differs for latest and dev versions. The update check, as always, is
performed at restart (1 minute after) and each 12 hours. It can be
triggered manually from the frontend.
- \[update]: First steps of update and log important messages from
GitHub.
- \[build]: Added workflow\_dispatch trigger and enhance dependency
management in CI.
- \[build]: Added macOS 15 to the CI matrix for Node.js builds.
- \[frontend]: Bump version 2.7.2.
- \[frontend]: Added the plugin name on the QR/Fabrics when in
childbridge mode. Changed operational mode to one click only.

##### Changed

- \[package]: Updated dependencies.
- \[matter.js]: Bumped `matter.js` to 0.15.2
([https://github.com/project-chip/matter.js/discussions/2203](https://redirect.github.com/project-chip/matter.js/discussions/2203)).
Great job matter.js!
- \[node.js]: Removed node 18 support.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.2.0-dev-20250802-fb1e4d0`](https://redirect.github.com/Luligu/matterbridge/compare/f7eb2a27845f03ed320d49142c511046c65b203d...fb1e4d04034fe4504350dad96cde1b10942035bd)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/f7eb2a27845f03ed320d49142c511046c65b203d...fb1e4d04034fe4504350dad96cde1b10942035bd)

###
[`v3.2.0-dev-20250801-f7eb2a2`](https://redirect.github.com/Luligu/matterbridge/compare/e5ebd9162f7d705a9c25e95fa8ac689eb723ea0b...f7eb2a27845f03ed320d49142c511046c65b203d)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/e5ebd9162f7d705a9c25e95fa8ac689eb723ea0b...f7eb2a27845f03ed320d49142c511046c65b203d)

###
[`v3.2.0-dev-20250801-e5ebd91`](https://redirect.github.com/Luligu/matterbridge/compare/d04e6d8c48c28cd170c2749b2f5c11135268f62f...e5ebd9162f7d705a9c25e95fa8ac689eb723ea0b)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/d04e6d8c48c28cd170c2749b2f5c11135268f62f...e5ebd9162f7d705a9c25e95fa8ac689eb723ea0b)

###
[`v3.2.0-dev-20250730-d04e6d8`](https://redirect.github.com/Luligu/matterbridge/compare/fcbf3926d8039f305a36679fb4f4b6838ee8664d...d04e6d8c48c28cd170c2749b2f5c11135268f62f)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/fcbf3926d8039f305a36679fb4f4b6838ee8664d...d04e6d8c48c28cd170c2749b2f5c11135268f62f)

###
[`v3.2.0-dev-20250729-fcbf392`](https://redirect.github.com/Luligu/matterbridge/compare/d64715f724b06eac6e754bb091aa57c80c54a99e...fcbf3926d8039f305a36679fb4f4b6838ee8664d)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/d64715f724b06eac6e754bb091aa57c80c54a99e...fcbf3926d8039f305a36679fb4f4b6838ee8664d)

###
[`v3.1.9-dev-20250729-d64715f`](https://redirect.github.com/Luligu/matterbridge/compare/3.1.8...d64715f724b06eac6e754bb091aa57c80c54a99e)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.1.8...d64715f724b06eac6e754bb091aa57c80c54a99e)

###
[`v3.1.8`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#318---2025-07-28)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/ed442c48f370d755d2b52bc85051f0d3828bb899...3.1.8)

##### Added

- \[Jest]: Total coverage 100%.
- \[certification]: Improved certification management in pairing.json.
Added pemToBuffer function for converting PEM strings to Uint8Array.
- \[certification]: Improved certification management in pairing.json.
Added extractPrivateKeyRaw function for extrating the raw part of PEM
private key to Uint8Array.
- \[workflow]: Update permissions and change GitHub token for Docker
build triggers.
- \[update]: Added support for retrieving and logging plugin development
versions.
- \[frontend]: Improved test units on Frontend class (total coverage
100%).
- \[frontend]: Bump version 2.7.1.
- \[frontend]: Added Changelog button that appears in the frontend when
a new version is installed and the frontend needs to be updated (page
refresh).
- \[frontend]: Added restart plugin in childbridge mode.
- \[frontend]: Added update to stable and update to dev banner. The
update to new appears only if you are on the dev and there is a new dev
version.
- \[frontend]: Added update to stable and update to dev banner for
plugins. The update to new dev appears only if you are on the dev and
there is a new dev version.
- \[frontend]: Added new menu item for manual update check.

##### Changed

- \[package]: Updated dependencies.

##### Fixed

- \[switch]: Added conditional handling for momentary switch events in
MatterbridgeEndpoint for single press only switches.
- \[advertise]: Changed the message advertise stopped to work also in
childbridge mode.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.1.8-dev-20250729-ed442c4`](https://redirect.github.com/Luligu/matterbridge/compare/c823a8951364f58caa5524ac9bba983b01fbeaf6...ed442c48f370d755d2b52bc85051f0d3828bb899)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c823a8951364f58caa5524ac9bba983b01fbeaf6...ed442c48f370d755d2b52bc85051f0d3828bb899)

###
[`v3.1.8-dev-20250727-c823a89`](https://redirect.github.com/Luligu/matterbridge/compare/b8987de35519cb39701635117def6e3b79802292...c823a8951364f58caa5524ac9bba983b01fbeaf6)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/b8987de35519cb39701635117def6e3b79802292...c823a8951364f58caa5524ac9bba983b01fbeaf6)

###
[`v3.1.8-dev-20250727-b8987de`](https://redirect.github.com/Luligu/matterbridge/compare/662308b1900706c33f89a610b96c6a39b575935e...b8987de35519cb39701635117def6e3b79802292)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/662308b1900706c33f89a610b96c6a39b575935e...b8987de35519cb39701635117def6e3b79802292)

###
[`v3.1.8-dev-20250727-662308b`](https://redirect.github.com/Luligu/matterbridge/compare/f93c04cdac616a3e3dfcb0ccf1f510ace91207e7...662308b1900706c33f89a610b96c6a39b575935e)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/f93c04cdac616a3e3dfcb0ccf1f510ace91207e7...662308b1900706c33f89a610b96c6a39b575935e)

###
[`v3.1.8-dev-20250726-f93c04c`](https://redirect.github.com/Luligu/matterbridge/compare/aa58df511b3c7af12c2b7a49a8ec39abf3c89587...f93c04cdac616a3e3dfcb0ccf1f510ace91207e7)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/aa58df511b3c7af12c2b7a49a8ec39abf3c89587...f93c04cdac616a3e3dfcb0ccf1f510ace91207e7)

###
[`v3.1.8-dev-20250726-aa58df5`](https://redirect.github.com/Luligu/matterbridge/compare/82f77ee1de5a7398cf8ea5efefdb3ad9a03af097...aa58df511b3c7af12c2b7a49a8ec39abf3c89587)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/82f77ee1de5a7398cf8ea5efefdb3ad9a03af097...aa58df511b3c7af12c2b7a49a8ec39abf3c89587)

###
[`v3.1.8-dev-20250726-82f77ee`](https://redirect.github.com/Luligu/matterbridge/compare/d6e57e3e3577f7136d1c9f8dff761ac47540576e...82f77ee1de5a7398cf8ea5efefdb3ad9a03af097)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/d6e57e3e3577f7136d1c9f8dff761ac47540576e...82f77ee1de5a7398cf8ea5efefdb3ad9a03af097)

###
[`v3.1.8-dev-20250725-d6e57e3`](https://redirect.github.com/Luligu/matterbridge/compare/b9a56eb8376b74b433e1ba247d8b00af39ec6959...d6e57e3e3577f7136d1c9f8dff761ac47540576e)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/b9a56eb8376b74b433e1ba247d8b00af39ec6959...d6e57e3e3577f7136d1c9f8dff761ac47540576e)

###
[`v3.1.8-dev-20250725-b9a56eb`](https://redirect.github.com/Luligu/matterbridge/compare/aa6ff9eb3b9faec5d8b62b73ad8d99d2eeedc093...b9a56eb8376b74b433e1ba247d8b00af39ec6959)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/aa6ff9eb3b9faec5d8b62b73ad8d99d2eeedc093...b9a56eb8376b74b433e1ba247d8b00af39ec6959)

###
[`v3.1.8-dev-20250725-aa6ff9e`](https://redirect.github.com/Luligu/matterbridge/compare/5cc04741e810293ee6db763367e900f4df0973a2...aa6ff9eb3b9faec5d8b62b73ad8d99d2eeedc093)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/5cc04741e810293ee6db763367e900f4df0973a2...aa6ff9eb3b9faec5d8b62b73ad8d99d2eeedc093)

###
[`v3.1.8-dev-20250725-5cc0474`](https://redirect.github.com/Luligu/matterbridge/compare/3.1.7...5cc04741e810293ee6db763367e900f4df0973a2)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.1.7...5cc04741e810293ee6db763367e900f4df0973a2)

</details>

---

This PR was generated by [Mend Renovate](https://mend.io/renovate/).
View the [repository job
log](https://developer.mend.io/github/L2jLiga/ha-addons).

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiI0MS41MS4xIiwidXBkYXRlZEluVmVyIjoiNDEuNTEuMSIsInRhcmdldEJyYW5jaCI6Im1hc3RlciIsImxhYmVscyI6WyJkZXBlbmRlbmNpZXMiLCJuby1zdGFsZSJdfQ==-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>