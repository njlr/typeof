include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'typeof',
  header_only = True,
  header_namespace = 'boost/typeof',
  exported_headers = subdir_glob([
    ('include/boost/typeof', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
