SSRC = psnaitr.f psnapps.f psnaup2.f psnaupd.f psneigh.f psneupd.f psngets.f \
       pssaitr.f pssapps.f pssaup2.f pssaupd.f psseigt.f psseupd.f pssgets.f \
       psgetv0.f pslamch.f pslarnv.f psnorm2.f

DSRC = pdnaitr.f pdnapps.f pdnaup2.f pdnaupd.f pdneigh.f pdneupd.f pdngets.f \
       pdsaitr.f pdsapps.f pdsaup2.f pdsaupd.f pdseigt.f pdseupd.f pdsgets.f \
       pdgetv0.f pdlamch.f pdlarnv.f pdnorm2.f

CSRC = pcnaitr.f pcnapps.f pcnaup2.f pcnaupd.f pcneigh.f pcneupd.f pcngets.f \
       pcgetv0.f pclarnv.f pscnorm2.f

ZSRC = pznaitr.f pznapps.f pznaup2.f pznaupd.f pzneigh.f pzneupd.f pzngets.f \
       pzgetv0.f pzlarnv.f pdznorm2.f

EXTRA_DIST = debug.h stat.h

noinst_LTLIBRARIES = libparpacksrc.la
libparpacksrc_la_SOURCES = $(SSRC) $(DSRC) $(CSRC) $(ZSRC)
