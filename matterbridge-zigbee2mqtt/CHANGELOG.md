Changes in this Release

<details><summary>86d8add ⬆️ Update matterbridge to v3.0.3 (#138)</summary>
⬆️ Update matterbridge to v3.0.3 (#138)

This PR contains the following updates:

| Package | Change | Age | Adoption | Passing | Confidence |
|---|---|---|---|---|---|
|
[matterbridge](https://redirect.github.com/Luligu/matterbridge/blob/main/README.md)
([source](https://redirect.github.com/Luligu/matterbridge)) | `3.0.2` ->
`3.0.3` |
[![age](https://developer.mend.io/api/mc/badges/age/npm/matterbridge/3.0.3?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![adoption](https://developer.mend.io/api/mc/badges/adoption/npm/matterbridge/3.0.3?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![passing](https://developer.mend.io/api/mc/badges/compatibility/npm/matterbridge/3.0.2/3.0.3?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![confidence](https://developer.mend.io/api/mc/badges/confidence/npm/matterbridge/3.0.2/3.0.3?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.0.3`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#303---2025-05-19)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/e6e72571bfe5a01d71a45b597855f0722746c744...3.0.3)

##### New plugins

[Dyson
robot](https://redirect.github.com/thoukydides/matterbridge-dyson-robot)

A Matterbridge plugin that connects Dyson robot vacuums and air
treatment devices.
to the Matter smart home ecosystem via their local MQTT APIs.

[Aeg
robot](https://redirect.github.com/thoukydides/matterbridge-aeg-robot)

AEG RX 9 / Electrolux Pure i9 robot vacuum plugin for Matterbridge.

##### Added

- \[virtual] Added virtual devices configuration mode in the
Matterbridge Settings: 'Disabled', 'Light', 'Outlet', 'Switch',
'Mounted_switch'. Switch is not supported by Alexa. Mounted Switch is
not supported by Apple.
- \[deviceTypes] Added evse, waterHeater, solarPower, batteryStorage and
heatPump device type.
- \[waterHeater] Added WaterHeater class to create a Water Heater Device
Type in one line of code (thanks https://github.com/lboue).
- \[subscribe] Added a third parameter context (provisional
implementation: when "context.offline === true" then this is a change
coming from the device).

##### Changed

-   \[package]: Updated dependencies.
- \[export]: Removed long deprecated Matter exports from matterbridge.
Use matterbridge/matter.
-   \[matterbridge]: Refactored initialize() and cleanup() methods.
-   \[matterbridge]: Updated -help informations.
- \[rvc]: Added the parameters in the RoboticVacuumCleaner class
constructor.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.0.3-dev-20250520-e6e7257`](https://redirect.github.com/Luligu/matterbridge/compare/e6e72571bfe5a01d71a45b597855f0722746c744...e6e72571bfe5a01d71a45b597855f0722746c744)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/e6e72571bfe5a01d71a45b597855f0722746c744...e6e72571bfe5a01d71a45b597855f0722746c744)

###
[`v3.0.3-dev-20250519-e6e7257`](https://redirect.github.com/Luligu/matterbridge/compare/acb27744e7577ba7fd0f0838915739b865cffc52...e6e72571bfe5a01d71a45b597855f0722746c744)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/acb27744e7577ba7fd0f0838915739b865cffc52...e6e72571bfe5a01d71a45b597855f0722746c744)

###
[`v3.0.3-dev-20250519-acb2774`](https://redirect.github.com/Luligu/matterbridge/compare/6aad062f7f6f7e436ebb2cd04639456fe843e4fa...acb27744e7577ba7fd0f0838915739b865cffc52)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/6aad062f7f6f7e436ebb2cd04639456fe843e4fa...acb27744e7577ba7fd0f0838915739b865cffc52)

###
[`v3.0.3-dev-20250519-6aad062`](https://redirect.github.com/Luligu/matterbridge/compare/e0f532cc1cf6a1e679b66c8f9705aee5880af7f4...6aad062f7f6f7e436ebb2cd04639456fe843e4fa)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/e0f532cc1cf6a1e679b66c8f9705aee5880af7f4...6aad062f7f6f7e436ebb2cd04639456fe843e4fa)

###
[`v3.0.3-dev-20250518-e0f532c`](https://redirect.github.com/Luligu/matterbridge/compare/a216d52874d197bdea955a2ce70b083a01537ebd...e0f532cc1cf6a1e679b66c8f9705aee5880af7f4)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/a216d52874d197bdea955a2ce70b083a01537ebd...e0f532cc1cf6a1e679b66c8f9705aee5880af7f4)

###
[`v3.0.3-dev-20250518-a216d52`](https://redirect.github.com/Luligu/matterbridge/compare/bcc5d13f0c1a2cad2e288df04fb1df279b96b147...a216d52874d197bdea955a2ce70b083a01537ebd)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/bcc5d13f0c1a2cad2e288df04fb1df279b96b147...a216d52874d197bdea955a2ce70b083a01537ebd)

###
[`v3.0.3-dev-20250517-bcc5d13`](https://redirect.github.com/Luligu/matterbridge/compare/720018f25d216cdd67f17ac300cff63fde403212...bcc5d13f0c1a2cad2e288df04fb1df279b96b147)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/720018f25d216cdd67f17ac300cff63fde403212...bcc5d13f0c1a2cad2e288df04fb1df279b96b147)

###
[`v3.0.3-dev-20250517-720018f`](https://redirect.github.com/Luligu/matterbridge/compare/3.0.2...720018f25d216cdd67f17ac300cff63fde403212)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.0.2...720018f25d216cdd67f17ac300cff63fde403212)

</details>

---

### Configuration

📅 **Schedule**: Branch creation - At any time (no schedule defined),
Automerge - At any time (no schedule defined).

🚦 **Automerge**: Enabled.

♻ **Rebasing**: Whenever PR is behind base branch, or you tick the
rebase/retry checkbox.

🔕 **Ignore**: Close this PR and you won't be reminded about this update
again.

---

- [ ] <!-- rebase-check -->If you want to rebase/retry this PR, check
this box

---

This PR was generated by [Mend Renovate](https://mend.io/renovate/).
View the [repository job
log](https://developer.mend.io/github/L2jLiga/ha-addons).

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiI0MC4xNi4wIiwidXBkYXRlZEluVmVyIjoiNDAuMTYuMCIsInRhcmdldEJyYW5jaCI6Im1hc3RlciIsImxhYmVscyI6WyJkZXBlbmRlbmNpZXMiLCJuby1zdGFsZSJdfQ==-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>