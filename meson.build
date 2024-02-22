project('pulseaudio-volume-watch', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3', 'cpp_std=c++14'])

pulseaudiodep = dependency('libpulse')
executable('pulseaudio-volume-watch',
           'pulsetest.cc',
           dependencies : pulseaudiodep,
           install : true)
