The 1090 Megahertz Riddle (Second edition)
============================================================

View the current second edition draft at: [The 1090 Megahertz Riddle (Second edition) [draft]](https://raw.githubusercontent.com/junzis/the-1090mhz-riddle/master/book.pdf)

This is the working branch of the new (second) edition of the book, which features many new chapters, major re-structuring, and content updates.

The new book will be published by TU Delft Open publishing under [CC BY-NC-SA-4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license, which allows copy, redistribute, remix, transform, and build upon this book.

(Visit the first edition online at: [mode-s.org](http://mode-s.org))

---


The new structure of the book:

```
Chapter 1 Introduction
  Section 1.1 Background: the "death ray" that saves lives
  Section 1.2 The primary radar
  Section 1.3 The secondary radar
  Section 1.4 Mode S
  Section 1.5 ADS-B
  Section 1.6 Other Mode S services
  Section 1.7 Summary
Chapter 2 Quick Start: Hardware and Software to Receive Mode S Data
  Section 2.1 Range
  Section 2.2 Antenna
  Section 2.3 Receiver
  Section 2.4 Software tools
Chapter 3 ADS-B Basics
  Section 3.1 Message structure
  Section 3.2 Capability
  Section 3.3 ICAO address
  Section 3.4 ADS-B message types
  Section 3.5 Example of ADS-B message structure
  Section 3.6 Availability and transmission rate
  Section 3.7 ADS-B versions
Chapter 4 Aircraft Identification and Category
  Section 4.1 Identification (Call Sign)
  Section 4.2 Wake vortex category
  Section 4.3 Example
Chapter 5 Airborne Position
  Section 5.1 A over-simplified example
  Section 5.2 Compact Position Reporting
  Section 5.3 Globally unambiguous position decoding
  Section 5.4 Locally unambiguous position decoding
  Section 5.5 Altitude decoding
  Section 5.6 Verification of decoded positions
Chapter 6 Surface Position
  Section 6.1 Movement
  Section 6.2 Ground track
  Section 6.3 Position
  Section 6.4 Example
Chapter 7 Airborne Velocity
  Section 7.1 Example messages
  Section 7.2 Vertical Rate
  Section 7.3 Difference between GNSS and barometric altitudes
  Section 7.4 Sub-type 1 and 2: Ground Speed decoding
  Section 7.5 Subtype 3 and 4: Airspeed decoding
Chapter 8 Aircraft Operation Status
  Section 8.1 Version 0
  Section 8.2 Version 1
  Section 8.3 Version 2
Chapter 9 Uncertainties in ADS-B
  Section 9.1 Terminology
  Section 9.2 Version 0
  Section 9.3 Version 1
  Section 9.4 Version 2
Chapter 10 Error control in ADS-B
  Section 10.1 CRC error control
  Section 10.2 ADS-B parity
Chapter 11 Basics of Mode S services
  Section 11.1 Mode S message structures
  Section 11.2 Parity
  Section 11.3 ICAO address recovery
  Section 11.4 Two's complement coding
Chapter 12 All-call reply
Chapter 13 Surveillance replies
  Section 13.1 Message structure
  Section 13.2 Altitude code
  Section 13.3 Identity code
Chapter 14 Airborne Collision Avoidance System
  Section 14.1 Background
  Section 14.2 ACAS with Mode C Transponders
  Section 14.3 ACAS with Mode S Transponders
  Section 14.4 Message fields of ACAS coordination messages
Chapter 15 Comm-B replies
  Section 15.1 Structure
  Section 15.2 BDS
Chapter 16 Mode S Elementary Surveillance
  Section 16.1 Data link capability report (BDS 1,0)
  Section 16.2 Common usage GICB capability report (BDS 1,7)
  Section 16.3 Aircraft identification (BDS 2,0)
  Section 16.4 ACAS active resolution advisory (BDS 3,0)
Chapter 17 Mode S Enhanced Surveillance
  Section 17.1 Selected vertical intention (BDS 4,0)
  Section 17.2 Track and turn report (BDS 5,0)
  Section 17.3 Heading and speed report (BDS 6,0)
Chapter 18 Mode S meteorological services
  Section 18.1 Meteorological routine air report (BDS 4,4)
  Section 18.2 Meteorological hazard report (BDS 4,5)
Chapter 19 Inferencing of BDS codes
  Section 19.1 BDS codes identification logics
  Section 19.2 Identification of BSD 5,0 and 6,0
  Section 19.3 Examples
Chapter 20 Summary and beyond
  Section 20.1 Summary
  Section 20.2 Crowd-sourced networks
  Section 20.3 Additional data
  Section 20.4 Congestion
  Section 20.5 Future of ADS-B
```