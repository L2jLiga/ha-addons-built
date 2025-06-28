Changes in this Release

<details><summary>841fc98 ⬆️ Update matterbridge to v3.1.0 (#148)</summary>
⬆️ Update matterbridge to v3.1.0 (#148)

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.1.0`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#310---2025-06-28)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/94e7f6ecf6d6c82009fed4444b1859a1853c2b4c...3.1.0)

##### Added

- \[DevContainer]: Added support for the **Matterbridge Dev Container**
with an optimized named volume for `node_modules`.
- \[GitHub]: Added GitHub issue templates for bug reports and feature
requests.
- \[Systemd]: Added a systemd service file for Matterbridge in the
systemd directory.
- \[ESLint]: Refactored ESLint configuration for TypeScript and improved
plugin integration.
- \[ESLint]: Added the plugins `eslint-plugin-promise`,
`eslint-plugin-jsdoc`, and `@vitest/eslint-plugin`.
- \[Vitest]: Added Vitest for TypeScript project testing. It will
replace Jest, which does not work correctly with ESM module mocks.
- \[JSDoc]: Added missing JSDoc comments, including `@param` and
`@returns` tags.
- \[MatterbridgeEndpoint]: Add MatterbridgeEndpoint mode='server'. It
allows to advertise a single device like an autonomous device with its
server node to be paired. The device is not bridged (alpha stage).
- \[MatterbridgeEndpoint]: Add MatterbridgeEndpoint mode='matter'. It
allows to add a single device to the Matterbridge server node next to
the aggregator. The device is not bridged (alpha stage).
- \[storage]: Improved error handling of corrupted storage.
- \[test]: Improved test units on Matterbridge classes.

##### Changed

- \[package]: Updated package to Automator v. 2.0.0.
- \[package]: Updated dependencies.
- \[storage]: Bumped `node-storage-manager` to 2.0.0.
- \[logger]: Bumped `node-ansi-logger` to 3.1.1.
- \[matter.js]: Bumped `matter.js` to 0.15.0
([https://github.com/project-chip/matter.js/discussions/2203](https://redirect.github.com/project-chip/matter.js/discussions/2203)).
Great job matter.js!

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.1.0-dev-20250627-94e7f6e`](https://redirect.github.com/Luligu/matterbridge/compare/2b5adba5bcb91b904cdb150332e91b9ed5ebae6f...94e7f6ecf6d6c82009fed4444b1859a1853c2b4c)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/2b5adba5bcb91b904cdb150332e91b9ed5ebae6f...94e7f6ecf6d6c82009fed4444b1859a1853c2b4c)

###
[`v3.1.0-dev-20250627-2b5adba`](https://redirect.github.com/Luligu/matterbridge/compare/1445fbddc644328233166f2feb96f930b3b85a35...2b5adba5bcb91b904cdb150332e91b9ed5ebae6f)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/1445fbddc644328233166f2feb96f930b3b85a35...2b5adba5bcb91b904cdb150332e91b9ed5ebae6f)

###
[`v3.0.8-dev-20250626-1445fbd`](https://redirect.github.com/Luligu/matterbridge/compare/50aa686f0f11f2f3385ce0b262f4914da666d134...1445fbddc644328233166f2feb96f930b3b85a35)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/50aa686f0f11f2f3385ce0b262f4914da666d134...1445fbddc644328233166f2feb96f930b3b85a35)

###
[`v3.0.8-dev-20250626-50aa686`](https://redirect.github.com/Luligu/matterbridge/compare/20885cb83f916818fb2d9b302dfc0d193b5d8542...50aa686f0f11f2f3385ce0b262f4914da666d134)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/20885cb83f916818fb2d9b302dfc0d193b5d8542...50aa686f0f11f2f3385ce0b262f4914da666d134)

###
[`v3.0.8-dev-20250625-20885cb`](https://redirect.github.com/Luligu/matterbridge/compare/61b37693524f298c69f602d3998d3cfc14a656f8...20885cb83f916818fb2d9b302dfc0d193b5d8542)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/61b37693524f298c69f602d3998d3cfc14a656f8...20885cb83f916818fb2d9b302dfc0d193b5d8542)

###
[`v3.0.8-dev-20250625-61b3769`](https://redirect.github.com/Luligu/matterbridge/compare/5abb0bb836c5789dc9ba6e39893b3deb4981bd60...61b37693524f298c69f602d3998d3cfc14a656f8)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/5abb0bb836c5789dc9ba6e39893b3deb4981bd60...61b37693524f298c69f602d3998d3cfc14a656f8)

###
[`v3.0.8-dev-20250624-5abb0bb`](https://redirect.github.com/Luligu/matterbridge/compare/f9e44a2312b0dbb41f07d57102ba6b6a9d41a560...5abb0bb836c5789dc9ba6e39893b3deb4981bd60)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/f9e44a2312b0dbb41f07d57102ba6b6a9d41a560...5abb0bb836c5789dc9ba6e39893b3deb4981bd60)

###
[`v3.0.8-dev-20250622-f9e44a2`](https://redirect.github.com/Luligu/matterbridge/compare/9a6255a5bdef1380d09357d099b901f23c0f27e0...f9e44a2312b0dbb41f07d57102ba6b6a9d41a560)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/9a6255a5bdef1380d09357d099b901f23c0f27e0...f9e44a2312b0dbb41f07d57102ba6b6a9d41a560)

###
[`v3.0.8-dev-20250622-9a6255a`](https://redirect.github.com/Luligu/matterbridge/compare/3.0.7...9a6255a5bdef1380d09357d099b901f23c0f27e0)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.0.7...9a6255a5bdef1380d09357d099b901f23c0f27e0)

</details>

---

This PR was generated by [Mend Renovate](https://mend.io/renovate/).
View the [repository job
log](https://developer.mend.io/github/L2jLiga/ha-addons).

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiI0MC42Mi4xIiwidXBkYXRlZEluVmVyIjoiNDAuNjIuMSIsInRhcmdldEJyYW5jaCI6Im1hc3RlciIsImxhYmVscyI6WyJkZXBlbmRlbmNpZXMiLCJuby1zdGFsZSJdfQ==-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>