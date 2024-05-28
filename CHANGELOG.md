# CHANGELOG

## [v1.0.0](https://github.com/NubeIO/rubix-ce/tree/v1.0.0) (2024-05-28)

- fixed point create form init issue (#1879)
- Update/limit history fetch size v1 (#1877)
- fixed dynamic output pin issue (#1881)
- Fix the issue with using new json schema (#1874)
- Show yellowish background for table items of networks/devices/points if disabled/fault (#1880)
- updated bacnet points table (#1875)
- updated bacnet point discovery table styles (#1865)
- fixed entity import mismatch warning messaging (#1870)
- Changes to identify and implement json-schema-form type object (#1869)
- fix deleting all hosts is not clearing up the host list (#1859)

## [v1.0.0-rc.9](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.9) (2024-05-16)

- Fix + create new location sometimes not showing up (#1854)
- Fix host creation from sidebar doesn't configure well (#1849)
- Small change for showing invalid datetime
- Add State, UpdatedAt fields & additional sorters in tables (#1844)
- Sort by rubix os version in host page (#1851)
- Remove unnecessary css styling causing issue with dashed variant antd button (#1850)
- Set boolean default and undefined output value to null (#1843)
- Increase version selector width and sort the versions (#1842)
- Fix: null pointer exception (#1827)
- Update/modbus baud rate override v1 (#1812)
- Added module enable after module installation (#1822)

## [v1.0.0-rc.8](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.8) (2024-04-24)

- Display version in RCE (#1821)

## [v1.0.0-rc.7](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.7) (2024-04-23)

- Bulk actions improvements & features (#1813)

## [v1.0.0-rc.6](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.6) (2024-04-18)

- Fix: cleanup plugins in download directory (#1818)

## [v1.0.0-rc.5](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.5) (2024-04-17)

- Add additional modules fields (#1795)
- Improvements/libraries (#1798)
- Bug/template restart check fix v2 (#1799)
- Updated lora icons (#1802)
- Updated alerts table tag function (#1811)
- Fix/hide maps v1 (#1803)
- Fixed mass edit table related row delete issues (#1800)
- Improvements on timezone (#1783)
- Support timezone typo change

## [v1.0.0-rc.4](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.4) (2024-04-03)

- Remove ROS dependencies (#1782)
- Wires folder node issue v1 (#1781)
- Add disable_periodic_rewrite node schema for flow point (#1785)

## [v1.0.0-rc.3](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.3) (2024-03-25)

- Fix: correct error message for ROS not installed scenario (#1773)
- Fix link builder v1 (#1775)
- Fix: template network install when there are no lorawan network present (#1769)

## [v1.0.0-rc.2](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.2) (2024-03-12)

- Add CC & BCC in email (#1763)
- Fix: module install from windows (#1765)

## [v1.0.0-rc.1](https://github.com/NubeIO/rubix-ce/tree/v1.0.0-rc.1) (2024-03-01)

- Templates update v1 (#1733)
- Add --server flag (#1732)
- Remove BACnet device discover duplicates (#1749)
- History quick time select v1 (#1750)
- Naming update v1 (#1748)
- Hide plugin page for none admin users (#1738)
- Add minimum rubix-os version support (#1741)
- Fix: dark mode context menu styling issue (#1756)
- Virtualized mapping tables (#1751)
- Updated bacnetmaster module name (#1759)

## [v0.3.3](https://github.com/NubeIO/rubix-ce/tree/v0.3.3) (2024-02-26)

- Merge pull request #1699 from NubeIO/table-refresh-fix-v1
- Add validation on EdgeBiosRubixOsOnEdgeInstall (#1704)
- Add type to RubixConnection and improvements on supervisor type (#1714)
- Merge pull request #1708 from NubeIO/improvement/get-repo-versions
- Fix: delete database for rubix-edge-wires (#1711)
- Merge pull request #1716 from NubeIO/1641-right-click-menu-off-bottom-of-screen
- Remove cleaning of entity name before dispatching it to server (#1720)
- Merge pull request #1710 from NubeIO/wires-drag-selection-fix-v1
- updated network wizard to work with modules (#1717)
- Merge pull request #1687 from NubeIO/update-node-settings-v1
- Import mismatch fix v1 (#1723)
- Fix: ros installation on edge ros is in stopped condition (#1729)
- Fix select version not working on Install Rubix OS (#1724)
- Fix ros restart timeout issues (#1730)
- Backup import error fix v1 (#1727)
- Commented network log tab (#1731)
- Hide tabs (#1744)
- Display points values as per the point's decimal value (#1745)

## [v0.3.2](https://github.com/NubeIO/rubix-ce/tree/v0.3.2) (2024-01-30)

- Merge pull request #1677 from NubeIO/virtualise-mass-edit-table-v1
- Merge pull request #1664 from NubeIO/batch-editor-update-v1
- Fix: windows icon on build (#1695)
- Merge pull request #1696 from NubeIO/JSON-import-styling-update-v1
- Fix: temp fix to show configure OpenVPN (#1700)

## [v0.3.1](https://github.com/NubeIO/rubix-ce/tree/v0.3.1) (2024-01-23)

- Fix: BACnet read API call (#1691)
- Fix UI overflowing (#1689)
- Refactoring sidebar supervisor menu and its refresh state logic (#1688)
- Fix schedules issues and improvements (#1690)
- Add support for text bases status on Widget Lock (#1692)

## [v0.3.0](https://github.com/NubeIO/rubix-ce/tree/v0.3.0) (2024-01-17)

- Support model movement change
- Upgrade ROS and its dependencies
- Support module schema API change
- Support module-core-rql API changes
- Add navigate menu feature
- Add focused mode feature
- Fix bacnet object #1625
- Column rearrange bug fix & removed unused code #1627
- Added API for write priority null #1629
- Priority array individual write v1 #1631
- Update readme for private repo dependencies download #1632
- Upgrade/module migration #1638
- Step connection style in wires v1 #1639
- Fixed CSV bulk update bug #1640
- Fix on supervisor switch view hides is not working in focused mode (#1655)
- Upgrade models & ROS versions (#1657)
- Supervisor menu column right click actions (#1656)
- Make dto and datatype changes (#1659)
- Sidebar menu items right clicks (#1658)
- Fix sidebar views are not refreshing (#1662)
- Correct locations/groups/hosts click context (#1663)
- Update sidebar menu items styling (#1665)
- Fix issue with creating subsequent hosts with default values (#1671)
- Added option to enable live mode for widget preview (#1670)
- Enable/Disable supervisor from the sidebar (#1667)
- Add additional context menu items of supervisors in sidebar menu (#1675)
- Make modules work same as plugins (#1679)
- Skip system plugin upload (#1683)
- Prerequisite:
    - rubix-os >= v0.3.0

## [v0.2.1](https://github.com/NubeIO/rubix-ce/tree/v0.2.1) (2023-12-06)

- Redo bacnet points discovery
- Fix crash on bulk update

## [v0.2.0](https://github.com/NubeIO/rubix-ce/tree/v0.2.0) (2023-12-05)

- Support API endpoint changes
- Improvement on the RQL editor layout
- Added template page
- Resize sidebar width by dragging
- Optimise table load time
- Updated Network, Device, & Points table context menu
- Give bulk action feature in location & group level
- Updated transaction & BACnet point discovery modal
- Prerequisite:
    - rubix-os >= v0.2.0

## [v0.1.5](https://github.com/NubeIO/rubix-ce/tree/v0.1.5) (2023-11-23)

- Upgrade nubeio-rubix-lib-models-go & misc changes
- Added template page
- Refactored RQL editor layout code
- Use Nube logo as the fallback image
- Misc bug fixes
- Prerequisite:
    - rubix-os >= v0.1.0

## [v0.1.4](https://github.com/NubeIO/rubix-ce/tree/v0.1.4) (2023-11-21)

- Fixed flow net & BACnet node input link issue
- Prerequisite:
    - rubix-os >= v0.0.90

## [v0.1.3](https://github.com/NubeIO/rubix-ce/tree/v0.1.3) (2023-11-20)

- Added ROS nodes in wires & made it so remote flow-networks will work
- Added copy to clipboard for networks/devices/points
- Let user select version on upgrade app
- Misc bug fixes
- Prerequisite:
    - rubix-os >= v0.0.90

## [v0.1.2](https://github.com/NubeIO/rubix-ce/tree/v0.1.2) (2023-11-13)

- ROS & Apps restart schedulers
- Email Dashboard
- Prerequisite:
    - rubix-os >= v0.0.88

## [v0.1.1](https://github.com/NubeIO/rubix-ce/tree/v0.1.1) (2023-10-24)

- Addition of pagination feature in networks, devices, & points page
- Tags improvement in network, device & point update
- Prerequisite:
    - rubix-os >= v0.0.73

## [v0.1.0](https://github.com/NubeIO/rubix-ce/tree/v0.1.0) (2023-10-12)

- First release
