# Change Log

## 1.1.9 (08/30/2018)

### Improvements

- Fixed error that prevented users from signing up for groups.

## 1.1.8 (08/29/2018)

### Improvements

- Updated for BfA! Removed all Legion content.
- Started adding BfA raids and mythic plus dungeons.

## 1.1.7 (12/12/2017)

### Improvements

- Added missing mythic level raid detection setting in LFG (Thanks Kpi!)

## 1.1.6 (12/12/2017)

### Improvements

- Added missing Antorus achievements and id for Triunvirate (Thanks Kpi!)

## 1.1.5 (06/16/2017)

### Improvements

- Added missing Tomb of Sargeras achievements

## 1.1.4 (05/06/2017)

### Improvements

- Fixed issue that was preventing search results from displaying initially. This was due to Blizzard making some LFG functions private.

## 1.1.3 (04/05/2017)

### Improvements

- Added ids for new mythic plus dungeons (Upper & Lower Karazhan and Cathedral of Eternal Night).
- Added Tomb of Sargeras and some achievements exect for AoTC and Cutting Edge because I don't know the ids right now. Will add them once the raid actually comes out.

## 1.1.2 (03/30/2017)

### Improvements

- Updated for patch 7.2
- Added realm first achievements as highest earned for Emerald Nightmare, Trial of Valor, Nighthold, and Keystone Master.

## 1.1.1 (03/02/2017)

### Improvements

- Fixed issue with not always finding keystones in bags. This prevents the send mythic keystone option from showing up.
- Added new wording for options based upon what your signing up for. For example, signing up for mythic plus will now say "Send Mythic Plus Achievement". Previously it just said "Use Ahead of the Curve Whisper".

## 1.1.0 (03/01/2017)

### New Features

- Now you can link your mythic plus keystone from the role select dialog box if you are signing up for a mythic plus dungeon!

### Improvements

- Added mythic achievements for Xavius, Helya, and Gul'dan. So if you don't have Cutting Edge for Xavius the highest default will be the mythic kill achievement.
- Always check achievement whisper option now doesn't require a ui reload. **Breaking Change: Always check whisper dialog checkbox options will now be set back to defaults.**

## 1.0.0 (02/05/2017)

### New Features

- Added Mythic Plus and Karazhan!
- Clicking on the button or icon under Default Highest Achievements Found section will now link that achievement to your chat input box.

### Improvements

- Made search ui a bit better by showing results returned and a default option if you have never picked an override. (Thanks Velgana!)
- If no achievements are found under the Default Highest Achievements Found then a message will now appear.
- If no achievement is found under the Default Highest Achievements Found section it will no longer list that raid/dungeon.
- Minor code cleanup.
- Bliz options now has a configure button to open up the options menu.
- Added minimap icon. (Thanks Velgana!)

## 1.0.0 Beta 2 (02/02/2017)

### Improvements

- Changed default highest achievments found from input boxes to text descriptions since they can't be changed.
- Added AoTC achievment icons to default highest achievments found.
- Default highest achievments found will now update dynamically.

## 1.0.0 Beta 1 (02/01/2017)

### Features

- Automates the sending of Ahead of the Curve achievments when signing up for raid groups via the LFG system.
- Currently only works for Legion raids.
- Determines highest achievment found for the raid your signing up for on your account (Cutting Edge, Ahead of the Curve, Normal/LFR Achievement).
- Allows you to override defaults by picking any achievement you have completed. This override will send for any Legion raid you sign up for.
- When signing up for a group you have the option to send a whisper or not. If no default achievement is found and no override is set no whisper will be sent.
