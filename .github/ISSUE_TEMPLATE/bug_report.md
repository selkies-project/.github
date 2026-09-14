---
name: Bug report
about: Bugs that affect usage
title: ''
labels: bug
assignees: ''

---

**Describe the bug**
<!--
A clear and concise description of what the bug is.
-->

**To Reproduce**
<!--
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error or issue
-->

**Expected behavior**
<!--
A clear and concise description of what you expected to happen.
-->

**Screenshots**
<!--
If applicable, add screenshots to help explain your problem.
-->

**Environment**

 - Version of this project, and whether it was installed from a package, a container image, or source
 - Host OS Version: [e.g. Ubuntu 26.04, Arch Linux 2026.01.01]
 - Host GPU Model and Driver Version, where graphics are involved: [e.g. Intel UHD Graphics 750, VA-API 1.19, libva 2.12.0 (outputs from `vainfo`) / NVIDIA RTX 3070, 535.129.03 driver]
 - Browser Version, where a web client is involved: [e.g. Chrome 121, Firefox 124]
 - Any other information specific to your environment

**Additional context**
<!--
Add any other context about the problem here.
-->

 - [ ] I confirm that this issue is relevant to the scope of this project. If you know that upstream projects are the cause of this problem, please raise the issue there.
 - [ ] I confirm that I have read other open and closed issues and that duplicates do not exist.
 - [ ] I confirm that the issue is easily reproducible and explained thoroughly.
 - [ ] I confirm that relevant log files have been included as explained below. Any relevant additional log files have also been included.
 - [ ] I confirm that no portion of this issue contains credentials or other private information, and it is my own responsibility to protect my privacy.
 - [ ] I confirm that the authors of this issue do not willfully breach or infringe legal regulations, in any and all global law, regarding trademarks, trade names, logos, patents, or any and all other forms of external intellectual property, as well as adhering to software license terms of open-source and proprietary software projects.

<!--
 - ALL BUGS: read the error, then upload the log of whichever component failed. A container keeps its log files in `/tmp`.
 - If the issue relates to screen capture or the display server, upload the display server's log (`/var/log/Xorg.0.log` or `~/.local/share/xorg/Xorg.0.log` for X11, the compositor's own output for Wayland).
 - If the issue relates to the web client, open the browser console (F12) and include any errors or warnings. For WebRTC, also attach the JSON dump of `chrome://webrtc-internals`, and report which codecs the browser offers: `console.log(RTCRtpReceiver.getCapabilities('video').codecs)` after typing `allow pasting`.
 - If the issue relates to a TURN server, check that its configuration is valid and reachable. Where an ISP throttles a protocol, try TURN over TCP and TURN over TLS.
 - If the issue relates to encoding or GPU acceleration, describe your setup and driver installation as precisely as possible.
 - Add any other information as you wish.
-->
