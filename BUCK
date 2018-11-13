prebuilt_cxx_library(
  name = 'supercluster', 
  header_namespace = '', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.mapbox-geometry.hpp//:geometry', 
    'buckaroo.github.buckaroo-pm.mourner-kdbush.hpp//:kdbush', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)