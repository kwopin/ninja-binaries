# Ninja binaries for Windows and macOS

This repository contains the binaries of the Ninja tool (version 1.10.2) for
Windows and macOS, which are used by our development pipelines. This repository
is cloned in the respective workflows and the binary installed system-wide.
This technique is favored over using some community-provided Github Actions to
increase maintainability and control over foreign binaries.
