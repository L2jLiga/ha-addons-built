Changes in this Release

<details><summary>b062480 ⬆️ Update matterbridge to v3.2.2 (#161)</summary>
⬆️ Update matterbridge to v3.2.2 (#161)

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.2.2`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#322---2025-08-10)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.2.1...3.2.2)

##### Changed

- \[package]: Updated dependencies.

##### Fixed

- \[frontend]: Fixed new Matterbridge frontend version message on the
Home page.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.2.1`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#321---2025-08-10)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/8836577034d5ea60fb120970afe4a164cfcb6db0...3.2.1)

##### Added

- \[platform]: Added uniqueId validation in registerDevice method. It
prevents to register a device if the implementation didn't call
createDefaultBasicInformationClusterServer() or
createDefaultBridgedDeviceBasicInformationClusterServer().
- \[platform]: Added deviceName validation in registerDevice method.
- \[platform]: Added serialNumber validation in registerDevice method.
- \[endpoint]: Removed static MatterbridgeEndpoint.bridgeMode.
- \[endpoint]: Removed BasicInformationServer remap to
BridgedDeviceBasicInformationServer in MatterbridgeEndpoint.
- \[platform]: Added BasicInformationServer remap to
BridgedDeviceBasicInformationServer in MatterbridgePlatform
registerDevice method when needed (bridgeMode = `bridge` and platform
type = `DynamicPlatform` in `childbridge` mode).
- \[frontend]: Bumped `frontend` version to 2.7.3.
- \[frontend]: Added frontend version to MatterbridgeInformation. It
triggers the page reload message on the Home page when updated.
- \[frontend]: Removed the sponsor badge. Added star and sponsor icons
buttons.

##### Changed

- \[package]: Updated dependencies.
- \[matter.js]: Bumped `matter.js` to 0.15.3. Thanks matter.js!
- \[matter.js]: Bumped `typescript` to 5.9.2.

##### Fixed

- \[frontend]: Fixed pointer on Discord icon.
- \[deepcopy]: Fixed Date test case to use a specific UTC timestamp. It
was failing on different timezones.
- \[frontend]: Fixed new Matterbridge version message on the Home page.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.2.1-dev-20250811-8836577`](https://redirect.github.com/Luligu/matterbridge/compare/1aeddad25a5a37ac35619867d11cd7eff3f623f6...8836577034d5ea60fb120970afe4a164cfcb6db0)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/1aeddad25a5a37ac35619867d11cd7eff3f623f6...8836577034d5ea60fb120970afe4a164cfcb6db0)

###
[`v3.2.1-dev-20250807-1aeddad`](https://redirect.github.com/Luligu/matterbridge/compare/84c80207d223393d3baa60c3dcf54dd3c1feb3d1...1aeddad25a5a37ac35619867d11cd7eff3f623f6)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/84c80207d223393d3baa60c3dcf54dd3c1feb3d1...1aeddad25a5a37ac35619867d11cd7eff3f623f6)

###
[`v3.2.1-dev-20250806-84c8020`](https://redirect.github.com/Luligu/matterbridge/compare/8a31d918de048ca478fccbc0911ca6d1e76645b1...84c80207d223393d3baa60c3dcf54dd3c1feb3d1)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/8a31d918de048ca478fccbc0911ca6d1e76645b1...84c80207d223393d3baa60c3dcf54dd3c1feb3d1)

###
[`v3.2.1-dev-20250806-8a31d91`](https://redirect.github.com/Luligu/matterbridge/compare/a440a54fc362e8af7412a6636146ad621802f52c...8a31d918de048ca478fccbc0911ca6d1e76645b1)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/a440a54fc362e8af7412a6636146ad621802f52c...8a31d918de048ca478fccbc0911ca6d1e76645b1)

###
[`v3.2.1-dev-20250805-a440a54`](https://redirect.github.com/Luligu/matterbridge/compare/be73ddb120aa6a59b2083c62174f945d3624bf5e...a440a54fc362e8af7412a6636146ad621802f52c)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/be73ddb120aa6a59b2083c62174f945d3624bf5e...a440a54fc362e8af7412a6636146ad621802f52c)

###
[`v3.2.1-dev-20250804-be73ddb`](https://redirect.github.com/Luligu/matterbridge/compare/c70121ebd64073d8f90eb93a7bf311327f0addfa...be73ddb120aa6a59b2083c62174f945d3624bf5e)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c70121ebd64073d8f90eb93a7bf311327f0addfa...be73ddb120aa6a59b2083c62174f945d3624bf5e)

###
[`v3.2.1-dev-20250803-c70121e`](https://redirect.github.com/Luligu/matterbridge/compare/f978b33d3f8b7d1824a859ea37e04aa2ce9016fd...c70121ebd64073d8f90eb93a7bf311327f0addfa)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/f978b33d3f8b7d1824a859ea37e04aa2ce9016fd...c70121ebd64073d8f90eb93a7bf311327f0addfa)

###
[`v3.2.1-dev-20250802-f978b33`](https://redirect.github.com/Luligu/matterbridge/compare/741949bd713abe80aa6a0af2fc0caaf92144cd4c...f978b33d3f8b7d1824a859ea37e04aa2ce9016fd)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/741949bd713abe80aa6a0af2fc0caaf92144cd4c...f978b33d3f8b7d1824a859ea37e04aa2ce9016fd)

###
[`v3.2.1-dev-20250802-741949b`](https://redirect.github.com/Luligu/matterbridge/compare/516a52213315c8875004d2a5f8bed3d95780c2db...741949bd713abe80aa6a0af2fc0caaf92144cd4c)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/516a52213315c8875004d2a5f8bed3d95780c2db...741949bd713abe80aa6a0af2fc0caaf92144cd4c)

###
[`v3.2.1-dev-20250802-516a522`](https://redirect.github.com/Luligu/matterbridge/compare/3.2.0...516a52213315c8875004d2a5f8bed3d95780c2db)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.2.0...516a52213315c8875004d2a5f8bed3d95780c2db)

</details>

---

This PR was generated by [Mend Renovate](https://mend.io/renovate/).
View the [repository job
log](https://developer.mend.io/github/L2jLiga/ha-addons).

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiI0MS42MC40IiwidXBkYXRlZEluVmVyIjoiNDEuNjAuNCIsInRhcmdldEJyYW5jaCI6Im1hc3RlciIsImxhYmVscyI6WyJkZXBlbmRlbmNpZXMiLCJuby1zdGFsZSJdfQ==-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>