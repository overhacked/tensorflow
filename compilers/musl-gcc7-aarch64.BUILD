package(default_visibility = ['//visibility:public'])

filegroup(
  name = 'gcc',
  srcs = [
    'bin/aarch64-linux-musl-gcc',
  ],
)

filegroup(
  name = 'ar',
  srcs = [
    'bin/aarch64-linux-musl-ar',
  ],
)

filegroup(
  name = 'ld',
  srcs = [
    'bin/aarch64-linux-musl-ld',
  ],
)

filegroup(
  name = 'nm',
  srcs = [
    'bin/aarch64-linux-musl-nm',
  ],
)

filegroup(
  name = 'objcopy',
  srcs = [
    'bin/aarch64-linux-musl-objcopy',
  ],
)

filegroup(
  name = 'objdump',
  srcs = [
    'bin/aarch64-linux-musl-objdump',
  ],
)

filegroup(
  name = 'strip',
  srcs = [
    'bin/aarch64-linux-musl-strip',
  ],
)

filegroup(
  name = 'as',
  srcs = [
    'bin/aarch64-linux-musl-as',
  ],
)

filegroup(
  name = 'compiler_pieces',
  srcs = glob([
    'aarch64-linux-musl/**',
    'libexec/**',
    'lib/gcc/aarch64-linux-musl/**',
    'include/**',
  ]),
)

filegroup(
  name = 'compiler_components',
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
