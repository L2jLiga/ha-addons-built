Changes in this Release

<details><summary>10142a3 feat: added docker flag to indicate that matterbridge is running in container</summary>
feat: added docker flag to indicate that matterbridge is running in container</details>

<details><summary>a2ecd76 Update MatterBridge</summary>
Update MatterBridge 

<details>
<summary>MatterBridge 1.2.18 -> 1.2.20</summary>

## [1.2.20] - 2024-06-03

### Changed
- [matter.js]: Update to @project-chip/matter-node.js v. 0.9.1
- [matterbridge]: Updated dependencies

### Fixed
- [matterbridge]: Log level of Plugin already configured is now info

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="./yellow-button.png" alt="Buy me a coffee" width="120">
</a>

## [1.2.19] - 2024-06-01

### Breaking change on Matterbridge start!
Now the plugins load and start before the controller connects.
A special thank to Tamer Salah (https://github.com/tammeryousef1006) for his help testing all controllers.

### Changed
- [matterbridge]: In bridge mode the plugins are loaded and started immediately
- [matterbridge]: In child bridge mode the plugins are loaded and started immediately
- [matterbridge]: Updated dependencies

### Fixed
- [frontend]: Fixed the error badge in the registered plugins window
- [frontend]: Added tooltip to the plugin update badge in the registered plugins window

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="./yellow-button.png" alt="Buy me a coffee" width="120">
</a>
</details>

<details>
<summary>MatterBridge Z2M 2.0.14 -> 2.0.15</summary>

## [2.0.15] - 2024-06-01

### Added

- [dependencies]: Update dependencies
- [matterbridge]: Adapted the code to the new start mode of Matterbridge. 

<a href="https://www.buymeacoffee.com/luligugithub">
  <img src="./yellow-button.png" alt="Buy me a coffee" width="120">
</a>

</details></details>