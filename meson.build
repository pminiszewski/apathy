project('apathy', 'cpp')

apathy_dep = declare_dependency(
  include_directories: [
    '.'
  ]
)

apathy_test_exe = executable('apathy_test', [
  'test.cpp'
],
include_directories: [
  'Catch/single_include'
],
dependencies: [
  apathy_dep
])

test('apathy test', apathy_test_exe)