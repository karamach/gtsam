# cd $NEOREPO/third_party/gtsam
# mkdir -p bld/install 
# cd bld
# cmake -DCMAKE_INSTALL_PREFIX=$NEOREPO/third_party/gtsam/bld/install ..
# make check
# make install

licenses(["notice"])

cc_library(
    name = "gtsam",
    srcs = glob(["bld/install/lib/**/*.so"]),
    hdrs = glob(["bld/install/include/**/*.h"]),
    visibility = ["//visibility:public"],
    linkstatic = 1,
)

