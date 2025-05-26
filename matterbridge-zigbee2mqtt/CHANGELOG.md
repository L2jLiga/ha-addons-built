Changes in this Release

<details><summary>bf2287d ⬆️ Update Matterbridge (#139)</summary>
⬆️ Update Matterbridge (#139)

This PR contains the following updates:

| Package | Change | Age | Adoption | Passing | Confidence |
|---|---|---|---|---|---|
|
[matterbridge](https://redirect.github.com/Luligu/matterbridge/blob/main/README.md)
([source](https://redirect.github.com/Luligu/matterbridge)) | `3.0.3` ->
`3.0.4` |
[![age](https://developer.mend.io/api/mc/badges/age/npm/matterbridge/3.0.4?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![adoption](https://developer.mend.io/api/mc/badges/adoption/npm/matterbridge/3.0.4?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![passing](https://developer.mend.io/api/mc/badges/compatibility/npm/matterbridge/3.0.3/3.0.4?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![confidence](https://developer.mend.io/api/mc/badges/confidence/npm/matterbridge/3.0.3/3.0.4?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
|
[matterbridge-zigbee2mqtt](https://www.npmjs.com/package/matterbridge-zigbee2mqtt)
([source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt))
| `2.4.7` -> `2.5.0` |
[![age](https://developer.mend.io/api/mc/badges/age/npm/matterbridge-zigbee2mqtt/2.5.0?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![adoption](https://developer.mend.io/api/mc/badges/adoption/npm/matterbridge-zigbee2mqtt/2.5.0?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![passing](https://developer.mend.io/api/mc/badges/compatibility/npm/matterbridge-zigbee2mqtt/2.4.7/2.5.0?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![confidence](https://developer.mend.io/api/mc/badges/confidence/npm/matterbridge-zigbee2mqtt/2.4.7/2.5.0?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.0.4`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#304---2025-05-26)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c88cf84156be1d62fba1f0e1a403ddbe4e5e2cf4...3.0.4)

##### Added

-   \[jsdoc]: Improved jsdoc for cluster helpers.
- \[cover]: Added createDefaultLiftTiltWindowCoveringClusterServer()
that create a window covering cluser with both lift and tilt features
(supported by Apple Home).

##### Changed

- \[legacy]: Removed legacy matter.js EndpointServer and logEndpoint
that will be removed in matter.js 0.14.0. For developers: if you need to
log the endpoint the call is Logger.get('LogEndpoint').info(endpoint).
-   \[package]: Updated dependencies.
-   \[package]: Updated multer package to 2.0.0.

##### Fixed

- \[virtualDevice]: Fixed possible vulnerability in the length of the
nodeLabel.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.0.4-dev-20250525-c88cf84`](https://redirect.github.com/Luligu/matterbridge/compare/b1cbfb7c1731889b369a265a68c1cb96bdd94706...c88cf84156be1d62fba1f0e1a403ddbe4e5e2cf4)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/b1cbfb7c1731889b369a265a68c1cb96bdd94706...c88cf84156be1d62fba1f0e1a403ddbe4e5e2cf4)

###
[`v3.0.4-dev-20250525-b1cbfb7`](https://redirect.github.com/Luligu/matterbridge/compare/3.0.3...b1cbfb7c1731889b369a265a68c1cb96bdd94706)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.0.3...b1cbfb7c1731889b369a265a68c1cb96bdd94706)

</details>

<details>
<summary>Luligu/matterbridge-zigbee2mqtt
(matterbridge-zigbee2mqtt)</summary>

###
[`v2.5.0`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/blob/HEAD/CHANGELOG.md#250---2025-05-26)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/1719c196015c44962ff03aeaa5fbc8bf37e94b8d...2.5.0)

##### Added

- \[scenes]: Added scenes support for groups and devices. See the
README.md for explanations.
- \[waterLeak]: Added waterLeakDetector device type for zigbee property
"water_leak". Default to false (i.e. no alarm) since is not possible to
get the property.
- \[rainSensor]: Added rainSensor device type for zigbee property
"rain". Default to false (i.e. no alarm) since is not possible to get
the property.
- \[smokeSensor]: Added smokeSensor device type for zigbee property
"smoke". Default to false (i.e. no alarm) since is not possible to get
the property.
- \[colorTemp]: Added conversion from color temperature to rgb for the
rgb devices that don't support color_temp.
- \[battery]: Set batChargeLevel to warning if battery is less than 40%
and the device doesn't expose battery_low.
- \[battery]: Set batChargeLevel to critical if battery is less than 20%
and the device doesn't expose battery_low.
- \[retain]: Send retained mqtt states at startup if z2m has retain
enabled. See the README.md for explanations.
-   \[logger]: Added onChangeLoggerLevel() to the platform.

##### Changed

-   \[package]: Updated package.
-   \[package]: Updated dependencies.
-   \[plugin]: Requires Matterbridge 3.0.4.
- \[config]: As anticipated in the previous release, the parameter
postfixHostname has been removed. Use postfix if needed.
- \[colorRgb]: Changed the default device type from
colorTemperatureLight to extendedColorLight to solve the SmartThings
issue with colors.
- \[colorTemp]: The min and max mired values for color_temp are now set
in the cluster.

##### Fixed

- \[logger]: Fixed logger not always taking the correct value from the
frontend.
- \[issue104]: Solved wrong mode AUTO in system_mode for HEAT only
devices.
-   \[issue107]: Solved motor_direction reversed.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v2.5.0-rc.1`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/ca0a2ed5f16be6b6455822927781a57cf99235bd...1719c196015c44962ff03aeaa5fbc8bf37e94b8d)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/ca0a2ed5f16be6b6455822927781a57cf99235bd...1719c196015c44962ff03aeaa5fbc8bf37e94b8d)

###
[`v2.5.0-dev.9`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/831ba059d52d84ac4e135516784f2c359117aef4...ca0a2ed5f16be6b6455822927781a57cf99235bd)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/831ba059d52d84ac4e135516784f2c359117aef4...ca0a2ed5f16be6b6455822927781a57cf99235bd)

###
[`v2.5.0-dev.8`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/6aae4a620fa76e80dd8a7b17c89acc36fa64f594...831ba059d52d84ac4e135516784f2c359117aef4)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/6aae4a620fa76e80dd8a7b17c89acc36fa64f594...831ba059d52d84ac4e135516784f2c359117aef4)

###
[`v2.5.0-dev.7`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/6aae4a620fa76e80dd8a7b17c89acc36fa64f594...6aae4a620fa76e80dd8a7b17c89acc36fa64f594)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/6aae4a620fa76e80dd8a7b17c89acc36fa64f594...6aae4a620fa76e80dd8a7b17c89acc36fa64f594)

###
[`v2.5.0-dev.6`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/f25ac1566f7fe26684b2fc6109b82284a78d4b69...6aae4a620fa76e80dd8a7b17c89acc36fa64f594)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/f25ac1566f7fe26684b2fc6109b82284a78d4b69...6aae4a620fa76e80dd8a7b17c89acc36fa64f594)

###
[`v2.5.0-dev.5`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/a49253294005ac735988078014156345c0d04d1a...f25ac1566f7fe26684b2fc6109b82284a78d4b69)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/a49253294005ac735988078014156345c0d04d1a...f25ac1566f7fe26684b2fc6109b82284a78d4b69)

###
[`v2.5.0-dev.4`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/b730534838c2b8c14a15780fa0260f2b91ff6f93...a49253294005ac735988078014156345c0d04d1a)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/b730534838c2b8c14a15780fa0260f2b91ff6f93...a49253294005ac735988078014156345c0d04d1a)

###
[`v2.5.0-dev.3`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/b730534838c2b8c14a15780fa0260f2b91ff6f93...b730534838c2b8c14a15780fa0260f2b91ff6f93)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/b730534838c2b8c14a15780fa0260f2b91ff6f93...b730534838c2b8c14a15780fa0260f2b91ff6f93)

###
[`v2.5.0-dev.2`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.4.7...b730534838c2b8c14a15780fa0260f2b91ff6f93)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.4.7...b730534838c2b8c14a15780fa0260f2b91ff6f93)

</details>

---

### Configuration

📅 **Schedule**: Branch creation - At any time (no schedule defined),
Automerge - At any time (no schedule defined).

🚦 **Automerge**: Enabled.

♻ **Rebasing**: Whenever PR is behind base branch, or you tick the
rebase/retry checkbox.

👻 **Immortal**: This PR will be recreated if closed unmerged. Get
[config
help](https://redirect.github.com/renovatebot/renovate/discussions) if
that's undesired.

---

- [ ] <!-- rebase-check -->If you want to rebase/retry this PR, check
this box

---

This PR was generated by [Mend Renovate](https://mend.io/renovate/).
View the [repository job
log](https://developer.mend.io/github/L2jLiga/ha-addons).

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiI0MC4xNi4wIiwidXBkYXRlZEluVmVyIjoiNDAuMTYuMCIsInRhcmdldEJyYW5jaCI6Im1hc3RlciIsImxhYmVscyI6WyJkZXBlbmRlbmNpZXMiLCJuby1zdGFsZSJdfQ==-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>