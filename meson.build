project('zimfuse', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3', 'cpp_std=c++11'])

libzim_dep = dependency('libzim', version : '>=7.2.0')
libfuse_dep = dependency('fuse3', version : '>=3.1')

executable('zimfuse',
           'main.cpp',
           dependencies : [libfuse_dep, libzim_dep],
           install : true)
