# SignalCheck Pro changelog

<p><em>Alpha testing now:</em></p>
<ul style="list-style-type: circle;">
<li><span style="color: #999999;"><del>Added full Dual-SIM compatibility.</del></span></li>
<li>Disabled beta option to display pending web entries on main screen due to crashes.</li>
<li>Updated numerous libraries.</li>
</ul>
<p><em>Beta testing now, likely to be included in next public release:</em></p>
<ul style="list-style-type: circle;">
<li><em><span style="text-decoration: underline;">Beta 4.712b (5/23/2022):</span></em></li>
<li>Improved app stability and reduced ANRs.</li>
<li>Optimized location service auto-restart function.</li>
<li>Reduced app size with leaner Google Play library.</li>
<li>Removed Sprint 1&#215;800 features.</li>
<li>Resolved force closes on Android 12+ devices when no cells were connected.</li>
<li><em><span style="text-decoration: underline;">Beta 4.711b (5/22/2022):</span></em></li>
<li>Added swipe-to-refresh feature on main screen.</li>
<li>Adjusted location service to automatically restart if the device location is 10 minutes old.</li>
<li>Adjusted web uploads to include NR data without a valid TAC.</li>
<li>Implemented new cell identification methods for Android 12+ devices.</li>
<li>Numerous minor display improvements.</li>
<li>Updated numerous libraries.</li>
<li>Updated target API to Android 12L.</li>
</ul>
<p><strong>Version 4.71 (Released 2/16/2022):</strong></p>
<ul>
<li>Added 5G-NR band/frequency status bar icons.</li>
<li>Added &#8220;Band&#8221; status bar icon option to only display &#8220;n#&#8221;/&#8221;B#&#8221; when connected to NR/LTE.</li>
<li>Added new menu option for non-beta users to export web data for manual upload.</li>
<li>Added non-standalone 5G-NR frequency information on some Android 12 devices.</li>
<li>Added option to add suffix to exported log files.</li>
<li>Added option to control automated checks for app updates at startup.</li>
<li>Added option to display location timestamp on main screen.</li>
<li>Adjusted 5G-NR NCI values displayed for some providers.</li>
<li>Changed web upload progress dialog box to a notification.</li>
<li>Disabled support for Android 4.0 – 4.4W.</li>
<li>Improved handling of log database backup failures.</li>
<li>Improved identification of 5G-NR bands on Android 11+ devices.</li>
<li>Improved identification of 5G-NR band n77.</li>
<li>Improved identification of connected network type on Android 7+ devices.</li>
<li>Improved identification of out-of-network cells.</li>
<li>Improved preferences accessibility.</li>
<li>Improved Site Note matching between T-Mobile/Sprint PLMNs.</li>
<li>Improved validation of 5G-NR NCI values.</li>
<li>Overhauled import/export/backup functions; users can now configure folder location.</li>
<li>Removed need for WRITE_EXTERNAL_STORAGE permission.</li>
<li>Removed Splunk crash reporting.</li>
<li>Removed unused tables and columns from the Logger database.</li>
<li>Resolved force closes on some devices related to notification channels.</li>
<li>Resolved force closes on some devices when app does not fully initialize quickly enough.</li>
<li>Resolved issue with duplicate 5G-NR Site Notes.</li>
<li>Resolved issue with extra blank lines on non-standalone 5G-NR display.</li>
<li>Resolved issue with improperly formatted GCI and NCI values on exported logs.</li>
<li>Resolved issue with invalid 5G-NR NCI and TAC values displaying.</li>
<li>Resolved issue with invalid Mobile connection block displaying on main screen.</li>
<li>Resolved issue with invalid provider or PLMN displayed on some devices.</li>
<li>Updated numerous libraries.</li>
<li>Updated target API to Android 12.</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.68 (Released 10/23/2021):</strong></span></p>
<ul>
<li>Added 5G-NR neighbor cell display.</li>
<li>Added new Shentel PLMN.</li>
<li>Added option to display location timestamp.</li>
<li>Added option to display LTE/NR cell ID in hexadecimal format with sector.</li>
<li>Adjusted scale of colored signal strength graphic bars.</li>
<li>Changed site note &amp; icon lock option to be two separate options.</li>
<li>Improved 5G-NR information on some devices.</li>
<li>Improved internal crash reporting routines.</li>
<li>Invalidated location accuracy value stored in Trail Log if device location timestamp is stale.</li>
<li>Moved Change Log button to About menu.</li>
<li>Moved Send Diagnostics button to Help menu.</li>
<li>Resolved force closes on some Android 10 devices.</li>
<li>Resolved force closes related to Purchase screen.</li>
<li>Resolved force closes when importing a database created in a newer version of the app.</li>
<li>Resolved issue with CDMA 1X BSL remaining on screen after 1X connection is lost.</li>
<li>Resolved issue with incorrect 5G-NR bands displaying on some networks.</li>
<li>Resolved issue with incorrect 5G-NR ECI values with sectors.</li>
<li>Resolved issue with location display appearing when Location Service was disabled.</li>
<li>Resolved issue with LTE cells not being logged on certain networks.</li>
<li>Resolved issue with some NR channel frequencies not rounding to two decimal places.</li>
<li>Updated compile API to Android 12.</li>
<li>Updated numerous libraries.</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.67 (Released 3/29/2021):</strong></span></p>
<ul>
<li>Added one-time popup to comply with Google Play background location policy. (Pro)</li>
<li>Changed location accuracy precision to one decimal place. (Pro)</li>
<li>Changed location accuracy to display in feet if metric units are not enabled. (Pro)</li>
<li>Improved PLMN ID validation.</li>
<li>Resolved force closes on some devices when connected to GSM/WCDMA networks.</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.66 (Released 3/23/2021):</strong></span></p>
<ul>
<li>Added option to display location accuracy on the main screen. (Pro)</li>
<li>Added toggling of Location Service, Site Logger, and Trail Logger features by clicking on the icons on the main screen. (Pro)</li>
<li>Changed location coordinates to update on main screen in real-time, independent of mobile signal updates. (Pro)</li>
<li>Changed LTE band 13 to display as LTE 750.</li>
<li>Changed pending diagnostic reports to use app cache; eliminates need for Storage permission to send reports.</li>
<li>Changed site note lock option to also lock Location/Site/Trail buttons. (Pro)</li>
<li>Code optimizations and enhancements.</li>
<li><del>Resolved force closes on some Android 10 devices.</del></li>
<li>Resolved force closes on some devices when attempting to update site notes. (Pro)</li>
<li><del>Resolved force closes on some devices when connected to a WCDMA network.</del></li>
<li>Resolved force closes when root modem functions were enabled. (Pro)</li>
<li><del>Resolved issue with CDMA 1X BSL remaining on screen after 1X connection is lost. (Pro)</del></li>
<li>Resolved issue with cell ID format on alert notifications not matching user preferences. (Pro)</li>
<li>Resolved issue with invalid signal strengths displayed on some devices when connected to a WCDMA network.</li>
<li>Resolved issue with older log database imports failing. (Pro)</li>
<li>Resolved logcat warnings when inserting geocoded addresses. (Pro)</li>
<li>Resolved SSL errors when sending diagnostic reports on older devices.</li>
<li>Resolved Wi-Fi errors on some Android 11 devices.</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.65 (Released 1/15/2021):</strong></span></p>
<ul>
<li>Added automated in-app update functionality.</li>
<li>Added option to display LTE/NR cell ID in decimal format with sector. (Pro)</li>
<li>Adjusted LTE and 5G-NR signal thresholds.</li>
<li>Changed Trail Logger to skip duplicate crumbs with the same coordinates. (Pro)</li>
<li>Improved automated crash reporting information.</li>
<li>Resolved force closes when root modem functions were enabled.</li>
<li>Resolved issue with alternate PLMN ID method active on LTE regardless of user preference setting.</li>
<li>Resolved issue with out-of-memory errors.</li>
<li>Updated Clearwire provider labels to display as Sprint.</li>
<li>Updated selected Sprint / T-Mobile PLMN labels.</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.64 (Released 12/25/2020):</strong></span></p>
<ul>
<li>Added 5G-NR signal strength to widget. (Pro)</li>
<li>Added 5G-NR site notes and logging features. (Pro)</li>
<li>Added new &#8220;hits&#8221; column to log database; reflects number of times cell has been logged. (Pro)</li>
<li>Added option to choose LTE/NR sector display format with the site note on the main screen. (Pro)</li>
<li>Added option to enable Trail Logger feature; saves one &#8220;crumb&#8221; to the trail log per signal update. (Pro)</li>
<li>Added option to use alternate method to obtain PLMN ID; some networks (T-Mobile) report different information with alternate method. (Pro)</li>
<li>Added options to trigger Alerts based on specific 5G-NR bands or plain-text strings. (Pro)</li>
<li>Added shortcut to submit diagnostic report; long-press on &#8220;Connected to..&#8221; network text.</li>
<li>Clarified 5G band alert message on non-standalone connections. (Pro)</li>
<li>Clarified menu options that may increase battery usage. (Pro)</li>
<li>Code optimizations and enhancements.</li>
<li>Improved 5G-NR information in notification pulldown. (Pro)</li>
<li>Improved alert notification icons to show connection type and band if applicable. (Pro)</li>
<li>Improved and clarified some options under Preferences menu. (Pro)</li>
<li>Improved reliability of 5G Lost alert. (Pro)</li>
<li>Improved some system shortcut options on Android 10/11. (Pro)</li>
<li>Improved warnings about root modem function being enabled unnecessarily. (Pro)</li>
<li>Resolved force closes when attempting to delete the BSL cache. (Pro)</li>
<li>Resolved force closes when excessive number of internal listeners are registered.</li>
<li>Resolved force closes when necessary permissions are not granted on some Android 10+ devices.</li>
<li>Resolved force closes when provider name was missing.</li>
<li>Resolved force closes when root modem functions were enabled. (Pro)</li>
<li>Resolved issue with 5G alerts not triggering. (Pro)</li>
<li>Resolved issue with 5G-NR provider name occasionally incorrect or missing from alert notifications and log entries. (Pro)</li>
<li>Resolved issue with improper identification of some LTE band 66 and 71 neighbor cells. (Pro)</li>
<li>Resolved issue with improperly formatted CDMA site log exports. (Pro)</li>
<li>Resolved issue with invalid LTE CA bandwidth values being displayed. (Pro)</li>
<li>Resolved issue with some 5G-NR bands displaying improperly.</li>
<li>Resolved issue with stale 5G-NR frequency display.</li>
<li>Resolved issue with unnecessary logcat warnings on non-5G devices.</li>
<li>Updated target API to Android 10.</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.63 (Released 11/1/2020):</strong></span></p>
<ul>
<li>Added colored accent line for Claro users. (Pro)</li>
<li>Added secondary crash reporting service.</li>
<li>Extensive code optimizations and enhancements.</li>
<li>Improved Sprint LTE site note compatibility with new PLMN ID. (Pro)</li>
<li>Resolved force closes on some devices related to database initialization. (Pro)</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.621 (Released 9/10/2020):</strong></span></p>
<ul>
<li>Added 5G-NR alerts and 5G standalone status bar icons. (Pro)</li>
<li>Added new system shortcuts for Samsung users. (Pro)</li>
<li>Added option to display colored accent line on active connections. (Pro)</li>
<li>Added separate 5G-NR information display block.</li>
<li>Improved depth and reliability of 5G-NR information.</li>
<li>Overhauled text color options; users can now choose any colors for text, background, action bar title, and action bar background. (Pro)</li>
<li>Reorganized display settings screen. (Pro)</li>
<li>Resolved issue with excessive warning messages when using System Shortcuts on some devices. (Pro)</li>
<li>Resolved issue with outdated notification channel warning. (Pro)</li>
<li>Resolved issue with some Clearwire LTE cells incorrectly labeled B41.</li>
<li>Updated help screen.</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.61 (Released 4/20/2020):</strong></span></p>
<ul>
<li><span style="color: #000000;">Resolved force closes with Location Service on devices using non-Latin characters. (Pro)</span></li>
<li><span style="color: #000000;">Resolved internal exception with multi-thread permission requests.</span></li>
<li>Resolved issue with log import/export features not working on some Android 10 devices. (Pro)</li>
<li><span style="color: #000000;">Resolved issue with out-of-memory errors.</span></li>
<li>Resolved issue with stale LTE data on some Android 10 devices.</li>
<li>Rolled back target API to Android 9.</li>
<li><span style="color: #000000;">Updated external permissions library.</span></li>
<li>Updated external root functionality library. (Pro)</li>
</ul>
<p><span style="text-decoration: underline; color: #000000;"><strong>Version 4.59 (Released 4/1/2020):</strong></span></p>
<ul>
<li><span style="color: #000000;">Added limited 5G-NR info display [BETA].</span></li>
<li><span style="color: #000000;">Added option to resolve stale LTE data on pre-Android 10 devices.</span></li>
<li><del><span style="color: #000000;">Resolved issue with stale LTE data on some Android 10 devices.</span></del></li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.58 (Released 2/24/2020):</strong></span></p>
<ul>
<li>Changed exported logs to use preferred LTE Cell ID display format. (Pro)</li>
<li>Improved compatibility with accessibility services.</li>
<li>Resolved force close when attempting to send diagnostics on some devices.</li>
<li>Resolved internal exception when notification sounds are missing. (Pro)</li>
<li>Resolved issue with all WCDMA neighbor cells reporting -120 dBm on some devices. (Pro)</li>
<li>Resolved issue with missing information when connected to Wi-Fi Calling on some devices.</li>
<li>SignalCheck Lite brought up-to-date.</li>
<li>Updated external libraries for root functions. (Pro)</li>
<li>Updated permissions to require <em>ACCESS_FINE_LOCATION</em> for all functions.</li>
<li>Updated target API to Android 10.</li>
</ul>
<p><span style="text-decoration: underline;"><strong style="font-size: inherit;">Version 4.57 (Released 2/17/2020):</strong></span></p>
<ul>
<li>Added additional indicators for AT&amp;T LTE iDAS and small cells.</li>
<li>Added option to choose LTE cell ID display format: GCI, ECI, or hybrid. (Pro)<br /><em>*** Users who previously enabled LTE ECI should update their selection.</em></li>
<li>Added option to display WCDMA neighbor cell PSC as hex. (Pro)</li>
<li>Improved efficiency and stability of internal databases.</li>
<li>Minor adjustments to action bar menu icons. (Pro)</li>
<li>Moved Neighbor Cells preferences to separate menu. (Pro)</li>
<li>Removed outdated references to nTelos.</li>
<li>Resolved force closes related to missing resources on some devices.</li>
<li>Resolved force closes when accessing Purchase menu with background service disabled.</li>
<li>Resolved issue with invalid CDMA Ec/Io values displayed.</li>
<li>Resolved issue with LTE band alerts not triggering when band changes. (Pro)</li>
<li>Resolved issue with LTE band alerts triggering for invalid bands. (Pro)</li>
<li>Resolved issue with missing CDMA data on some Android 10+ devices.</li>
<li>Resolved issue with PSC failing to be logged for WCDMA connections. (Pro)</li>
<li>Resolved issue with some AT&amp;T LTE band 66 connections displaying as band 4.</li>
<li>Updated Shentel LTE indicators.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.56 (Released 1/7/2020):</strong></span></p>
<ul>
<li>Added system shortcut for app system settings. (Pro)</li>
<li>Extensive code optimizations and enhancements.</li>
<li>Internal code enhancements to Location Service. (Pro)</li>
<li>Removed persistent prompts/warnings that appeared when a user denied background location permission but had the background service disabled.</li>
<li>Resolved force closes on some devices using decimal separators other than &#8216;dot&#8217;.</li>
<li>Resolved force closes related to permission requests.</li>
<li>Resolved internal exception when installing/updating the app.</li>
<li>Resolved issue with incorrect signal strength notification icon when connected to LTE &amp; Wi-Fi Calling. (Pro)</li>
<li>Resolved issue with negative LTE SNR values missing the &#8220;-&#8221; character.</li>
<li>Resolved issue with persistent warnings appearing when a user denies background location permission and requests not to be prompted again.</li>
<li>Resolved issue with screen padding not working with GSM-based connections. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.551 (Released 12/1/2019):</strong></span></p>
<ul>
<li>Resolved issue with missing data on Android 10 devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.55 (Released 11/29/2019):</strong></span></p>
<ul>
<li>Added limited recognition of 802.11ax Wi-Fi connections.</li>
<li>Added option to add padding to the left and right borders of the main screen. (Pro)</li>
<li>Added prompt to warn users if background location permissions have been denied. (Pro)</li>
<li>Changed optional correction factor on LTE Timing Advance (TA) value to also apply to TD-LTE connections. (Pro)</li>
<li>Improved Android 10 compatibility.</li>
<li>Resolved force closes on Samsung Android 10 devices.</li>
<li>Resolved force closes related to exiting the app.</li>
<li>Resolved issue with duplicate notification channel entries. (Pro)</li>
<li>Resolved issue with missing WCDMA data on certain devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.54 (Released 7/12/2019):</strong></span></p>
<ul>
<li>Added in-app purchase functionality for voluntary contributions.</li>
<li>Changed imperial LTE TA distance units to display miles instead of feet.</li>
<li>Resolved force closes related to the Location Service on some Android 8+ devices (Pro).</li>
<li><del>Resolved internal exception when installing the app.</del></li>
<li>Resolved issue with invalid CDMA sites being displayed/logged.</li>
<li>Resolved various force closes related to starting and exiting the app.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.532 (Released 6/5/2019):</strong></span></p>
<ul>
<li>Added ability to look up network registrant by clicking on IP address. (Pro)</li>
<li>Added additional information to Logger Statistics screen. (Pro)</li>
<li>Added indicators for Sprint Airave 4 CDMA/LTE connections.</li>
<li>Added option to apply a correction factor to LTE timing advance (TA) value. (Pro)</li>
<li>Added option to display carrier aggregation info on Android 9.0+ devices [BETA]. (Pro)</li>
<li>Removed option to exclude logcat output from diagnostic reports. (Pro)</li>
<li>Resolved force closes when permissions were denied/revoked.</li>
<li><del>Resolved internal exception when installing version 4.52.</del></li>
<li>Resolved issue with CDMA site notes and logging not working when connected to Sprint Airave 4. (Pro)</li>
<li>Resolved issue with EARFCN values off by 1 for some LTE band 66 and 71 cells.</li>
<li>Resolved issue with missing LTE data on some Android 7+ devices.</li>
<li>Resolved issue with missing popup when permissions were denied.</li>
<li>Resolved issue with no signal alerts not triggering. (Pro)</li>
<li>Updated help screen.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.52 (Released 4/18/2019):</strong></span></p>
<ul>
<li>Added FirstNet PLMN ID.</li>
<li>Added indicator for Sprint LTE band 41 small cells that also may appear as Mini-Macro.</li>
<li>Added LTE timing advance (TA) value and estimated distance.</li>
<li>Added option to control display of horizontal signal meters on main screen. (Pro)</li>
<li>Added option to control logging of LTE sites if the TAC is missing/invalid. (Pro)</li>
<li>Added option to display LTE bandwidth on Android 9.0+ devices [BETA]. (Pro)</li>
<li>Added options to trigger Alerts based on specific LTE bands or plain-text strings. (Pro)</li>
<li>Adjusted animated action bar tower icon colors when idle. (Pro)</li>
<li>Changed device location settings warning to reappear on every app update.</li>
<li>Changed primary signal data source on Android 7+ devices.</li>
<li>Disabled battery-related options for Location Service and Site Logger on Android 8.0+ devices; intend add back in a future update. (Pro)</li>
<li>Improved deployment process; releases will now be smaller, more optimized downloads.</li>
<li>Resolved issue with Alerts preferences not working properly on Android 8.0+ devices. (Pro)</li>
<li>Resolved issue with app failing to exit immediately in certain scenarios.</li>
<li>Resolved issue with missing data on Android Q Beta devices.</li>
<li>Resolved issue with missing PLMN ID in certain scenarios.</li>
<li>Resolved issue with missing provider database on Android 9.0 devices.</li>
<li>Resolved issue with missing WCDMA data on newer devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.51 (Released 12/30/2018):</strong></span></p>
<ul>
<li>Added additional indicators for AT&amp;T LTE band 14 FirstNet cells.</li>
<li>Added icon to indicate when Wi-Fi calling is active. (Pro)</li>
<li>Added indicator for Sprint LTE band 41 small cell second carriers.</li>
<li>Added indicators for AT&amp;T LTE band 2 small cells.</li>
<li>Disabled support for Android 2.3 &#8211; Android 3.2.</li>
<li>Changed LTE band 14 to display as LTE 750.</li>
<li>Changed primary PLMN ID source on Android 7+ devices.</li>
<li>Implemented Android Oreo notification channels. (Pro)</li>
<li>Improved Sprint LTE site notes to appear across multiple PLMN IDs. (Pro)</li>
<li>Minor adjustments to animated action bar tower icon. (Pro)</li>
<li>Resolved force closes when Background Service is disabled.</li>
<li>Resolved issue with app auto-launching regardless of Launch on Device Boot preference setting. (Pro)</li>
<li>Resolved issue with cached diagnostic reports not sending.</li>
<li>Resolved issue with missing LTE band data when PLMN ID changes.</li>
<li>Resolved issue with Show Mobile IP Address failing. (Pro)</li>
<li>Resolved issue with some Sprint LTE band 41 cells showing improper MM and SC indicators.</li>
<li>Updated PLMN 310580 to Inland Cellular.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.49 (Released 10/26/2018):</strong></span></p>
<ul>
<li>Added indicators for AT&amp;T LTE band 14 FirstNet cells.</li>
<li>Added indicators for Clearwire LTE band 41 third carriers.</li>
<li>Added indicators for Rogers LTE band 2, 4, 7, and 17 cells.</li>
<li>Added option to disable adding/editing site notes from the main screen. (Pro)</li>
<li>Added option to use new patterns to identify Sprint LTE cells in Samsung markets reconfigured in 2018. (Pro)</li>
<li>Added system shortcut for voice band mode selection. (Pro)</li>
<li>Added workaround for improper identification of some LTE band 66 and 71 cells <a href="https://issuetracker.google.com/issues/37136986" target="_blank" rel="noopener noreferrer">due to a known Android bug</a>.</li>
<li>Changed action bar icon on main screen to be animated; new option to use previous static icon. (Pro)</li>
<li>Changed action bar title on main screen to match user-selected text color. (Pro)</li>
<li>Changed alerts to be off by default. (Pro)</li>
<li>Changed diagnostic routine to use SSL.</li>
<li>Final version for Android 2.3 &#8211; Android 3.2 devices.</li>
<li>General internal code enhancements.</li>
<li>Improved runtime permission handling.</li>
<li>Resolved issue with app closing when Preferences menu is selected or orientation is changed and Background Service is disabled. (Pro)</li>
<li>Resolved issue with invalid LTE neighbor cell displaying with PCI 0 and 0 dBm. (Pro)</li>
<li>Updated references to new domain (signalcheck.app).</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.48 (Released 2/24/2018):</strong></span></p>
<ul>
<li>Added additional indicators for Sprint LTE band 41 Magic Box cells (up to 0FC).</li>
<li>Internal development changes.</li>
<li>Resolved force closes on certain Android 7 devices with the 1X status bar icon enabled. (Pro)</li>
<li>Resolved force closes on some devices when Location Service is stopped before it finishes initializing. (Pro)</li>
<li>Resolved issue with CDMA BSL display failing on certain Android 8.0 devices. (Pro)</li>
<li>Resolved issue with missing Wi-Fi data on Android 8.1 when location permission was not requested.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.47 (Released 12/15/2017):</strong></span></p>
<ul>
<li>Added additional indicators for AT&amp;T LTE band 2, 4, 5, 12, 17, and 30 cells.</li>
<li>Added additional indicators for Sprint CDMA Airave cells.</li>
<li>Added additional indicators for Sprint LTE band 41 Magic Box cells (up to 0F3).</li>
<li>Added Data/EPST and Debug/Engineering shortcuts for rooted Pixel devices. (Pro)</li>
<li>Added indicators for T-Mobile LTE band 71 cells <em>(<a href="/signalcheck/known-issues#tmobile">excluding East Coast &amp; Western US</a>)</em>.</li>
<li>Added option to hide &#8220;Unknown&#8221; neighbor cells. (Pro)</li>
<li>Added support for newest LTE bands in 3GPP spec.</li>
<li>Changed AT&amp;T LTE band 17 indicators to display as &#8220;B12/B17&#8221; if EARFCN cannot be obtained.</li>
<li>Overhauled implementation of Android 6+ runtime permissions requirements.</li>
<li>Overhauled Wi-Fi channel and bandwidth routines.</li>
<li>Reorganized Display Settings screen. (Pro)</li>
<li>Resolved force closes on devices with multiple user accounts.</li>
<li>Resolved force closes when necessary permissions have not been granted on Android 6+.</li>
<li>Resolved force closes with Send Diagnostics function when storage permission is not granted.</li>
<li>Resolved issue with CDMA BSL display failing on Android 8.1. (Pro)</li>
<li>Resolved issue with missing signal information on GSM devices reporting 99% BER.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.46 (Released 9/20/2017):</strong></span></p>
<ul>
<li>Added additional indicators for Sprint LTE band 41 Airave/S1000 cells.</li>
<li>Added additional indicators for Sprint LTE band 41 Magic Box cells (up to 0EF).</li>
<li>Added indicators for T-Mobile LTE band 4 Cellspot and In-Store Pico cells.</li>
<li>Added support for LTE band 71.</li>
<li>Improved identification of mobile network type on IWLAN connections.</li>
<li>Resolved issue with invalid GSM neighbor cell PLMN/CID/LAC information displayed. (Pro)</li>
<li>Resolved issue with IWLAN signal strength missing from notification icon. (Pro)</li>
<li>Updated provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.45 (Released 9/1/2017):</strong></span></p>
<ul>
<li>Added &#8220;Maximum&#8221; notification icon priority. (Pro)</li>
<li>Added notification icons for Airave 1X connections. (Pro)</li>
<li>Added notification icons for IWLAN and TD-SCDMA networks. (Pro)</li>
<li>Added option to limit notifications when Samsung DeX mode is active. (Pro)</li>
<li>Added provider name to LTE neighbor cells if PLMN is reported and does not match active connection. (Pro)</li>
<li>Changed main screen to display &#8220;Mobile&#8221; instead of &#8220;CDMA&#8221; when there is no mobile connection.</li>
<li>Changed &#8220;Wi-Fi Calling&#8221; label to &#8220;IWLAN&#8221;.</li>
<li>Improved third-party (Tasker) intents; omitted Extras will no longer trigger changes. (Pro)</li>
<li>Resolved issue with CDMA BSL display failing on Android 8.0 due to <a href="https://issuetracker.google.com/issues/63130155">a known Android bug</a>. (Pro)</li>
<li>Resolved issue with LTE band 12 displaying 1 MHz too high.</li>
<li>Resolved issue with mobile IP address not displaying in certain situations. (Pro)</li>
<li>Resolved issue with Sprint Airave/800 indicators displaying improperly.</li>
<li>Resolved issue with status bar notification priority preference not working. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.44 (Released 7/21/2017):</strong></span></p>
<ul>
<li>Added donation link to About screen.</li>
<li>Added feature to add current location to a site note. (Pro)</li>
<li>Added indicators for some Sprint LTE band 25 oDAS cells.</li>
<li>Added notification icons for LTE bands outside of North America. (Pro)</li>
<li>Added option to display LTE ECI (decimal) instead of GCI (hex). (Pro)</li>
<li>Added option to display mobile connection IP address. (Pro)</li>
<li>Added option to display Reset Mobile Connection button on the action bar. (Pro)</li>
<li>Added option to hide CDMA 1X display when connected to LTE. (Pro)</li>
<li>Changed provider to indicate if CDMA 1X connection is a Sprint Airave or 800 SMR.</li>
<li>Improved diagnostic reports; failed reports will now be saved and can be manually resubmitted from the Send Diagnostics screen.</li>
<li>Resolved force closes at startup in certain situations.</li>
<li>Resolved force closes when requested permissions are not immediately granted on Android 6+.</li>
<li>Resolved issue with connection titles overlapping signal meters.</li>
<li>Resolved issue with geocoder features not working. (Pro)</li>
<li>Resolved issue with LTE 1900 notification icons missing. (Pro)</li>
<li>Resolved issue with LTE band conflicts between native EARFCN and GCI-calculated band.</li>
<li>Resolved issue with LTE frequency title not updating properly in certain situations.</li>
<li>Resolved issue with misidentified Sprint LTE band 25 10&#215;10 sites in certain areas.</li>
<li>Resolved issue with unreliable CDMA 1X BSL and Site Note displayed in the notification pulldown when a call is in progress. (Pro)</li>
</ul>
<p><strong><span style="text-decoration: underline;">Version 4.43 (Released 6/29/2017):</span></strong></p>
<ul>
<li>Added automatic site note correlation between Verizon B2/B4/B13 LTE sites. (Pro)</li>
<li>Added Change Log display on first app launch.</li>
<li>Added indicators for additional AT&amp;T, T-Mobile, and Verizon LTE bands and cells.</li>
<li>Added indicators for AT&amp;T LTE band 2 small cells (SC) &amp; oDAS.</li>
<li>Added indicators for AT&amp;T LTE band 17 single-sector (SS) macro cells.</li>
<li>Added indicators for Sprint LTE band 25 10&#215;10 sites.</li>
<li>Added indicators for Sprint LTE band 41 Airave 3.0 &amp; Magic Box (MB) cells.</li>
<li>Added indicators for Sprint LTE band 41 carriers 3-6.</li>
<li>Added indicators for Sprint LTE band 41 Mini-Macro (MM) &amp; small cells (SC).</li>
<li>Added indicators for Sprint LTE band 41 MM high capacity (HC) sites.</li>
<li>Added LTE band display (and option to include EARFCN) to neighbor cells. (Pro)</li>
<li>Added visual notification when any alerts are triggered on Android 6+. (Pro)</li>
<li>Changed AT&amp;T LTE DAS indicators to &#8220;iDAS&#8221; (indoor) or &#8220;oDAS&#8221; (outdoor).</li>
<li>Changed PLMN 311940 to Clearwire.</li>
<li>Implemented Android 6+ runtime permissions requirements.</li>
<li>Implemented basic privacy policy.</li>
<li>Implemented native LTE EARFCN display and band identification on compatible Android 7+ devices.</li>
<li>Improved identification of Sprint LTE band 25 second carriers in certain regions.</li>
<li>Improved identification of Sprint LTE connections for prepaid users.</li>
<li><a href="/signalcheck/known-issues#tmobile">Removed calculated indicators for T-Mobile LTE bands in some markets (East Coast, Western US) due to deployment inconsistencies.</a></li>
<li>Resolved force closes with Location Service on devices using non-Latin characters. (Pro)</li>
<li>Resolved issue with device freezing while Site Logs were exported. (Pro)</li>
<li>Resolved issue with GSM Site Log export failing. (Pro)</li>
<li>Resolved issue with incorrect LTE site notes displaying if database had been manually edited. (Pro)</li>
<li>Resolved issue with Location Service restarting when power is connected. (Pro)</li>
<li>Resolved issue with LTE PCI 0 not displaying.</li>
<li>Resolved issue with provider display showing PLMN instead of name in certain situations.</li>
<li>Resolved issue with some LTE band 30 notification icons not displaying. (Pro)</li>
<li>Significant behind-the-scenes code optimizations.</li>
<li>Updated help screen.</li>
<li>Updated launcher icon to material and round designs.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.31 (Released 4/10/2016):</strong></span></p>
<ul>
<li>Added additional indicators for nTelos LTE band 41 and T-Mobile LTE band 4.</li>
<li>Added broadcast intents to toggle Background Service, Location Service, and Site Logger through third-party apps (i.e. Tasker). (Pro)</li>
<li>Added indicators for AT&amp;T LTE band 4 second carriers and band 30.</li>
<li>Added indicators for Sprint LTE band 41 third carriers.</li>
<li>Added indicators for Verizon LTE band 4 second carriers.</li>
<li>Added indicators for nTelos LTE band 41 second carriers.</li>
<li>Added initial support for Wi-Fi Calling network type.</li>
<li>Added option to allow users to set text color on main screen. (Pro)</li>
<li>Added option to display LTE EARFCN and frequency data from the onboard modem if rooted. (Pro)</li>
<li>Added options to automatically enable/disable Location Service upon charging, unplugging, or low battery. (Pro)</li>
<li>Added options to automatically enable/disable Site Logger upon charging, unplugging, or low battery. (Pro)</li>
<li>Added site note pairing for nTelos LTE bands 25 and 41. (Pro)</li>
<li>Implemented Material design theme.</li>
<li>Added support for all valid EARFCN values.</li>
<li>Resolved force closes with Location Service caused by outdated/missing Google Play Services. (Pro)</li>
<li>Resolved issue with incorrect PLMN displaying on some nTelos LTE connections.</li>
<li>Resolved issue with missing LTE identity data and neighbor cells on some newer devices. (Pro)</li>
<li>Resolved issue with missing LTE identity data when CDMA 1X connection is also present.</li>
<li>Resolved issue with notification icon occasionally appearing as blank square on Android 5+. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.29 (Released 11/7/2015):</strong></span></p>
<ul>
<li>Added indicators for Boost Mobile and Virgin Mobile LTE bands 25, 26, and 41.</li>
<li>Added indicators for Boost Mobile and Virgin Mobile LTE second carriers.</li>
<li>Added indicators for nTelos LTE band 25 second carriers.</li>
<li>Added indicators for nTelos LTE bands 25, 26, and 41.</li>
<li>Added indicators for Sprint LTE band 41 second carriers.</li>
<li>Added option to add color to notification pulldown based on connection type or major US mobile provider on Android 5+. (Pro)</li>
<li>Added option to control notification icon visibility on Android 5+ lockscreens. (Pro)</li>
<li>Improved Android 6.0 (Marshmallow) compatibility.</li>
<li>Improved crash reporting and diagnostic routines.</li>
<li>Improved information display when initially connecting to some CDMA 1X networks.</li>
<li>Resolved force closes at startup on many Huawei devices.</li>
<li>Resolved force closes on Android 6+ devices with Alerts or icons enabled. (Pro)</li>
<li>Resolved force closes when Location Service is enabled on some devices. (Pro)</li>
<li>Resolved issue with BSL displaying in notification pulldown when there was no connection or user preferred to hide it. (Pro)</li>
<li>Resolved issue with false CDMA 1X and GSM connections displayed in certain situations.</li>
<li>Resolved issue with occasional false alerts/indicators when LTE PLMN changes. (Pro)</li>
<li>Updated RootTools library. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.28 (Released 5/13/2015):</strong></span></p>
<ul>
<li>Added additional indicators for AT&amp;T LTE bands 2, 4, and 17, including DAS and small cells.</li>
<li>Added icon to indicate when telephone calls are unavailable. (Pro)</li>
<li>Added indicators for Sprint LTE band 25 and most second carriers (labeled with ²).</li>
<li>Added indicators for T-Mobile LTE band 12.</li>
<li>Added indicators for Verizon LTE bands 2, 4, and 13.</li>
<li>Added Logger statistics window. (Pro)</li>
<li>Added option for one-time clean up of duplicate GCI Site Logger entries. (Pro)</li>
<li>Added option for one-time clean up of null GCI Site Logger entries. (Pro)</li>
<li>Added option to hide CDMA 1X BSL when a Site Note exists. (Pro)</li>
<li>Added option to control logging of LTE if the GCI is missing/invalid. (Pro)</li>
<li>Changed exported logs to include leading zero on plain-text dates. (Pro)</li>
<li>Improved internal diagnostic routines.</li>
<li>Improved neighbor cell display. (Pro)</li>
<li>Moved the CDMA 1X Provider display line above the Site Note.</li>
<li>Resolved force closes at startup related to the internal provider database.</li>
<li>Resolved issue with Alerts on all versions of Android except for the L Preview. (Pro)</li>
<li>Resolved issue with LTE frequency display sticking when connection was lost.</li>
<li>Resolved issue with missing/invalid LTE identity data.</li>
<li>Resolved issue with Site Logger ignoring CDMA 1X sites with a missing/invalid BSL. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.27 (Released 12/22/2014):</strong></span></p>
<ul style="list-style-type: disc;">
<li>Added ability to backup and import Logger databases. (Pro)</li>
<li>Added additional indicators for AT&amp;T LTE bands 4, 17, 4 DAS, and 17 DAS.</li>
<li>Added display of primary scrambling code (PSC) in hex format.</li>
<li>Added LTE band display to widget. (Pro)</li>
<li>Added many new higher-resolution status bar icons. (Pro)</li>
<li>Added new indicators for T-Mobile LTE bands 2 and 4.</li>
<li>Added option to choose the background color for the main screen. (Pro)</li>
<li>Added option to display location information in metric units of measurement. (Pro)</li>
<li>Added option to display LTE neighbor cell site notes based on location. (Pro)</li>
<li>Added option to display recognized LTE bands or frequency classes on status bar icons. (Pro)</li>
<li>Added option to ignore PLMN for neighbor site notes. (Pro)</li>
<li>Added option to specify maximum range to display location-based LTE neighbor cell site notes. (Pro)</li>
<li>Changed display to show &#8220;Clearwire B41&#8221; if connected to a former Clearwire LTE band 41 site.</li>
<li>Changed display to show Sprint prepaid MVNO connections (Boost or Virgin Mobile).</li>
<li>Changed Location Service to use new Google routines. (Pro)</li>
<li>Changed main screen to default to a true black background, saves power on AMOLED devices.</li>
<li>Improved 1X and LTE provider identification; unknown IDs will now display network-provided name.</li>
<li>Improved method to obtain LTE GCI information, courtesy of the guys over at <a href="https://play.google.com/store/apps/details?id=net.simplyadvanced.ltediscovery" target="_blank" rel="noopener noreferrer">Simply Advanced</a>!</li>
<li>Improved reliability of PLMN ID identification for Sprint users.</li>
<li>LTE Site Logger will run an automatic one-time background cleanup to remove various null entries. (Pro)</li>
<li>Removed option for secondary GSM icon; would likely never be shown on any device. (Pro)</li>
<li>Resolved force closes on Android 4.2+ devices caused by invalid neighbor cell data. (Pro)</li>
<li>Resolved issue with dictionary suggestions not appearing when editing site notes. (Pro)</li>
<li>Resolved issue with Free Mobile WCDMA display string.</li>
<li>Resolved issue with LTE band identification for Sprint Prepaid users on PLMN 312530.</li>
<li>Resolved issue with missing LTE connection information when reported RSRQ is invalid.</li>
<li>Resolved issue with Sprint LTE band 41 frequencies not displaying on compatible HTC devices.</li>
<li>Resolved issue with stale LTE GCI display.</li>
<li>Updated provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.261 (Released 10/26/2014):</strong></span></p>
<ul>
<li>Added display of frequency class for recognized LTE bands (i.e. &#8220;LTE 800&#8221;) on the main screen.</li>
<li>Added display of primary scrambling code (PSC) for GSM sites.</li>
<li>Added indicators for Free Mobile UMTS bands 1 and 8.</li>
<li>Added option to display LTE and GSM neighbor cells. (Pro)</li>
<li>Added options to hide disconnected or unavailable connection types. (Pro)</li>
<li>Added Site Log fields for strongest signals and the locations they were received. (Pro)</li>
<li>Changed user site note prompts to capitalize the first letter of each word by default. (Pro)</li>
<li>Improved Sprint LTE band 41 identification, including new 8T8R sites.</li>
<li>Resolved issue with disconnected Wi-Fi connections showing -127 dBm signal on Android 5.0.</li>
<li>Resolved issue with missing last_time values in the Site Log. (Pro)</li>
<li>Resolved issue with null GCI and TAC values appearing in the LTE site log. (Pro)</li>
<li>Resolved issue with PLMN 311490 always showing for Sprint LTE band 41.</li>
<li>Resolved issue with Sprint LTE PLMN failing to update properly.</li>
<li>Resolved issue with stale 1X information displayed after connection is lost. (Pro)</li>
<li>Resolved issue with Wi-Fi connections displaying speeds of 0 Mbps on some devices.</li>
<li>Sprint LTE band 41 sites that were owned by Clearwire are now marked with an asterisk on the main screen.</li>
<li>Sprint LTE band 41 sites that were not Clearwire sites will share user notes with co-located B25 sites. (Pro)</li>
<li>Updated provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.251 (Released 8/13/2014):</strong></span></p>
<ul>
<li>Added indicators for AT&amp;T LTE bands 2, 4, 5, 17, and 17 DAS.</li>
<li>Added site notes to notification pulldown. (Pro)</li>
<li>Improved Android L compatibility; SignalCheck alerts are not yet available on this OS. (Pro)</li>
<li>Improved Sprint LTE band 26 display reliability.</li>
<li>Resolved force closes when GSM PLMN is invalid or missing.</li>
<li>Resolved force closes when Location Service is enabled or automatically restarted on some devices. (Pro)</li>
<li>Resolved force closes when Wi-Fi MAC address is invalid or missing.</li>
<li>Resolved issue where invalid LTE site notes could be entered before the LTE PLMN was identified. (Pro)</li>
<li>Resolved issue where location information would stop updating. (Pro)</li>
<li>Resolved issue with stale 1X site, provider, and BSL information displayed when connecting. (Pro)</li>
<li>Updated GSM provider database.</li>
<li>Disabled support for Android 2.2.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.243 (Released 4/22/2014):</strong></span></p>
<ul>
<li>Improved reliability of LTE site note database entries. (Pro)</li>
<li>Resolved force closes when certain Site Hint options are enabled. (Pro)</li>
<li>Resolved force closes when enabling Location Service on some devices. (Pro)</li>
<li>Resolved force closes when Location Service is enabled in locales that use a comma as a decimal separator. (Pro)</li>
<li>Resolved issue with existing GSM site notes failing to be pre-filled in popup window. (Pro)</li>
<li>Resolved issue with LTE site note display not updating on some HTC devices. (Pro)</li>
<li>Resolved issue with no information showing when in EV-DO only mode.</li>
<li>Resolved issue with Sprint LTE band 41 display missing.</li>
<li>Resolved issue with Sprint users in Shentel and former US Cellular service areas seeing false indications of LTE band 26.</li>
<li>Final version for Android 2.2 devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.24 (Released 4/14/2014):</strong></span></p>
<ul>
<li>Added ability for the widget to launch system shortcuts directly. (Pro)</li>
<li>Added ability for users to add notes to LTE (if GCI is identified), 1X, and GSM sites. (Pro)</li>
<li>Added BID and street address back to BSL markers in Google Maps. (Pro)</li>
<li>Added BSL display to notification icon pulldown. (Pro)</li>
<li>Added display of Wi-Fi channel, frequency, bandwidth, protocol suffix, and IP address.</li>
<li>Added field to display when telephone calls are in progress, limited or unavailable.</li>
<li>Added icons to illuminate when location service or site logger are enabled. (Pro)</li>
<li>Added location features and options. (Pro)</li>
<li>Added logging features and options for 1X, GSM, and LTE sites. (Pro)</li>
<li>Added new &#8220;Site Hint&#8221; options for major CDMA service providers. (Pro)</li>
<li>Added option for the Reset feature to use the <a href="http://android.dm.id.lv/Jelly_Bean_4.x_Airplane_Mode_Helper" target="_blank" rel="noopener noreferrer">Jelly Bean Airplane Mode Helper</a> Xposed module if a user prefers, instead of the method built into the app. (Pro)</li>
<li>Added option to disable background service when app is not in the foreground. (Pro)</li>
<li>Added option to disable expanded notification pulldown. (Pro)</li>
<li>Added options to display timestamp and/or device location coordinates. (Pro)</li>
<li>Added system shortcut to update PRL on Nexus 5 devices. (Pro)</li>
<li>Changed label of &#8220;1xRTT 800&#8221; to &#8220;1X 800&#8221;.</li>
<li>Changed label of Reset feature to Reset Mobile Connection. (Pro)</li>
<li>Improved display of LTE channel/frequency information available on some HTC devices.</li>
<li>Improved recognition of Boost and Virgin Mobile LTE connections.</li>
<li>Improved recognition of Sprint &#8220;Spark&#8221; LTE connections on bands 26 (&#8220;Sprint B26&#8221;) and 41 (&#8220;Sprint B41&#8221;).</li>
<li>Improved speed and reliability of Reset feature for Android 4.2+ devices. (Pro)</li>
<li>Reset feature will now take a device out of Airplane Mode. (Pro)</li>
<li>Resolved force closes on GSM devices when the PLMN was invalid.</li>
<li>Resolved force closes on some devices when connecting to LTE.</li>
<li>Resolved force closes when using the Reset feature. (Pro)</li>
<li>Resolved freezing/crashing issues on some devices when connection is lost/weak.</li>
<li>Resolved issue with 1X provider name showing as &#8220;SID: xxxx&#8221;.</li>
<li>Resolved issue with alerts failing to trigger. (Pro)</li>
<li>Resolved issue with BSL continuing to display after 1X connection is lost. (Pro)</li>
<li>Resolved issue with duplicate or unneeded 1X status bar icon on the screen on KitKat devices. (Pro)</li>
<li>Resolved issue with incorrect LTE PLMN display on some Sprint devices.</li>
<li>Resolved issue with invalid LTE TAC values appearing.</li>
<li>Resolved issue with no information showing when in EV-DO only mode.</li>
<li>Some system shortcuts will now be hidden on unsupported devices. (Pro)</li>
<li>Updated GSM provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.22 (Released 1/4/2014):</strong></span></p>
<ul>
<li>Added release date to About screen.</li>
<li>Added Samsung &#8220;Hidden Menu&#8221; back to System Shortcuts. (Pro)</li>
<li>Added workaround for Android 4.4+ bug which stops icon and widget updates; 4.4 devices now require the main status bar icon to be enabled while the app is running until another solution is found. (Pro)</li>
<li>Changed 1X and eHRPD/EV-DO sections to indicate &#8220;Disabled&#8221; when in LTE-only mode.</li>
<li>Resolved force closes when connecting to LTE in certain situations.</li>
<li>Resolved issue with no connection showing when in LTE-only mode.</li>
<li>Updated GSM provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.21 (Released 12/25/2013):</strong></span></p>
<ul>
<li>Added display of last known LTE cell information when Show Hidden Data is enabled and LTE connection is lost. (Pro)</li>
<li>Added LTE cell information and mobile data connection status to the expandable notification on Android 4.1+ devices. (Pro)</li>
<li>Added option to include logcat output from the app when sending a diagnostic report.</li>
<li>Added support for more devices to system shortcuts. (Pro)</li>
<li>Changed mobile location services warning prompt to clarify that location services may only be needed if the app does not perform as expected.</li>
<li>Changed some Sprint LTE connections to appear as &#8220;Sprint*&#8221; as a temporary indicator of likely Band 41 &#8220;Spark&#8221; connections. Evaluation and testing of this feature is ongoing and likely to change in the future.</li>
<li>Overhauled provider database functions, drastically reducing the number of queries needed; this results in less CPU, memory, and battery usage by the app.</li>
<li>Resolved issue with CDMA 1X provider names failing to display.</li>
<li>Resolved issue with display layout on non-CDMA devices when connected to LTE.</li>
<li>Resolved issue with errors when changing alert tone selections. (Pro)</li>
<li>Resolved issue with incorrect LTE PLMN on some newer devices.</li>
<li>Resolved issue with LTE CQI display.</li>
<li>Updated a small number of Verizon entries in the CDMA provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.19 (Released 12/10/2013):</strong></span></p>
<ul>
<li>Added Android 4.0-style action bar for devices running older OS versions.</li>
<li>Added display of mobile data connection status and mobile data traffic activity to action bar.</li>
<li>Added feature providing users with the ability to send a diagnostic report for technical support.</li>
<li>Changed &#8220;Carrier&#8221; label to &#8220;Provider&#8221; for clarity and standardization.</li>
<li>Changed display of &#8220;UMTS&#8221; to &#8220;W-CDMA&#8221; for clarity and standardization.</li>
<li>Changed secondary status bar icon behavior; if only an LTE connection is active, secondary 1X or GSM icon will be hidden, regardless of preference setting. (Pro)</li>
<li>Changed system shortcut menu options and expanded support for HTC, LG, and Samsung devices; menu options are no longer manufacturer-specific. (Pro)</li>
<li>Improved reliability of Reset Data Connection feature. (Pro)</li>
<li>Overhauled main GSM screen; section(s) will now display the type of connection. Inactive connections will now be hidden.</li>
<li>Removed routine to disable CDMA-only preferences on GSM devices. All options are now visible for all devices; CDMA-only features will have no effect on GSM devices, and GSM features will have no effect on CDMA devices. (Pro)</li>
<li>Removed widget action options that are still in testing. (Pro)</li>
<li>Resolved issue with false GSM connections appearing with static data.</li>
<li>Resolved issue with missing/invalid EV-DO provider name in the notification pulldown. (Pro)</li>
<li>Resolved issue with missing provider name for some Samsung LTE users.</li>
<li>Updated a small number of Cricket entries in the CDMA provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.18 (Released 11/14/2013):</strong></span></p>
<ul>
<li>Added display of LTE CQI (channel quality indicator), if available.</li>
<li>Added display of LTE TAC (tracking area code), if available.</li>
<li>Added prompt to warn users when mobile network location services are disabled.</li>
<li>Improved accuracy of PLMN data for GSM and LTE connections.</li>
<li>Improved database functions, reducing SQLite errors and overhead.</li>
<li>Resolved issue with provider name missing from main notification pulldown when on 1X and roaming. (Pro)</li>
<li>Resolved issue with invalid LTE SNR display on some devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.171 (Released 11/6/2013):</strong></span></p>
<ul>
<li>Removed Sprint LTE &#8220;Band 41&#8221; labels due to inaccuracies. Feature will be re-added in a future release.</li>
<li>Resolved issue with BSL continuing to display after connection is lost. (Pro)</li>
<li>Resolved issue with missing LTE GCI and frequency information on HTC devices running Sense 5.5.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.17 (Released 10/26/2013):<br /></strong></span></p>
<ul>
<li>Added dBm-only option for CDMA 1X status bar icon. (Pro)</li>
<li>Added option to hide main status bar icon when 1X status bar icon is enabled and active connection is 1X. (Pro)</li>
<li>Added option to display &#8220;site hint&#8221; which may assist some users in determining the ID of the connected 1X site. (Pro)</li>
<li>Added option to set priority of status bar icons/notifications. (Pro)</li>
<li>Added optional alert for when LTE connection is lost. (Pro)</li>
<li>Added optional alert for when Sprint 1X 800 MHz connection is lost. (Pro)</li>
<li>Added optional secondary GSM status bar icon to display GSM signal strength when connected to LTE. (Pro)</li>
<li>Added Sprint LTE &#8220;Band 41&#8221; labels on a trial basis.</li>
<li>Changed notification pulldown to display data connection provider name instead of 1X provider name, if available. (Pro)</li>
<li>Changed Preferences menu; options now organized into groups on separate pages. (Pro)</li>
<li>Corrected GSM CID field to display integer instead of hex value.</li>
<li>Resolved issue with dBm-only status bar icons disappearing when there is no signal. (Pro)</li>
<li>Resolved issue with invalid LTE SNR information; LTE SNR will now be hidden if invalid.</li>
<li>Resolved issue with invalid/missing signal information on some newer devices.</li>
<li>Resolved issue with &#8220;Unknown&#8221; provider display while showing LTE PLMN 31000.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.14 (Released 9/6/2013):</strong></span></p>
<ul>
<li>Resolved issues with invalid/missing EV-DO and LTE information on some devices that was introduced in Version 4.13.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.13 (Released 9/5/2013):</strong></span></p>
<ul>
<li>Added hex value of BID on main display.</li>
<li>Corrected LTE sector ID fields to display as &#8220;GCI&#8221; (Global Cell Identity) instead of &#8220;Serving Cell&#8221; or &#8220;CID&#8221;.</li>
<li>Resolved force closes on GSM devices when the PLMN was invalid.</li>
<li>Resolved issue with incorrect BSL address cache entries. (Pro)</li>
<li>Updated numerous entries in the CDMA and EV-DO provider databases.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.09 (Released 8/18/2013):</strong></span></p>
<ul>
<li><span style="color: #0000ee;"><span style="color: #333333;">Added caching of BSL addresses; geocoding server will only be queried if the BSL is &#8220;new&#8221; to that device.  BSL addresses that are &#8220;new&#8221; will be cached and displayed in bold the first time. (Pro)</span></span></li>
<li><span style="color: #0000ee;"><span style="color: #333333;">Added ability for rooted Android 4.2+ devices to utilize the Reset Data Connection feature. (Pro)</span> </span></li>
<li>Added option to show &#8220;hidden&#8221; EVDO/eHRPD and LTE signals when not connected to EVDO/eHRPD or LTE. (Pro)</li>
<li>Changed providername display; each connection type will display the name of the connected mobile provider, if available.</li>
<li>Changed signal bars icon to display &#8220;LTE&#8221; instead of &#8220;4G&#8221;. (Pro)</li>
<li>Corrected GSM area code field to display as &#8220;LAC&#8221; instead of &#8220;AC&#8221;.</li>
<li>Removed unused libraries, reducing APK file size. (Pro)</li>
<li>Resolved force closes with BSL in locales that use a comma as a decimal separator. (Pro)</li>
<li>Resolved issue with CDMA provider database location on multi-user devices.</li>
<li>Resolved issue with Google Maps not showing BSL marker on first launch. (Pro)</li>
<li>Resolved issue with invalid LTE serving cell and frequency values displaying.</li>
<li>Resolved issue with stale EVDO/eHRPD or LTE data displayed after connection is lost.</li>
<li>Simplified BSL display when address is not cached and geocoding server is unavailable. (Pro)</li>
<li>Updated hundreds of entries in the provider database.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.06 (Released 7/27/2013):</strong></span></p>
<ul>
<li>Added LTE connection frequencies on HTC devices.</li>
<li>Added menu shortcut to hidden system menu on Samsung devices. (Pro)</li>
<li>Added option for users to set the Reset Data Connection delay time. (Pro)</li>
<li>Improved BSL feature; map link is active even if the address cannot be displayed. (Pro)</li>
<li>Improved display of CDMA mobile provider names; will now show provider names at all times, including while roaming or otherwise connected to another mobile network.</li>
<li>Improved Reset Data Connection feature; increased delay and only the cellular radios will now be reset. (Pro)</li>
<li>Resolved issue with Google Maps 7+ displaying an error when mapping the BSL. (Pro)</li>
<li>Resolved issue with stale LTE data displayed on the HTC One after LTE connection is lost.</li>
<li>Resolved issue with widget always displaying GSM connection type as &#8220;N/A&#8221;. (Pro)</li>
<li>Updated EV-DO labels to display eHRPD if connected to eHRPD or LTE.</li>
<li>Updated help screen to reference the <a title="SignalCheck Help / FAQ" href="/signalcheck/help/">online FAQ</a> page.</li>
<li>Updated LTE CID field to display in hex format.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 4.03 (Released 6/20/2013):</strong></span></p>
<ul>
<li>Added options to allow users to select any notification tone on their device for alerts. (Pro)</li>
<li>Added status bar icons for Sprint 1xRTT 800MHz SMR service. (Pro)</li>
<li>Added support for LTE on Android 2.x devices.</li>
<li>Resolved issue with invalid SID/NID/BID values displayed in the 1X notification icon status while on a telephone call. (Pro)</li>
<li>Improved handling of Sprint 1xRTT 800MHz SMR status while on a telephone call.</li>
<li>Disabled support for Android 2.1.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.17 (Released 6/29/2013)</strong></span></p>
<ul>
<li>Resolved issues introduced in Versions 3.14-3.15 on GSM devices. (Lite)</li>
<li>Final version for Android 2.1 devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.16 (6/28/2013)</strong></span></p>
<ul>
<li>Released as Lite version only.</li>
<li>Temporarily removed features added in Versions 3.14-3.15 due to issues on GSM devices. (Lite)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.15 (6/14/2013)</strong></span></p>
<ul>
<li>Resolved force closes when using the 1X notification icon. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.14 (6/14/2013)</strong></span></p>
<ul>
<li>Resolved issue with Sprint 1xRTT 800MHz SMR alerts not working. (Pro)</li>
<li>Resolved issue with Reset Data Connection button displaying at the top of the screen on GSM devices. (Pro)</li>
<li>Resolved issue with upgrade banner display blocking info on small screens. (Lite)</li>
<li>Resolved issue with SID/NID/BID/BSL fields not updating while on a telephone call; these fields are not updated by the system during an active call.  Fields will now be hidden during calls to prevent display of invalid data.</li>
<li>Adjusted alerts to reduce occurrences of sounds &#8220;stuttering&#8221; or quickly playing several times in a row. (Pro)</li>
<li><span style="line-height: 13px;">Adjusted layout to prevent scrollbar on 4&#8243; screens in most circumstances.</span></li>
<li>Added error display and help screen to notify user when BSL geocoding is failing. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.09 (5/15/2013):</strong></span></p>
<ul>
<li><span style="line-height: 13px;">Resolved issue with &#8220;null&#8221; appearing after the LTE SNR reading on some devices.</span></li>
<li>Resolved issue with SignalCheck not launching automatically at boot in certain situations. (Pro)</li>
<li>Resolved issue with widget appearing as 2&#215;2 instead of 1&#215;1 on some devices. (Pro)</li>
<li>Added support for Samsung&#8217;s Multi Window (aka multi-view) feature.</li>
<li>Added option to allow SignalCheck to display in portrait or landscape mode according to how the user rotates the device. (Pro)</li>
<li>Added address text to BSL marker in Google Maps. (Pro)</li>
<li>Special thanks to <a title="S4GRU" href="http://S4GRU.com" target="_blank" rel="noopener noreferrer">S4GRU</a> for their tremendous support of SignalCheck from the beginning!</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.06 (4/13/2013):</strong></span></p>
<ul>
<li>Resolved some issues with false LTE readings on CM10.1 ROMs.</li>
<li>Resolved issues with crashes caused by invalid latitude/longitude values. (Pro)</li>
<li>Added configurable SignalCheck widget. (Pro)</li>
<li>Added options for Sprint 1xRTT 800MHz SMR connection alerts. (Pro)</li>
<li>Added option to display EV-DO sector ID (only for HTC devices at this time). (Pro)</li>
<li>Clicking on 1X BSL address now launches default mapping application with the base station marked. (Pro)</li>
<li>Alerts no longer require icons to be active. (Pro)</li>
<li>1X icon no longer requires main icon to be active. (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.03 (3/20/2013):</strong></span></p>
<ul>
<li>Most HTC devices running a stock ROM will now show the LTE Cell ID, regardless of Android version; may also work on HTC devices running custom ROMs.  <em>Huge thanks to lordsutch from <a title="S4GRU" href="http://S4GRU.com" target="_blank" rel="noopener noreferrer">S4GRU</a> for coming up with the code to handle this!</em></li>
<li>Added option to display street address of CDMA 1X base station location (i.e. location of tower or sector; data varies depending on cellular provider). (Pro)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 3.02 (2/27/2013):</strong></span></p>
<ul>
<li>Introduced LTE Cell ID display on *some* Android 4.2 devices. If device is capable, information will be displayed under LTE on main screen.</li>
<li>Introduced user preference to select LTE alert sound. Will be expanded in future releases. (Pro)</li>
<li>Introduced option to display Reset Data Connection button on main screen. (Pro)</li>
<li>Resolved issue with icon display in pulldown notification menu. (Pro)</li>
<li>Resolved issue with status bar icon disappearing in certain situations. (Pro)</li>
<li>Resolved issue with default user preferences not initiating properly. (Pro)</li>
<li>New distinct vibration pattern for LTE alerts. (Pro)</li>
<li>Minor code optimizations and enhancements.</li>
</ul>
<p><strong><span style="text-decoration: underline;">Version 3.01 (2/18/2013):</span></strong></p>
<ul>
<li>Introduced brand new customizable main status bar icons. (Pro)</li>
<li>Introduced a customizable secondary status bar icon for always-on 1X display. (Pro)</li>
<li>Redesigned Preferences menu. (Pro)</li>
<li>LTE RSSI readings were removed. All LTE functions now use RSRP.</li>
<li>Adjusted graphical bar levels for LTE and Wi-Fi.</li>
<li>Improved detection of &#8220;no signal&#8221; situations.</li>
<li>Separated vibrate and audio alert preferences for LTE alerts. (Pro)</li>
<li>Expanded help screen.</li>
<li>Improved resolution of SignalCheck icon.</li>
<li>Code optimizations and enhancements.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.13 (1/24/2013):</strong></span></p>
<ul>
<li>Added option to automatically run when device boots up. (Pro)</li>
<li>Added option to keep screen on while SignalCheck is in the foreground. (Pro)</li>
<li>Resolved force closes some users were experiencing when connected to LTE.</li>
<li>Resolved issue with some non-GSM devices showing GSM information.</li>
<li>Corrected math error with 1xRTT and EV-DO readings.</li>
<li>Redesigned the menus.</li>
<li>Improved quality of data provided by BugSense automated crash reporting.</li>
<li>Code enhancements and optimizations.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.09 (1/19/2013):</strong></span></p>
<ul>
<li>Improved compatibility checks for Advanced menu options. (Pro)</li>
<li>Removed LTE cell information for Android 4.2 users due to crashes. Feature is still in development and will be added in the near future.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.08 (1/19/2013):</strong></span></p>
<ul>
<li>Resolved several issues on GSM devices.</li>
<li>Fixed permissions problems for Jelly Bean users.</li>
<li>Corrected math error with LTE readings.</li>
<li>Added LTE cell information for Android 4.2 users. (Beta)</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.07 (1/14/2013):</strong></span></p>
<ul>
<li>Resolved force closes on GSM devices when receiving no signal.</li>
<li>Fixed incorrect notification icon displaying on GSM devices on HSPA+ networks. (Pro)</li>
<li>Fixed Mobile Network Settings shortcut.</li>
<li>Minor code optimizations and enhancements.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.6 (1/10/2013):</strong></span></p>
<ul>
<li>Resolved several issues on GSM devices.</li>
<li>Resolved force closes with Advanced shortcuts. (Pro)</li>
<li>Added menu shortcut to Mobile Network Settings.</li>
<li>Added BugSense automatic crash reporting tool.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.4 (1/6/2013):</strong></span></p>
<ul>
<li>Resolved several issues on GSM devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.2 (1/3/2013):</strong></span></p>
<ul>
<li>Resolved several issues on GSM devices.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 2.0 (1/2/2013):</strong></span></p>
<ul>
<li>First public release.</li>
</ul>
<p><span style="text-decoration: underline;"><strong>Version 1.x (2012)</strong></span></p>
<ul>
<li>Private beta testing.</li>
</ul>
