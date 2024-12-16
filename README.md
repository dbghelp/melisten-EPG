# melisten-EPG
XML EPG for melisten radio stations

## Overview

This repository contains the XML EPG (Electronic Program Guide) for melisten radio stations. The EPG provides a schedule of the current and upcoming radio programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/melisten-EPG/refs/heads/main/melisten.xml

## Features

- XML formatted EPG for melisten radio stations
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/melisten-EPG/refs/heads/main/melisten.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/melisten-EPG/refs/heads/main/melisten.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id         | Channel Name   |
|----------------|----------------|
| indiego        | indiego        |
| Class95        | CLASS 95       |
| meradioAdMap   | GOLD 905       |
| 987            | 987            |
| CNA938         | CNA938         |
| Symphony924    | Symphony 924   |
| Yes933         | YES 933        |
| Love972        | LOVE 972       |
| Capital958     | CAPITAL 958    |
| Ria897         | RIA 897        |
| Warna942       | WARNA 942      |
| Oli968         | OLI 968        |
