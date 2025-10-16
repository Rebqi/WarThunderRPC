# WarThunder Discord Rich Presence (RPC)

## About

![image](https://github.com/ValerieOSD/WarThunderRPC/assets/144137904/2ff2533c-d962-42cf-a2f9-0d113e9029b5)

![image](https://github.com/ValerieOSD/WarThunderRPC/assets/144137904/26584cb8-37d0-4af3-b664-1c41f948fac1)


**This is a external application which adds War Thunder as a Discord Rich Presence application. \[1].**

\[1] This application **pulls in-game information from War Thunder through Port 8111**.
War Thunder outputs some in-game data to 127.0.0.1:8111 and it's subfolders automatically on all machines. There really isn't much to go off and it's pretty awfully structured, but it makes do for now.
This application modifies in no way whatsoever any data from the game, it is completely safe and will not get you banned.

### Requirements (Will add a .exe after some time when i think the time is Right)

 - [Python 3.11+](https://www.microsoft.com/store/productId/9NRWMJP3717K?ocid=pdpshare)

### Features

  - Shows if you are in the hangar, in a match, or in a test drive.
  - Shows what map you are in.
  - Detects what vehicle you are using.
  - Displays simple match statistics (Air or Ground, Domination or Conquest, etc).

Unfortunately some modes or vehicles aren't supported due to how the data is structured from the game itself,
Naval vehicles show no data and will not work, it will show up as "Unknown vehicle".


## How to Install

 1. Click on "Code"
 2. Download ZIP
 3. Run the application which Python whilst War Thunder is open


## Development

This Project is Originally from ValerieOSD and has been Updated by me to work again since she has Discontinued it. I have the Permission from her and will try my Best to Keep it Updated!

## Issues

 - Air vehicles selected in the hangar does not update RPC, updates when a ground vehicle is selected.
 - Some Maps still do not Show the Name, will take a bit to add all the recent ones
