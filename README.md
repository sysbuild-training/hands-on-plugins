# Plugins for hands-on-base system extension

## Overview

[hands-on-base](https://github.com/sysbuild-training/hands-on-base) 
has been extended to support the startup script.
It is similar to the cloud-init (AWS) or /etc/rc.local (traditional Unix) script.

debian-pc container runs the script once at the startup time 
if the environment variable RC_LOCAL_SCRIPT_URL is defined.


## Plugin lists

- [lpic-2024q2](lpic-2024q2)
    - a dummy script to show just a message.
    - LPI Webinar 2024-06-08 version does not use this extension.


## License

Creative Commons BY-NC-SA [4.0](https://creativecommons.org/licenses/by/4.0/deed.en).

<HR>
Last-Modified: 2024-08-03
Copyright (C) 2024 Ken'ichi Fukamachi, CC BY-NC-SA 4.0
