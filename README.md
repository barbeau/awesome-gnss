# awesome-gnss [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/barbeau/awesome-gnss/commits/master.atom)

##### Community list of open-source Global Navigation Satellite System (GNSS) software and resources :satellite:

Have something to add or change? Open a [pull request](https://github.com/barbeau/awesome-gnss/pulls) or [issue](https://github.com/barbeau/awesome-gnss/issues).

### Android apps (open-source)

- **GPSTest** ([Google Play](https://play.google.com/store/apps/details?id=com.android.gpstest), [F-Droid](https://f-droid.org/packages/com.android.gpstest.osmdroid/), [Source code](https://github.com/barbeau/gpstest)) - Supports dual-frequency GNSS for GPS, GLONASS, QZSS, BeiDou/COMPASS, Galileo, IRNSS, as well as various SBAS systems. Supports measuring accuracy using a ground truth location and file logging for NMEA, raw measurements, navigation messages, and location data. Logs are compatible with Google's [GPS Measurement Tools](https://github.com/google/gps-measurement-tools) suite to [visualize data](https://developer.android.com/guide/topics/sensors/gnss#analyze).
- **GNSS Compare** ([Google Play](https://play.google.com/store/apps/details?id=com.galfins.gnss_compare), [Documentation](https://gnss-compare.readthedocs.io), [Source code](https://github.com/TheGalfins/GNSS_Compare)) - Supporting calculating positions from raw measurements for GPS and Galileo. Beta support for dual-frequency.
- **Sat Stat** ([F-Droid](https://f-droid.org/packages/com.vonglasow.michael.satstat/), [Source code](https://gitlab.com/mvglasow/satstat)) - Android Location, Sensor and Radio Network Status.
- **GNSSLogger** ([Source code](https://github.com/google/gps-measurement-tools#gnsslogger)) - Log raw measurements for visualization in Google's [GPS Measurement Tools](https://github.com/google/gps-measurement-tools) suite.
- **RTKGPS+** ([Google Play](https://play.google.com/store/apps/details?id=gpsplus.rtkgps)) - Android frontend of [RTKLIB]((http://www.rtklib.com/)).

### iOS apps (open-source)

- **Overland-iOS** ([App Store](https://apps.apple.com/us/app/overland-gps-tracker/id1292426766), [Source code](https://github.com/aaronpk/Overland-iOS)) - An experiment at gathering data from an iPhone to test the Core Location API and its various settings.
- **Open GPX Tracker** ([App Store](https://apps.apple.com/app/open-gpx-tracker/id984503772), [Source code](https://github.com/merlos/iOS-Open-GPX-Tracker)) -  Open source GPX tracker app written in Swift. 

### Desktop tools

- **Google's GPS Measurement Tools suite** ([Download](https://github.com/google/gps-measurement-tools/releases), [Source code](https://insidegnss.com/gnss-analysis-tools-from-google/)) - Desktop companion app for GNSSLogger to visualize and analyze raw measurements. Supports Windows, Mac, and Linux.
- **EGNOS Toolkit** ([Download](https://sourceforge.net/projects/libegnos/files/), [Source code](https://sourceforge.net/projects/libegnos/))-  A set of tools to work with Satellite-Based Augmentation Systems (SBAS), specially EGNOS. Support Linux.
- **GNSS-SDR** ([Download](https://gnss-sdr.org/), [Source code](https://github.com/gnss-sdr/gnss-sdr)) - An open source GNSS software defined receiver. Supports Linux, Mac, and Windows.
- **RTKLIB** ([Download](http://www.rtklib.com/), [Source code](https://github.com/tomojitakasu/RTKLIB)) - An Open Source Program Package for GNSS Positioning. Has a companion Android app [RTKGPS+](https://play.google.com/store/apps/details?id=gpsplus.rtkgps). Supports Windows.
- **RNXCMP** ([Download](https://terras.gsi.go.jp/ja/crx2rnx.html)) - Open source software for Hatanaka compression/restoration of RINEX observation files.
- **GPSTk** ([Download](http://www.gpstk.org), [Source code](https://github.com/SGL-UT/GPSTk)) - C++ open source library and a suite of applications for GPS processing problems.
- **gLAB Lab** ([Download](https://gage.upc.es/gLAB/)) - Performs precise modeling of GNSS observables (pseudorange and carrier phase) at the centimetre level, allowing both standalone GPS positioning and PPP. Supports RINEX-3.00, SP3, ANTEX and SINEX, as well as GPS, Galileo, and GLONASS. Developed under an European Space Agency (ESA) contract by the Universitat Politecnica de Catalunya (UPC). Free to download but not open-source.
- **teqc** ([Download](https://www.unavco.org/software/data-processing/teqc/teqc.html)) - Translation, editing, and quality check of GNSS data in native and in RINEX/BINEX formats. Free to download but not open-source.

### Web tools (proprietary)

- [Jason Positioning-as-a-Service](https://jason.rokubun.cat) - Upload GNSS data (e.g., RINEX, u-blox files, GNSS logger files) and process it using Post-processing Kinematic (PPK) strategy. Automatically picks a nearby reference receiver. Currently free in beta, but will become a paid service with a free tier for evaluation and low-volume usage.
- [GNSS-Radar](http://www.taroz.net/GNSS-Radar.html) - GNSS coverage simulator over time for any given location.

### Social media

- [IGS](https://twitter.com/IGSorg) - International GNSS Service.
- [GSA](https://twitter.com/EU_GNSS) - European GNSS Agency.
- [GNSS Status](https://twitter.com/GNSS_Status) - GNSS satellites updated status.

### Blogs

- [rtklibexplorer](https://rtklibexplorer.wordpress.com/) - Using RTKLIB for precise positioning with low-cost GNSS receivers.
- [BlackDotGNSS](https://www.blackdotgnss.com/blog/) - Technical discussions related to GNSS data processing.

### Wikis

- [Navipedia](https://gssc.esa.int/navipedia/index.php/Main_Page) by ESA - An online reference for GNSS systems and data processing.

### Videos

- [*How to get one-meter location-accuracy from Android devices (Google I/O '18)*](https://www.youtube.com/watch?v=vywGgSrGODU) by Google - Discussion of calculating position from raw GNSS measurements, including carrier phase measurements, as well as Wi-Fi RTT.

### Articles

- [*Dual-frequency GNSS on Android devices*](https://medium.com/@sjbarbeau/dual-frequency-gnss-on-android-devices-152b8826e1c) by Sean Barbeau - Discussion of dual-frequency GNSS support on Android, including screenshots showing device support for dual-frequency in GPSTest.
- [*tl;dr — Dual-frequency GNSS on Android — Table of devices*](https://medium.com/@sjbarbeau/tl-dr-dual-frequency-gnss-on-android-table-of-devices-9be4bbb83a7b) by Sean Barbeau - Table summarizing the above article.
- [*Measuring GNSS Accuracy on Android devices*](https://medium.com/@sjbarbeau/measuring-gnss-accuracy-on-android-devices-6824492a1389) by Sean Barbeau - Discussion of *estimated* and *actual* accuracy on Android, including the feature in GPSTest to measure actual accuracy.
- [*Using GNSS Raw Measurements on Android Devices*](https://www.gsa.europa.eu/system/files/reports/gnss_raw_measurement_web_0.pdf) by GSA GNSS Raw Measurements Task Force - Technical discussion of how to determine a device's position based on raw pseudorange measurements provided via Android APIs.
- [*Android - Raw GNSS Measurements*](https://developer.android.com/guide/topics/sensors/gnss) by Google - Lists Android devices that support raw GNSS measurements as well as documentation for [GNSSLogger](https://github.com/google/gps-measurement-tools#gnsslogger) and Google's [GPS Measurement Tools](https://github.com/google/gps-measurement-tools) suite.
- [*GNSS Analysis Tools from Google*](https://insidegnss.com/gnss-analysis-tools-from-google/) by Inside GNSS - Discussion of Google's [GPS Measurement Tools](https://github.com/google/gps-measurement-tools) suite.
- [*SAR and GNSS, monitoring Earth from space*](https://medium.com/worldsensing-techblog/sar-and-gnss-monitoring-earth-from-space-24d12c31b3b) by Toni M. del Hoyo in Worldsensing's Tech Blog - Overview on Global Navigation Satellite systems and on Synthetic Aperture Radar

### Books

- [GNSS Data Processing books](https://gage.upc.es/forum/gnss-books/) by UPC/gAGE - Theory and exercises to learn GNSS data processing (e.g., range modelling, navigation equations, Kalman filter)

### Lists

- [Upcoming satellite launches](https://www.gpsworld.com/resources/upcoming-gnss-satellite-launches/) by GPS World
- Galileo
  - [Supported devices (official)](https://www.usegalileo.eu/EN/inner.html#data=smartphone)
  - [Real-time status (official)](https://www.gsc-europa.eu/system-service-status/constellation-information)
- QZSS
  - [Supported devices (official)](https://qzss.go.jp/en/usage/products/list.html#smartphones-tablet-computers)
- WAAS
  - [Real-time status (official)](https://www.nstb.tc.faa.gov/RT_WaasSatelliteStatus.htm)
