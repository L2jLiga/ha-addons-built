Changes in this Release

<details><summary>8660c7e ⬆️ Update matterbridge to v3 (#133)</summary>
⬆️ Update matterbridge to v3 (#133)

This PR contains the following updates:

| Package | Change | Age | Adoption | Passing | Confidence |
|---|---|---|---|---|---|
|
[matterbridge](https://redirect.github.com/Luligu/matterbridge/blob/main/README.md)
([source](https://redirect.github.com/Luligu/matterbridge)) | `2.2.9` ->
`3.0.1` |
[![age](https://developer.mend.io/api/mc/badges/age/npm/matterbridge/3.0.1?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![adoption](https://developer.mend.io/api/mc/badges/adoption/npm/matterbridge/3.0.1?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![passing](https://developer.mend.io/api/mc/badges/compatibility/npm/matterbridge/2.2.9/3.0.1?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|
[![confidence](https://developer.mend.io/api/mc/badges/confidence/npm/matterbridge/2.2.9/3.0.1?slim=true)](https://docs.renovatebot.com/merge-confidence/)
|

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.0.1`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#301---2025-05-06)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/a1822952938d27ddf2a39fc8785cb738fce61ad7...3.0.1)

##### Added

- \[docker]: The builder for the **docker** image with tag **latest**
will run each day at 00:00 UTC if there are new releases. Inside the
image matterbridge and all plugins with the latest release (as published
on npm) are already loaded. You can just pull the new image and
matterbridge with all plugins will be updated to the latest.
- \[docker]: The builder for the **docker** image with tag **dev** will
run each day at 00:00 UTC if there are new commits. Inside the image
matterbridge and all plugins with the dev release (as pushed on GitHub)
are already loaded. You can just pull the new image and matterbridge
with all plugins will be updated to the latest dev. It is possible that
the devs are outdated by some published latests.
- \[npm]: The dev of matterbridge is published with tag **dev** on
**npm** each day at 00:00 UTC if there is a new commit. It is possible
that the dev is outdated by a published latest.
- \[frontend]: Added closeSnackbarMessage() to remove the notification
with timeout = 0.
-   \[frontend]: Moved all plugin actions from express to web socket.
-   \[frontend]: Moved all settings from express to web socket.
-   \[endpoint]: Added OperationalState cluster helper and behavior.
-   \[behaviors]: Added Jest test on MatterbridgeBehaviors.

##### Changed

-   \[package]: Updated dependencies.
-   \[docker]: Updated the [Docker configurations](README-DOCKER.md).
- \[frontend]: Changing configuration for a plugin now only lock
configuration on that plugin.
-   \[frontend]: Optimized rendering of Devices and Plugins panels.
-   \[frontend]: Frontend v.2.6.4.

##### Fixed

- \[BasicInformation]: Fixed vulnerability in BasicInformation and
BridgedDeviceBasicInformation cluster initialization attributes.
-   \[frontend]: Fixed refresh and postfix for select in HomeDevices.

###
[`v3.0.1-dev-20250507-a182295`](https://redirect.github.com/Luligu/matterbridge/compare/c77ed3608a333b3e0cfcbea6d19fcc26658259cc...a1822952938d27ddf2a39fc8785cb738fce61ad7)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c77ed3608a333b3e0cfcbea6d19fcc26658259cc...a1822952938d27ddf2a39fc8785cb738fce61ad7)

###
[`v3.0.1-dev-20250506-c77ed36`](https://redirect.github.com/Luligu/matterbridge/compare/cbd2c6e26a6913138d7c2a571a82a1a4d64c35a7...c77ed3608a333b3e0cfcbea6d19fcc26658259cc)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/cbd2c6e26a6913138d7c2a571a82a1a4d64c35a7...c77ed3608a333b3e0cfcbea6d19fcc26658259cc)

###
[`v3.0.1-dev-20250505-cbd2c6e`](https://redirect.github.com/Luligu/matterbridge/compare/1dd1d7e6ab994bba6966f9fb914ee3528cd3450a...cbd2c6e26a6913138d7c2a571a82a1a4d64c35a7)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/1dd1d7e6ab994bba6966f9fb914ee3528cd3450a...cbd2c6e26a6913138d7c2a571a82a1a4d64c35a7)

###
[`v3.0.1-dev-20250505-1dd1d7e`](https://redirect.github.com/Luligu/matterbridge/compare/c760ef893841bfaceb161b9c82d14eece7de2779...1dd1d7e6ab994bba6966f9fb914ee3528cd3450a)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c760ef893841bfaceb161b9c82d14eece7de2779...1dd1d7e6ab994bba6966f9fb914ee3528cd3450a)

###
[`v3.0.1-dev-20250504-c760ef8`](https://redirect.github.com/Luligu/matterbridge/compare/b7cccff612108867d2dc7a64a7627cc4d2b28f38...c760ef893841bfaceb161b9c82d14eece7de2779)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/b7cccff612108867d2dc7a64a7627cc4d2b28f38...c760ef893841bfaceb161b9c82d14eece7de2779)

###
[`v3.0.1-dev-20250504-b7cccff`](https://redirect.github.com/Luligu/matterbridge/compare/aa33494c96bbef6149eda59670c58e752aa11dd2...b7cccff612108867d2dc7a64a7627cc4d2b28f38)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/aa33494c96bbef6149eda59670c58e752aa11dd2...b7cccff612108867d2dc7a64a7627cc4d2b28f38)

###
[`v3.0.1-dev-20250504-aa33494`](https://redirect.github.com/Luligu/matterbridge/compare/966b0b423888446aee78a8cfa66883cc60fc0baf...aa33494c96bbef6149eda59670c58e752aa11dd2)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/966b0b423888446aee78a8cfa66883cc60fc0baf...aa33494c96bbef6149eda59670c58e752aa11dd2)

###
[`v3.0.1-dev-20250504-966b0b4`](https://redirect.github.com/Luligu/matterbridge/compare/6f217b41153e34e7234759905eb885acb3f9f178...966b0b423888446aee78a8cfa66883cc60fc0baf)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/6f217b41153e34e7234759905eb885acb3f9f178...966b0b423888446aee78a8cfa66883cc60fc0baf)

###
[`v3.0.1-dev-20250504-6f217b4`](https://redirect.github.com/Luligu/matterbridge/compare/3bfa0001be91bf2af569f990afb65d28224f9ee0...6f217b41153e34e7234759905eb885acb3f9f178)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3bfa0001be91bf2af569f990afb65d28224f9ee0...6f217b41153e34e7234759905eb885acb3f9f178)

###
[`v3.0.1-dev-20250504-3bfa000`](https://redirect.github.com/Luligu/matterbridge/compare/aa33494c96bbef6149eda59670c58e752aa11dd2...3bfa0001be91bf2af569f990afb65d28224f9ee0)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/aa33494c96bbef6149eda59670c58e752aa11dd2...3bfa0001be91bf2af569f990afb65d28224f9ee0)

###
[`v3.0.1-dev-20250503-aa33494`](https://redirect.github.com/Luligu/matterbridge/compare/466a8ecc76e72b785557cb8823808fa085d35c51...aa33494c96bbef6149eda59670c58e752aa11dd2)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/466a8ecc76e72b785557cb8823808fa085d35c51...aa33494c96bbef6149eda59670c58e752aa11dd2)

###
[`v3.0.1-dev-20250503-466a8ec`](https://redirect.github.com/Luligu/matterbridge/compare/71b796a1ff05cbc2455671985deb56dda37e5d18...466a8ecc76e72b785557cb8823808fa085d35c51)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/71b796a1ff05cbc2455671985deb56dda37e5d18...466a8ecc76e72b785557cb8823808fa085d35c51)

###
[`v3.0.1-dev-20250503-71b796a`](https://redirect.github.com/Luligu/matterbridge/compare/f37492364448b34524bd45302642b77572ca1715...71b796a1ff05cbc2455671985deb56dda37e5d18)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/f37492364448b34524bd45302642b77572ca1715...71b796a1ff05cbc2455671985deb56dda37e5d18)

###
[`v3.0.1-dev-20250502-f374923`](https://redirect.github.com/Luligu/matterbridge/compare/c002841e28de7d51b6a198fc49db211c7d4e8558...f37492364448b34524bd45302642b77572ca1715)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c002841e28de7d51b6a198fc49db211c7d4e8558...f37492364448b34524bd45302642b77572ca1715)

###
[`v3.0.1-dev-20250502-c002841`](https://redirect.github.com/Luligu/matterbridge/compare/7ffc38bc87f09d715a5087db5476a2eed9eb4bf6...c002841e28de7d51b6a198fc49db211c7d4e8558)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/7ffc38bc87f09d715a5087db5476a2eed9eb4bf6...c002841e28de7d51b6a198fc49db211c7d4e8558)

###
[`v3.0.1-dev-20250502-7ffc38b`](https://redirect.github.com/Luligu/matterbridge/compare/ef62ce529d458d1a2fd88ddaf1f0c79c4f12090c...7ffc38bc87f09d715a5087db5476a2eed9eb4bf6)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/ef62ce529d458d1a2fd88ddaf1f0c79c4f12090c...7ffc38bc87f09d715a5087db5476a2eed9eb4bf6)

###
[`v3.0.1-dev-20250502-6d36575`](https://redirect.github.com/Luligu/matterbridge/compare/f7acdd010f8d847dfbbb0623f1ec9af7b7659740...ef62ce529d458d1a2fd88ddaf1f0c79c4f12090c)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/f7acdd010f8d847dfbbb0623f1ec9af7b7659740...ef62ce529d458d1a2fd88ddaf1f0c79c4f12090c)

###
[`v3.0.1-dev-20250501-4f463f9`](https://redirect.github.com/Luligu/matterbridge/compare/d9f7d943cf75edf346d25845b3ec640d584baf30...f7acdd010f8d847dfbbb0623f1ec9af7b7659740)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/d9f7d943cf75edf346d25845b3ec640d584baf30...f7acdd010f8d847dfbbb0623f1ec9af7b7659740)

###
[`v3.0.1-dev-20250430-a3ea2b7`](https://redirect.github.com/Luligu/matterbridge/compare/3.0.0...d9f7d943cf75edf346d25845b3ec640d584baf30)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.0.0...d9f7d943cf75edf346d25845b3ec640d584baf30)

###
[`v3.0.0`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#300---2025-04-29)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/49eae51abc93a75bf463f4a71affb26fa6ab2dd1...3.0.0)

###
[`v3.0.0-edge.16`](https://redirect.github.com/Luligu/matterbridge/compare/adce437e894c6b329178693782e5b1bfd9bda3dc...49eae51abc93a75bf463f4a71affb26fa6ab2dd1)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/adce437e894c6b329178693782e5b1bfd9bda3dc...49eae51abc93a75bf463f4a71affb26fa6ab2dd1)

###
[`v3.0.0-edge.15`](https://redirect.github.com/Luligu/matterbridge/compare/64fd1f7d1fc79180f0ad26046c90dd6a4769454f...adce437e894c6b329178693782e5b1bfd9bda3dc)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/64fd1f7d1fc79180f0ad26046c90dd6a4769454f...adce437e894c6b329178693782e5b1bfd9bda3dc)

###
[`v3.0.0-edge.14`](https://redirect.github.com/Luligu/matterbridge/compare/6ba971cb082484c6a9fd3e022ebcc1ef314e2d2f...64fd1f7d1fc79180f0ad26046c90dd6a4769454f)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/6ba971cb082484c6a9fd3e022ebcc1ef314e2d2f...64fd1f7d1fc79180f0ad26046c90dd6a4769454f)

###
[`v3.0.0-edge.13`](https://redirect.github.com/Luligu/matterbridge/compare/0534614e166e17393ba5cf40ad0ad3c2bca56aa9...6ba971cb082484c6a9fd3e022ebcc1ef314e2d2f)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/0534614e166e17393ba5cf40ad0ad3c2bca56aa9...6ba971cb082484c6a9fd3e022ebcc1ef314e2d2f)

###
[`v3.0.0-edge.12`](https://redirect.github.com/Luligu/matterbridge/compare/187c977f915ab8cfccdf48e7bc8910e015144098...0534614e166e17393ba5cf40ad0ad3c2bca56aa9)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/187c977f915ab8cfccdf48e7bc8910e015144098...0534614e166e17393ba5cf40ad0ad3c2bca56aa9)

###
[`v3.0.0-edge.11`](https://redirect.github.com/Luligu/matterbridge/compare/c06f46fff3489dd7e4db0acc6b9ecd9875dc85f3...187c977f915ab8cfccdf48e7bc8910e015144098)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c06f46fff3489dd7e4db0acc6b9ecd9875dc85f3...187c977f915ab8cfccdf48e7bc8910e015144098)

###
[`v3.0.0-edge.10`](https://redirect.github.com/Luligu/matterbridge/compare/8f4346c007fe8548edd587ef1c796c028f340e4b...c06f46fff3489dd7e4db0acc6b9ecd9875dc85f3)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/8f4346c007fe8548edd587ef1c796c028f340e4b...c06f46fff3489dd7e4db0acc6b9ecd9875dc85f3)

###
[`v3.0.0-edge.8`](https://redirect.github.com/Luligu/matterbridge/compare/8f4346c007fe8548edd587ef1c796c028f340e4b...8f4346c007fe8548edd587ef1c796c028f340e4b)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/8f4346c007fe8548edd587ef1c796c028f340e4b...8f4346c007fe8548edd587ef1c796c028f340e4b)

###
[`v3.0.0-edge.7`](https://redirect.github.com/Luligu/matterbridge/compare/c279ed8606eb6f11e6f8ea971def6c6fc428a796...8f4346c007fe8548edd587ef1c796c028f340e4b)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c279ed8606eb6f11e6f8ea971def6c6fc428a796...8f4346c007fe8548edd587ef1c796c028f340e4b)

###
[`v3.0.0-edge.6`](https://redirect.github.com/Luligu/matterbridge/compare/c279ed8606eb6f11e6f8ea971def6c6fc428a796...c279ed8606eb6f11e6f8ea971def6c6fc428a796)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c279ed8606eb6f11e6f8ea971def6c6fc428a796...c279ed8606eb6f11e6f8ea971def6c6fc428a796)

###
[`v3.0.0-edge.5`](https://redirect.github.com/Luligu/matterbridge/compare/48f02880d43826620b07834dd48ad8db3a878c0b...c279ed8606eb6f11e6f8ea971def6c6fc428a796)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/48f02880d43826620b07834dd48ad8db3a878c0b...c279ed8606eb6f11e6f8ea971def6c6fc428a796)

###
[`v3.0.0-edge.4`](https://redirect.github.com/Luligu/matterbridge/compare/64bd6f7c9a504612ea97ec3eb0a24d84aadc8e6e...48f02880d43826620b07834dd48ad8db3a878c0b)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/64bd6f7c9a504612ea97ec3eb0a24d84aadc8e6e...48f02880d43826620b07834dd48ad8db3a878c0b)

###
[`v3.0.0-edge.3`](https://redirect.github.com/Luligu/matterbridge/compare/ccd0260a8e942fd666630b05f2abe4e5dd0a4218...64bd6f7c9a504612ea97ec3eb0a24d84aadc8e6e)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/ccd0260a8e942fd666630b05f2abe4e5dd0a4218...64bd6f7c9a504612ea97ec3eb0a24d84aadc8e6e)

###
[`v3.0.0-edge.2`](https://redirect.github.com/Luligu/matterbridge/compare/3d8baf54a842f1e664755a256ef5fa8842face3a...ccd0260a8e942fd666630b05f2abe4e5dd0a4218)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3d8baf54a842f1e664755a256ef5fa8842face3a...ccd0260a8e942fd666630b05f2abe4e5dd0a4218)

###
[`v3.0.0-edge.1`](https://redirect.github.com/Luligu/matterbridge/compare/2.2.9...3d8baf54a842f1e664755a256ef5fa8842face3a)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/2.2.9...3d8baf54a842f1e664755a256ef5fa8842face3a)

</details>

---

### Configuration

📅 **Schedule**: Branch creation - At any time (no schedule defined),
Automerge - At any time (no schedule defined).

🚦 **Automerge**: Disabled by config. Please merge this manually once you
are satisfied.

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

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiIzOS4yNjQuMCIsInVwZGF0ZWRJblZlciI6IjM5LjI2NC4wIiwidGFyZ2V0QnJhbmNoIjoibWFzdGVyIiwibGFiZWxzIjpbImRlcGVuZGVuY2llcyIsIm5vLXN0YWxlIl19-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>