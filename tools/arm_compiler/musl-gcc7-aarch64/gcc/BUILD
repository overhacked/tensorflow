package(default_visibility = ['//tools/arm_compiler/musl-gcc7-aarch64:__pkg__'])

filegroup(
  name = 'gcc',
  srcs = [
    '@MuslAarch64Gcc7//:gcc',
    'aarch64-linux-musl-gcc',
  ],
)

filegroup(
  name = 'ar',
  srcs = [
    '@MuslAarch64Gcc7//:ar',
    'aarch64-linux-musl-ar',
  ],
)

filegroup(
  name = 'ld',
  srcs = [
    '@MuslAarch64Gcc7//:ld',
    'aarch64-linux-musl-ld',
  ],
)

filegroup(
  name = 'nm',
  srcs = [
    '@MuslAarch64Gcc7//:nm',
    'aarch64-linux-musl-nm',
  ],
)

filegroup(
  name = 'gcov',
  srcs = [
    '@MuslAarch64Gcc7//:gcov',
    'aarch64-linux-musl-gcov',
  ],
)

filegroup(
  name = 'objcopy',
  srcs = [
    '@MuslAarch64Gcc7//:objcopy',
    'aarch64-linux-musl-objcopy',
  ],
)

filegroup(
  name = 'objdump',
  srcs = [
    '@MuslAarch64Gcc7//:objdump',
    'aarch64-linux-musl-objdump',
  ],
)

filegroup(
  name = 'strip',
  srcs = [
    '@MuslAarch64Gcc7//:strip',
    'aarch64-linux-musl-strip',
  ],
)

filegroup(
  name = 'as',
  srcs = [
    '@MuslAarch64Gcc7//:as',
    'aarch64-linux-musl-as',
  ],
)

filegroup(
  name = 'tool-wrappers',
  srcs = [
    ':gcc',
    ':ar',
    ':ld',
    ':nm',
    ':objcopy',
    ':objdump',
    ':strip',
    ':as',
  ],
)
