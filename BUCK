include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'fruit',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', 'fruit/**/*.h'),
    ('configuration/bazel', '**/*.h'),
  ]),
  srcs = glob([
    'src/*.cpp',
  ]),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
