
- configure
% CPPFLAGS="-g -I{MTCPROOT}/mtcp/lib/ -I${MTCPROOT}/mtcp/src/include/ -I${MTCPROOT}/io_engine/include/ -DMULTI_THREADED" LIBS="${MTCPROOT}/mtcp/lib/libmtcp.a ${MTCPROOT}/io_engine/lib/libps.a -lpthread -lnuma -lrt" ./configure

- make
% make
