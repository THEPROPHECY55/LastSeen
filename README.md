# LastSeen

**LastSeen** is a BetterDiscord plugin that tracks the "Last Seen" time of a specific user, showing the last time they were online.

## Description

This plugin monitors the online status of a specified user and updates their "Last Seen" time when they go offline. The "Last Seen" information is saved as a note in their profile, making it easy to check later.

## Usage

1. **Edit the Code**:  
   Open the plugin file and replace the following line with the Discord ID of the user you want to track:
   ```javascript
   this.userId = "12345"; // Replace with the target user's ID
   ```
   If you're unsure how to get someone's Discord ID, search online for a guide to enabling Developer Mode in Discord.

2. **Load the Plugin**:
Place the modified plugin file into your BetterDiscord plugins folder and enable it in the plugin settings.

3. **Check the Note**:
The "Last Seen" time will be displayed as a note in the tracked user's profile when they were last online.

## Features
Tracks a single user's "Last Seen" time.
Updates only when the user transitions from online to offline.
Works silently in the background without notifications.
