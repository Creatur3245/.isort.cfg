# .isort.cfg
[settings]
profile = black
line_length = 88
multi_line_output = 3
include_trailing_comma = true
force_sort_within_sections = true
known_first_party = my_project  # Replace 'my_project' with your project name
known_third_party = django, flask, numpy  # Add third-party libraries
sections = FUTURE,STDLIB,THIRDPARTY,FIRSTPARTY,LOCALFOLDER
default_section = THIRDPARTY
lines_after_imports = 2