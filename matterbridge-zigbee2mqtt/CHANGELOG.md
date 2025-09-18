Changes in this Release

<details><summary>ac17cc3 ⬆️ Update Matterbridge (#168)</summary>
⬆️ Update Matterbridge (#168)

Coming soon: The Renovate bot (GitHub App) will be renamed to Mend. PRs
from Renovate will soon appear from 'Mend'. Learn more
[here](https://redirect.github.com/renovatebot/renovate/discussions/37842).

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.2.7`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#327---2025-09-14)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/f9e5ea7a5ad4795b6d9783c1a2d481d9297804cd...3.2.7)

##### Breaking Changes

- \[platform]: Typed PlatformConfig with the default properties: name,
type, version, debug and unregisterOnShutdown.
- \[platform]: Removed DefaultPlatformConfig interface definition.

##### Added

- \[jest]: Added Jest helpers module.
- \[colorControl]: Added createEnhancedColorControlClusterServer
(provisional to run compatibility tests on all controllers).
- \[frontend]: Bumped `frontend` version to 2.7.6.
- \[frontend]: Added api/view-diagnostic.
- \[frontend]: Refactored the QRCode component for device with
mode='server' (e.g. the Rvcs): added turn on and off pairing mode,
resend mDns advertise, remove single fabrics, formatted manual paring
code, copy to clipboard the manual pairing code and is fully web socket
based. The main QRCode panel will have the same features (bridge mode
and childbridge mode) in the next release.

##### Changed

- \[package]: Updated dependencies.
- \[matterbridge.io]: Updated web site
[matterbridge.io](matterbridge.io).

##### Fixed

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.2.7-dev-20250914-f9e5ea7`](https://redirect.github.com/Luligu/matterbridge/compare/9d0d09554cc97336b4235ab95209c28efad6c773...f9e5ea7a5ad4795b6d9783c1a2d481d9297804cd)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/9d0d09554cc97336b4235ab95209c28efad6c773...f9e5ea7a5ad4795b6d9783c1a2d481d9297804cd)

###
[`v3.2.7-dev-20250913-9d0d095`](https://redirect.github.com/Luligu/matterbridge/compare/10831d3c40c83f61fea76b9f7f40c289866104b3...9d0d09554cc97336b4235ab95209c28efad6c773)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/10831d3c40c83f61fea76b9f7f40c289866104b3...9d0d09554cc97336b4235ab95209c28efad6c773)

###
[`v3.2.7-dev-20250909-10831d3`](https://redirect.github.com/Luligu/matterbridge/compare/3bb699e14625f719b2cb958e1c2a84a5de0daea0...10831d3c40c83f61fea76b9f7f40c289866104b3)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3bb699e14625f719b2cb958e1c2a84a5de0daea0...10831d3c40c83f61fea76b9f7f40c289866104b3)

###
[`v3.2.7-dev-20250908-3bb699e`](https://redirect.github.com/Luligu/matterbridge/compare/c623e4298ec055e5a224179add8e7fa8ef871836...3bb699e14625f719b2cb958e1c2a84a5de0daea0)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c623e4298ec055e5a224179add8e7fa8ef871836...3bb699e14625f719b2cb958e1c2a84a5de0daea0)

###
[`v3.2.7-dev-20250907-c623e42`](https://redirect.github.com/Luligu/matterbridge/compare/3.2.6...c623e4298ec055e5a224179add8e7fa8ef871836)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.2.6...c623e4298ec055e5a224179add8e7fa8ef871836)

</details>

<details>
<summary>Luligu/matterbridge-zigbee2mqtt
(matterbridge-zigbee2mqtt)</summary>

###
[`v2.8.0`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/blob/HEAD/CHANGELOG.md#280---2025-09-14)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/41664fb3d18fb175542831185f3774f2d1e05042...2.8.0)

##### Breaking changes

Some color conversion have been optimized to improve performnces.

It is possible that existing scenes on the controllers now render the
color in a different nuance.

If this is the case, update the color attributes in the controller
scenes.

##### Automations and scenes

The package
[zigbee2mqtt-automations](https://redirect.github.com/Luligu/zigbee2mqtt-automations)
has been updated to version 3.0.0 that includes also scenes.

##### Added

- \[adaptiveLighting]: Added support for **Apple Home Adaptive
Lighting**. See
<https://redirect.github.com/Luligu/matterbridge/discussions/390>.
- \[platform]: Optimized command handlers execution and perfomance when
the controllers send huge light scenes.
- \[devcontainer]: Added the plugin name to the container.
- \[devcontainer]: Improved performance of first build with shallow
clone.
- \[workflows]: The publish workflow now triggers automatically the
docker build of matterbridge.
- \[jest]: Added jest helper module v. 1.0.6.

##### Changed

- \[package]: Updated dependencies.
- \[package]: Updated package to Automator v. 2.0.6.
- \[workflows]: Ignore any .md anywhere.
- \[workflows]: Improved speed on Node CI.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v2.8.0-dev-20250915-41664fb`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/2f5e24e86da526a0aa9e48256cc9548263404c54...41664fb3d18fb175542831185f3774f2d1e05042)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/2f5e24e86da526a0aa9e48256cc9548263404c54...41664fb3d18fb175542831185f3774f2d1e05042)

###
[`v2.8.0-dev-20250912-2f5e24e`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/36784a2d250ec797ee98de865998b1a425b4e997...2f5e24e86da526a0aa9e48256cc9548263404c54)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/36784a2d250ec797ee98de865998b1a425b4e997...2f5e24e86da526a0aa9e48256cc9548263404c54)

###
[`v2.8.0-dev-20250911-36784a2`](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.7.0...36784a2d250ec797ee98de865998b1a425b4e997)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge-zigbee2mqtt/compare/2.7.0...36784a2d250ec797ee98de865998b1a425b4e997)

</details>

---

This PR was generated by [Mend Renovate](https://mend.io/renovate/).
View the [repository job
log](https://developer.mend.io/github/L2jLiga/ha-addons).

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiI0MS45Ny4xMCIsInVwZGF0ZWRJblZlciI6IjQxLjk3LjEwIiwidGFyZ2V0QnJhbmNoIjoibWFzdGVyIiwibGFiZWxzIjpbImRlcGVuZGVuY2llcyIsIm5vLXN0YWxlIl19-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>