scala_library(name='scala',
  dependencies=[
    '3rdparty:netty',
    'finagle/finagle-core',
    '3rdparty/jvm/com/twitter/common:stats-util',
    'util/util-core',
  ],
  sources=rglobs('*.scala'),
  provides=artifact(org='com.twitter',
                    name='finagle-mux',
                    repo='pants-support/ivy:internal',),
)
