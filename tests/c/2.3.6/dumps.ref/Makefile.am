include $(top_srcdir)/config/automake.common

SUFFIXES = .med .dump

.med.dump:
	@H5DUMP@ $< > $@

test2.dump: test2.med
	@H5DUMP@ -a /ENS_MAA/maa1/DIM -a /ENS_MAA/maa1/DES -a /ENS_MAA/maa1/TYP -g /ENS_MAA/maa2 -g /ENS_MAA/maa3 -g /INFOS_GENERALES $< > $@

#BUILT_SOURCES = 

check-local: ./test10.dump\
./test12.dump\
./test14.dump\
./test16.dump\
./test18.dump\
./test19.dump\
./test1.dump\
./test20.dump\
./test21.dump\
./test23.dump\
./test25.dump\
./test27.dump\
./test29.dump\
./test31.dump\
./test2.dump\
./test4.dump\
./test6.dump\
./test8.dump


CLEANFILES = \
./test10.dump\
./test12.dump\
./test14.dump\
./test16.dump\
./test18.dump\
./test19.dump\
./test1.dump\
./test20.dump\
./test21.dump\
./test23.dump\
./test25.dump\
./test27.dump\
./test29.dump\
./test31.dump\
./test2.dump\
./test4.dump\
./test6.dump\
./test8.dump

EXTRA_DIST = \
./test10.med\
./test12.med\
./test14.med\
./test16.med\
./test18.med\
./test19.med\
./test1.med\
./test20.med\
./test21.med\
./test23.med\
./test25.med\
./test27.med\
./test29.med\
./test31.med\
./test2.med\
./test4.med\
./test6.med\
./test8.med


