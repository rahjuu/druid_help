---
title: What is BOOST?
weight: 10
---
BOOST is short for Battery Optimized Overclocking Strategy Tuning, a condition-triggered feature that can increase the frequency of data collecting (GPS and ENV). When BOOST is triggered, the minimal collecting interval can reach 20 seconds (the interval varies on different devices). The conditions that can trigger BOOST are listed below:

- Voltage<br>
  When the battery voltage is higher than the predefined threshold, BOOST is triggered automatically. When the battery voltage drops back to the threshold, BOOST stops.
<br>
- Speed<br>
  When the instant speed of the device and the battery voltage are higher than the predefined threshold, BOOST is triggered automatically. When the instant speed or the battery voltage drops back to the threshold, BOOST stops.

Note that the collecting interval is changed dynamically during the BOOST period.
