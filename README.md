com.macjutsu.super.plist assists with MacOS updates. I have added a plist that I have found useful. It will have a soft deadline of 5 deferrals for scheduling before you can't remove the window and a hard deadline of 5 days after which updates will automatically deploy

com.apple.applicationaccess defers major OS updates for 14 days so we have time to thoroughly test.

com.tinyspeck.slackmacgap sets default org, sets environment to corporate as opposed to gove and turns off auto updates so updates can be managed. This is critical for users that are not admin as slack prompts for credentials on updates

com.apple.notificationsettings turns off notifications for users when mdm adds login items

com.apple.extensiblesso.plist is for okta fastpass but does not support psso and we use jamf connect

Both Jamf Connect plists are settings I have found useful when deploying jamf connect with Okta Identity Engine

Okta profiles are for settings I've found helpful when deploying fastpass and for the necessary SSO Extension I did not include management attestation profiles as they are easiest to roll out through the MDM GUI. 



