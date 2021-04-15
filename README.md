# tasker-low-battery-alert
Tasker(https://tasker.joaoapps.com/) script to send email alert when the battery percentage is low.

Description

I wanted to create a simple task to send me an email with the current location as the battery percentage gets low from my son's phone.
Usage

I configured a series of profiles to run when the battery is between 5 and 20% but that could easily be adjustable.

Profile Description

Profile: Low Battery 20 (2)
Restore: no
State: Battery Level [ From:20 To:25 ]
State: Not Power [ Source:Any ]
Enter: Low Battery Alert (3)
A1: Get Location v2 [  Timeout (Seconds):30 Minimum Accuracy (meters): Speed (meters/second): Altitude (meters): Near Location: Enable Location If Needed:Off Last Location If Timeout:Off Min Speed Accuracy (m/s): ]
A2: Send email [ Configuration:Send email from <user@server.com> to <user@server.com> Timeout (Seconds):0 ]
A3: Flash [ Text:Alert, battery is low!
%BATT Long:Off ]

Exit: Low Battery Alert (3)
A1: Get Location v2 [  Timeout (Seconds):30 Minimum Accuracy (meters): Speed (meters/second): Altitude (meters): Near Location: Enable Location If Needed:Off Last Location If Timeout:Off Min Speed Accuracy (m/s): ]
A2: Send email [ Configuration:Send email from <user@server.com> to <user@server.com> Timeout (Seconds):0 ]
A3: Flash [ Text:Alert, battery is low!
%BATT Long:Off ]

Profile: Low Battery 10 (4)
Restore: no
State: Battery Level [ From:10 To:15 ]
State: Not Power [ Source:Any ]
Enter: Low Battery Alert (3)
A1: Get Location v2 [  Timeout (Seconds):30 Minimum Accuracy (meters): Speed (meters/second): Altitude (meters): Near Location: Enable Location If Needed:Off Last Location If Timeout:Off Min Speed Accuracy (m/s): ]
A2: Send email [ Configuration:Send email from <user@server.com> to <user@server.com> Timeout (Seconds):0 ]
A3: Flash [ Text:Alert, battery is low!
%BATT Long:Off ]

Exit: Low Battery Alert (3)
A1: Get Location v2 [  Timeout (Seconds):30 Minimum Accuracy (meters): Speed (meters/second): Altitude (meters): Near Location: Enable Location If Needed:Off Last Location If Timeout:Off Min Speed Accuracy (m/s): ]
A2: Send email [ Configuration:Send email from <user@server.com> to <user@server.com> Timeout (Seconds):0 ]
A3: Flash [ Text:Alert, battery is low!
%BATT Long:Off ]

Profile: Low Battery 5 (5)
Restore: no
State: Battery Level [ From:5 To:7 ]
State: Not Power [ Source:Any ]
Enter: Low Battery Alert (3)
A1: Get Location v2 [  Timeout (Seconds):30 Minimum Accuracy (meters): Speed (meters/second): Altitude (meters): Near Location: Enable Location If Needed:Off Last Location If Timeout:Off Min Speed Accuracy (m/s): ]
A2: Send email [ Configuration:Send email from <user@server.com> to <user@server.com> Timeout (Seconds):0 ]
A3: Flash [ Text:Alert, battery is low!
%BATT Long:Off ]

Exit: Low Battery Alert (3)
A1: Get Location v2 [  Timeout (Seconds):30 Minimum Accuracy (meters): Speed (meters/second): Altitude (meters): Near Location: Enable Location If Needed:Off Last Location If Timeout:Off Min Speed Accuracy (m/s): ]
A2: Send email [ Configuration:Send email from <user@server.com> to <user@server.com> Timeout (Seconds):0 ]
A3: Flash [ Text:Alert, battery is low!
%BATT Long:Off ] 
