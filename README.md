# duo_unix_psc
PSC's patches to DUO's duo_unix source

The patches provided here are applied to DUO's open source duo_unix
code, which works with Linux PAM to integrate DUO multi-factor
authentication with *nix services and tools. DUO's duo_unix integration
is described at https://duo.com/docs/duounix

Our patches modify default behavior and add functionality as documented
in the PEARC17 paper (PEARC17_paper_117.pdf) provided here.

Our initial patch implementation was done for duo_unix-1.9.14. We have
updated the patches for duo_unix-1.10.0, and provide that patch file
here. We plan to maintain the patches for future releases and will
publish those here as well.

An example walkthrough of applying the patches is provided on the
https://github.com/pscedu/duo_unix_psc/wiki page.

(c) Copyright 2018 Pittsburgh Supercomputing Center
