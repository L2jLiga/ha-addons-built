Changes in this Release

<details><summary>f3af222 ⬆️ Update matterbridge to v3.2.9 (#170)</summary>
⬆️ Update matterbridge to v3.2.9 (#170)

Coming soon: The Renovate bot (GitHub App) will be renamed to Mend. PRs
from Renovate will soon appear from 'Mend'. Learn more
[here](https://redirect.github.com/renovatebot/renovate/discussions/37842).

---

### Release Notes

<details>
<summary>Luligu/matterbridge (matterbridge)</summary>

###
[`v3.2.9`](https://redirect.github.com/Luligu/matterbridge/blob/HEAD/CHANGELOG.md#329---2025-09-27)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/bb89bea5d1d0e558df693c455fe73473d521aecd...3.2.9)

##### Breaking Changes

- \[profiles]: Profile management has changed. Now, each profile has its
own independent directories under `profiles` with storage,
matterstorage, plugin config, and plugin directory. This means that if
you are using profiles, Matterbridge will not find the old profile data.
The new profile management allows to run multiple instances of
matterbridge (change the frontend port and the matter port for each
profile) or to simply make a test of a new plugin without modifing your
production setup.

##### Added

- \[frontend]: Bumped `frontend` version to 3.1.0. Now, 100% on
typescript and fully typed with the backend.
- \[frontend]: Removed legacy `react-table` and created an autonomous
component `MbfTable`. Features: unique UI for all tables with integrated
column sorting and column selection.
- \[frontend]: Use MbfTable for Plugins, Devices, Registered devices and
Clusters tables.
- \[frontend]: Optimized WebSocker message handlers. Now, the handler
targets the component.
- \[frontend]: Removed dangerouslySetInnerHTML from log rendering.
- \[frontend]: Added push update to Icon view and table view cluster
panel. Now, they updates data in real time.
- \[frontend]: Added install progress dialog when installing or
uploading packages.
- \[endpoint]: Added occupancy feature to all Thermostat cluster
helpers. When provided (either false or true) it will create a
Thermostat with occupancy feature.
- \[endpoint]: Added outdoorTemperature to all Thermostat cluster
helpers. Default is undefined (it will be ignored).

##### Changed

- \[matter]: Bumped `matter.js` version to 0.15.4. Thanks matter.js!
- \[package]: Updated dependencies.

##### Fixed

- \[frontend]: Fix default values (devices) for homePageMode
(logs/devices) in MatterbridgeSettings.

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="bmc-button.svg" alt="Buy me a coffee" width="80">
</a>

###
[`v3.2.9-dev-20250926-bb89bea`](https://redirect.github.com/Luligu/matterbridge/compare/85736bb1f3245824f27c7b31a553e50605a6aaa3...bb89bea5d1d0e558df693c455fe73473d521aecd)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/85736bb1f3245824f27c7b31a553e50605a6aaa3...bb89bea5d1d0e558df693c455fe73473d521aecd)

###
[`v3.2.9-dev-20250926-85736bb`](https://redirect.github.com/Luligu/matterbridge/compare/c639a33217ddd695f5f599fbbed9a9d88b2b52ca...85736bb1f3245824f27c7b31a553e50605a6aaa3)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/c639a33217ddd695f5f599fbbed9a9d88b2b52ca...85736bb1f3245824f27c7b31a553e50605a6aaa3)

###
[`v3.2.9-dev-20250924-c639a33`](https://redirect.github.com/Luligu/matterbridge/compare/9417698fad74c1fae1d7cc2f792bb4228cae726f...c639a33217ddd695f5f599fbbed9a9d88b2b52ca)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/9417698fad74c1fae1d7cc2f792bb4228cae726f...c639a33217ddd695f5f599fbbed9a9d88b2b52ca)

###
[`v3.2.9-dev-20250924-9417698`](https://redirect.github.com/Luligu/matterbridge/compare/2e9594f5918f4af006b7ca4b587fdf0887abd638...9417698fad74c1fae1d7cc2f792bb4228cae726f)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/2e9594f5918f4af006b7ca4b587fdf0887abd638...9417698fad74c1fae1d7cc2f792bb4228cae726f)

###
[`v3.2.9-dev-20250924-2e9594f`](https://redirect.github.com/Luligu/matterbridge/compare/359572c7a7f704bf7f4fae609e8d70d0f13d16dc...2e9594f5918f4af006b7ca4b587fdf0887abd638)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/359572c7a7f704bf7f4fae609e8d70d0f13d16dc...2e9594f5918f4af006b7ca4b587fdf0887abd638)

###
[`v3.2.9-dev-20250923-359572c`](https://redirect.github.com/Luligu/matterbridge/compare/517cae7b2cd9b17b3dbbaced720506965e637c18...359572c7a7f704bf7f4fae609e8d70d0f13d16dc)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/517cae7b2cd9b17b3dbbaced720506965e637c18...359572c7a7f704bf7f4fae609e8d70d0f13d16dc)

###
[`v3.2.9-dev-20250922-517cae7`](https://redirect.github.com/Luligu/matterbridge/compare/6e00637d4216c3a3e83faf3fd8c3b453e7d3ac9d...517cae7b2cd9b17b3dbbaced720506965e637c18)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/6e00637d4216c3a3e83faf3fd8c3b453e7d3ac9d...517cae7b2cd9b17b3dbbaced720506965e637c18)

###
[`v3.2.9-dev-20250922-6e00637`](https://redirect.github.com/Luligu/matterbridge/compare/3.2.8...6e00637d4216c3a3e83faf3fd8c3b453e7d3ac9d)

[Compare
Source](https://redirect.github.com/Luligu/matterbridge/compare/3.2.8...6e00637d4216c3a3e83faf3fd8c3b453e7d3ac9d)

</details>

---

This PR was generated by [Mend Renovate](https://mend.io/renovate/).
View the [repository job
log](https://developer.mend.io/github/L2jLiga/ha-addons).

<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiI0MS4xMzAuMSIsInVwZGF0ZWRJblZlciI6IjQxLjEzMC4xIiwidGFyZ2V0QnJhbmNoIjoibWFzdGVyIiwibGFiZWxzIjpbImRlcGVuZGVuY2llcyIsIm5vLXN0YWxlIl19-->

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com></details>