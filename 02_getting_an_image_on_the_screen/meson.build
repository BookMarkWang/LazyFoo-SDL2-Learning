current_dir = meson.current_source_dir()
current_file = fs.name(current_dir) + '.cpp'
src = files(current_file)

executable(fs.name(current_dir), src,
            dependencies : [sdl2_dep],
            cpp_args : ['-O0', '-g', '-ggdb'])
