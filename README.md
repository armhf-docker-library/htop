[![Build Status](https://armdrone.strahlungsfrei.de/api/badges/armhf-docker-library/htop/status.svg)](https://armdrone.strahlungsfrei.de/armhf-docker-library/htop)

This is htop in a Docker container, for armhf devices. Run it with `--pid host` in order to see all processes on the host:

    docker run -it --rm --pid=host armhfbuild/htop

This should be especially useful on lightweight distributions who are built on Docker, but missing htop (like RancherOS ;)).
