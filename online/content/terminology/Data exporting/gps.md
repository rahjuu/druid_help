---
title: GPS data
date: 2017-10-17T15:26:15Z
draft: false
weight: 36
---

The table below gives the explanations to the data fields of the exported GPS data.

| Data field           | Explanation                                                  |
| -------------------- | ------------------------------------------------------------ |
| SN                   | Serial Number.                                               |
| UUID                 | Universally Unique Identifier, a 128-bit number used to identify information in computer systems. |
| Transmitting time    | Time the device communicates with the server, accurate to milliseconds. |
| Collecting time      | Time the device collects data, accurate to seconds.          |
| Longitude            | Longitude of the GPS fix in degrees, accurate to 7 decimal places. |
| Latitude             | Latitude of the GPS fix in degrees, accurate to 7 decimal places. |
| Altitude             | Altitude of the GPS fix in meters, accurate to 2 decimal places. |
| Geoid height         | Geoid height of the GPS fix in meters. The geoid is the shape that the ocean surface would take under the influence of the gravity and rotation of Earth. |
| Speed                | Movement speed of the device in meters.                      |
| Course               | The angle between the clockwise direction from the north and the movement direction of the device. The value range is 0 ~ 359.9, where 0 means the device moves towards north. |
| Satellite            | Number of satellites connected for positioning.              |
| Positioning mode     | Valid values are 0, 1, and 2, where 0 represents a failed positioning, 1 represents 2D positioning, 2 represents 3D positioning. |
| HorAccuracy          | Index of horizonal accuracy of GPS positioning. Lower value indicates that the positioning is more accurate. |
| VerAccuracy          | Index of vertical accuracy of GPS positioning. Lower value indicates that the positioning is more accurate. |
| Time for Positioning | Time spent in one positioning session in seconds.            |
| Data Source          | Modes of data collecting. Valid values are 1, 2, and 4, where 1 represents scheduled collecting, 2 represents dynamic collecting, 4 represents in-flight collecting. |

