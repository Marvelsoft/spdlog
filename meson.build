project('spdlog',
        'cpp',
        version: run_command('cat', files('version.txt')).stdout().strip(),
        default_options: ['cpp_std=c++14'])

spdlog_inc = include_directories('include')
spdlog_dep = declare_dependency(include_directories: spdlog_inc)
