# Driver_Drowsiness_system

This research presents a comprehensive system for real-time drowsiness
detection and alerting in an environment. The core functionality is based on
a multi-step process that continuously integrates image capture, landmark
localization, drowsiness metric computation, and adaptive alarm triggering.
The initial phase involves capturing images from a camera feed, providing a
continuous stream of visual data. Subsequently, a landmark localization
algorithm identifies key facial landmarks, enabling precise tracking of facial
features. The system lies in the calculation of Drowsiness Metric (DM),
which is derived from a designed formula. This metric serves as a
quantifiable indicator of the driver's alertness level, taking into account
various facial expressions. A critical decision-making step follows the metric
calculation. The system evaluates whether the drowsiness metric exceeds a
predefined threshold value. If the metric goes below this threshold, an alarm
is triggered instantly, serving as a vital alert to the driver. This alarm includes
audible and visual elements to ensure rapid response. Conversely, if the
drowsiness metric remains above the threshold, the system continues to
capture frames and count those frames. This research exemplifies the fusion
of image processing, facial analysis, and intelligent decision-making to create
a responsive and reliable drowsiness monitoring system.
