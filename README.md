# Operations Tracker: releases

This repository holds only the signed Windows installers for the Operations Tracker,
so installed copies can update themselves. There is no source code and no data here.

Each release has the installer (`Operations-Tracker-Setup-x.y.z.exe`) and `latest.json`,
which carries its checksum and a digital signature. The app installs an update only if
that signature matches the publisher's key.
