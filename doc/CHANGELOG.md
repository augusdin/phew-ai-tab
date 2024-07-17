# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

### Added
- 

### Fixed
- 

### Changed
-

## [alpha-0.2.1] - 2024.7-15

### Added
- [New] AI grouping and domain grouping now support sorting groups by the number of tabs, disabled by default
- [New] After AI grouping, tabs within groups can be further sorted by domain, enabled by default
- [New] Option to disable continuous automatic grouping. When disabled, clicking the group button performs grouping only once. Automatic grouping is enabled by default
- [New] Ability to delete grouping rules, useful for reverting unsatisfactory AI grouping results
- [New] Added premium user plan, supporting grouping with GPT4o
- [New] Added "explanation" field for AI grouping, viewable in the Options page to understand AI grouping rationale and improve grouping effectiveness

### Fixed
- Resolved the issue of tab item focus loss during sliding

### Changed
- [Improved] Tab item height, making tabs more compact
- [Improved] AI grouping effectiveness, enhancing consistency, stability, and accuracy of groupings
- [Improved] In the Space list, the current Space is now placed at the end of the list for easier operation
- [Changed] Due to suboptimal user experience, the page preview feature is temporarily suspended. It will return next month with improved usability

## [alpha-0.2.0] - 2024.5-9

### Added
- 

### Fixed
- [Fixed] Issues with domain grouping
- [Fixed] Problem of repeated grouping when Emoji is enabled during AI grouping

### Changed
- [Improved] Enhanced AI grouping speed by reducing prompt word count (only reducing descriptive content)

## [alpha-0.1.9] - 2024.5-8

### Added
- 

### Fixed
- [Fixed] Bug in generating Space names when Spaces are unavailable
- [Fixed] Issue of losing pinned tabs when switching Spaces

### Changed
- 

## [alpha-0.1.8] - 2024.5-8

### Added
- [New] Moved "Unlink all groups" from the main menu to the AI Grouping button menu
- [New] Display loading status when automatically naming Spaces
- [New] Custom model naming (limited to Pro and LTD users)
- [New] Shortcut to shuffle all tabs in the current window

### Fixed
- 

### Changed
- [Changed] Moved the Space dialog to the bottom
- [Changed] Upgraded the payment system
- [Optimized] Optimized the style of the Space list, increased recognizability, and displayed the creation date of the Spaces

## [alpha-0.1.7] - 2024.4-29

### Added
- [New] New feature to export tab information under the export window as CVS, supporting all types of windows including current, suspended, pinned, and historical data
- [New] Global search based on AI analysis of tab content
- [New] Added emojis to Space automatic naming for easier identification
- [New] Display the category of the window at the bottom of the sidebar window (requires AI page analysis to be enabled)

### Fixed
- [Fixed] Fixed the issue with switching to a new Space
- [Fixed] Renamed suspended and pinned Windows
- [Fixed] Fixed the issue where group names updated in version 0.1.2 could not be updated in group rules
- [Fixed] Fixed the problem of space windows remaining empty after deleting suspended, pinned, and historical lists
- [Fixed] Further reduced the frequency of requests to the server when analyzing pages
- [Fixed] Issue with frequent toast notifications when grouping by domain
- [Fixed] Compatibility issue with Chrome tab loading states occasionally malfunctioning
- [Fixed] Incorrect settings when enabling domain grouping
- [Fixed] Bug missing pinned windows when creating default Spaces locally

### Changed
- [Changed] Renamed "favorites" to "pins," fully implementing edit functions like pin, delete, and rename, with encryption and syncing to the server
- [Changed] AI page analysis and previews are off by default
- [Optimized] Enhanced toolbar icon display
- [Optimized] Major interface overhaul, simplified UI elements
- [Updated] Upgraded to the latest OpenAI gpt-3.5-turbo model

## [alpha-0.1.6] - 2024.4-29

### Added
- [New] Shortcut Ctrl+Shift+C to close all tabs in the current group

### Fixed
- [Fixed] Issue with frequent server analysis requests
- [Fixed] Potential issues when switching Spaces

### Changed
- [Optimized] Improved performance of multi-end automatic synchronization

## [alpha-0.1.5] - 2024.4-28

### Added
- [New] Shortcut Command+E to toggle between "Expand all groups" and "Collapse other groups" (Alt+Shift+E on Windows)
- [New] Shortcut Command+Shift+U to ungroup all current groups (Ctrl+Shift+U on Windows)
- [New] Shortcut Ctrl+Shift+N to create a new Space
- [New] Reserved slot for "Expand all groups" for custom shortcut configuration
- [New] Reserved slot for "Begin AI Grouping" for custom shortcut configuration

### Fixed
- 

### Changed
- [Optimized] Upgraded "Expand all groups" button to toggle group expansion state

## [alpha-0.1.4] - 2024.4-27

### Added
- 

### Fixed
- [Fixed] Compatibility with old grouping rules

### Changed
- 

## [alpha-0.1.3] - 2024.4-27

### Added
- [New] Export and import of grouping rules (supports old versions)

### Fixed
-

### Changed
- 

## [alpha-0.1.2] - 2024.4-27

### Added
- [New] One-click recovery of all magic suspended tabs
- [New] Space management
- [New] AES 256 military-grade encryption for local and remote data synchronization, ensuring that all tab data under a Space can only be accessed by the user.
- [New] Multi-end cloud synchronization (Pro, LTD users)
- [New] LTD users can privately deploy Space data to Supabase
- [New] New tab card supporting AI summary of opened pages (Pro, LTD users)
- [New] AI grouping supports emojis (Pro, LTD users)
- [New] AI grouping supports custom categorization
- [New] Automatic translation of AI grouping into browser interface language
- [New] Search all tabs under the current Space based on AI summary content
- [New] Automatic naming of new Spaces (Pro, LTD users)

### Fixed
-

### Changed
- [Optimized] Improved grouping effect
- [Optimized] Enhanced page preview effect, using server-side screenshots to completely avoid issues caused by local screenshots. (Pro, LTD users)
- [Optimized] AI grouping supports subdomains
- [Optimized] Reduced memory usage, improved sidebar performance.

## [alpha-0.1.1] - 2024-3-15

### Added
- 

### Fixed
- 

### Changed
- Reduced unnecessary re-renders, improved sidebar performance

## [alpha-0.1.0] - 2024-3-8

### Added
- 

### Fixed
- [Fixed] Critical online bug

### Changed
- 

## [alpha-0.0.9] - 2024-3-8

### Added
- 

### Fixed
- [Fixed] Google account login issue

### Changed
- [Added] User avatar customization; users can change their avatar in the personal center after logging in
- [Added] Account deletion; users can delete their account in the personal center after logging in


## [alpha-0.0.8] - 2024-3-8

### Added
- [New] User system is online, log in to use plugins without the need for serial numbers and API Keys
- [New] Window titles are automatically renamed based on the domain and title of the tabs with the highest count (custom modifications are not supported in this version, will be restored in the next version)
- [New] New "Domain Merging" feature, which automatically groups tabs with the same domain together and displays the domain name clearly
- [New] New "Inter-window Domain Merging" feature, if a domain opened is already present in another window, it will automatically merge into that window (premium members feature)

### Fixed
- [Fixed] Fixed issues with window panel expansion
- [Fixed] List stuttering and high memory usage
- [Fixed] Continuous issues with Group Switch not turning on or off

### Changed
- New magic tab suspension display format, now suspended pages are displayed more clearly and intuitively
- Magic suspension is now enabled by default (premium members feature), with an interval of 24 hours
- After clicking on search results, returns to the main interface
- Default behavior collapses windows other than the current window, remembers expand/collapse action after one operation
- Temporarily defaults to disabling the webpage screenshot preview feature (to be fully fixed in the next version)

## [alpha-0.0.7] - 2023-1-15

### Added

### Fixed
- [Fixed] The issue where the preview feature was ineffective (pages opened before installing the plugin need to be refreshed to show preview screenshots).
- [Fixed] Lagging issues with sidepanel tabs (introduced in version 0.0.6).
- [Fixed] Instances where automatic magic suspension was ineffective.
- [Fixed] Misalignment between the order of tabs in the sidepanel and the browser tabs.
- [Fixed] Issues related to the logic of automatic scrolling.

### Changed
-

## [alpha-0.0.6] - 2023-1-15

### Added
- [New] Page screenshot preview feature: when the mouse hovers over the sidebar tab icons, a preview of the tab's page screenshot pops up (Pro version feature, known issues with incorrect screenshots on sites like YouTube, to be fixed in future updates).
- [New] Magic Suspension feature: close tabs or windows and save them in the sidebar. Clicking on the suspended tab restores it to its original location, thereby freeing browser tabs from computer memory limitations. Suspended tabs remain effective even after reopening the browser, replacing the previous window cache feature.
- [New] Automatic Magic Suspension, with an option to set the suspension interval, defaulting to every 30 minutes (Pro version feature).
- [New] Magic Suspension whitelist, supporting specifications via URL, domain name, and regular expression for pages that should never be suspended. It's also possible to add the current page URL to the whitelist from the window options (Pro version feature).
- [New] Sidebar automatically scrolls to the tab of the current page (default option, can be disabled in settings).
- [New] Automatically collapses groups other than the one containing the current tab (non-default option, needs to be enabled in settings).
- [New] Tab hover and selection display address.
- [New] Group operation buttons, allowing for changing group color, disbanding groups, closing windows within a group, moving groups to a new window, and other operations.
- [New] Display of the last visit time outside the current window.

### Fixed
- [Fixed] A formatting error in OpenAI's return causing the group rule configuration panel to crash.
- [Fixed] An issue where group colors were easily duplicated.

### Changed
- Tabs now hide URLs by default.
- Automatic pre-group sorting changed to a non-default option, needs to be enabled in settings.
- Improved AI grouping accuracy.
- [Optimized] Enhanced sidebar interaction logic.
- [Optimized] Improved sidebar display style.
- [Optimized] Significantly faster grouping speed.


## [alpha-0.0.5] - 2023-12-27

### Added
- Added compatibility with Great Suspender-like extensions for suspended tabs.
- Added alphabetical sorting of tabs within windows.
- Introduced a shortcut Command+Shift+P (Ctrl+Shift+P on Windows) to toggle the sidebar.
- Added an option to change the panel position.
- Introduced a cohesive group display style, set as the default. The previous tag style (more prominent) can be switched back in the options.
- Added OpenAI Proxy URL configuration.
- Launched a visual editor for AI grouping rules.
- Added display of tab URLs, enabled by default, with an option to hide it.

### Fixed
- Fixed the issue of plugin grouping affecting pinned tabs.
- Resolved automatic grouping malfunctions in certain scenarios.
- Fixed styling issues during dragging.
- Resolved the problem of dragging leading to multiple selections.
- Fixed the inability to search within suspended, bookmarked, and history windows.
- Improved search box accuracy and performance; the search function is now significantly more powerful than the browser's built-in feature.
- [Critical] Fixed the issue of repeated group rules accumulating, causing chaos in grouping logic.

### Changed
- Optimized the display of tab icons.
- Enhanced click response performance.
- Significantly improved sidebar performance.
- Enabling AI grouping now automatically turns on auto-grouping.

## [alpha-0.0.4] - 2023-12-25

### Added
-

### Fixed
- Fixed the issue where having more than a certain number of tabs (e.g., 100) could lead to group timeouts.
- Fixed the issue where groups were incorrectly identified as different due to case sensitivity in names.
- Fixed the issue where automatic grouping was not effective.

### Changed
- Optimized the OpenAI request algorithm to reduce the amount of data requested, enhancing the speed and effectiveness of grouping.
- Rewrote AI grouping rules to process requests in batches of 60 effective tabs.
- The default internal grouping rules are now displayed in the settings panel and can be modified by the user.
- Improved the visibility of the color bars on the right side of the sidebar for easier group identification.


## [alpha-0.0.3] - 2023-12-18

### Added
- 

### Fixed
- Fixed the issue of AI grouping not matching Chrome browser language (now using Chrome's UI default language).
- Fixed the AI grouping rules cache invalidation issue causing frequent OpenAI requests.
- Fixed the issue where chrome:// pages were incorrectly processed during grouping.

### Changed
- Added some grouping categories to enhance the AI grouping effect.
- Improved the continuous AI grouping algorithm in automatic grouping mode.
- Tabs are now sorted before AI grouping.


## [alpha-0.0.2] - 2023-12-17

### Added
- Added sorting by domain.
- Added grouping by domain.
- Added feature to change window names with a click.
- Added feature to change group names with a click (automatically updates rules).
- Added count of tabs under windows and groups.

### Fixed
- Fixed issues with breaking styles on some pages and problems with upgrade pop-ups not appearing.
- Fixed the issue of not syncing tab order changes.
- Partially resolved the issue of auto grouping not working (however, there are still issues with window states affecting each other).

### Changed
- 
