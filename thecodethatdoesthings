set PROFILE to "YOURPROFILEHERE"
if application "Google Chrome" is running then
	tell application "System Events" to tell process "Google Chrome"
		set frontmost to true
		click menu item PROFILE of menu 1 of menu bar item "People" of menu bar 1
	end tell
end if
if application "Google Chrome" is not running then
	tell application "Google Chrome"
		activate
	end tell
	tell application "System Events" to tell process "Google Chrome"
		set frontmost to true
		click menu item PROFILE of menu 1 of menu bar item "People" of menu bar 1
	end tell
end if
