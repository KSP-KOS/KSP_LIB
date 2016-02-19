KSP_LIB
=======
This is a repository used to enable travis-ci to build kOS without having KSP
installed, and without making the KSP dll files publicly available.  It serves a
compromise between protecting the intellectual property of Squad, and the
benefits that come with leveraging automated build testing.

* kos-[x.y.z].tar - tar containing dummy dlls that implement publicly accessible
KSP classes and their public members.  Credit to zengei of the #kspmodders IRC
channel (irc.esper.net) for sourcing these files.  These files are valid for the
KSP version identified by [x.y.z].
* kos-[x.y.z].tar.enc - encrypted tar containing dlls.  These files are valid
for the KSP version identified by [x.y.z].
