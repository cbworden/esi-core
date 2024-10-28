## main
 - Mods to azure_pipelines.yml.

## 1.2.1 / 2024-09-28

 - Refactor .gitlab-ci.yml to build linux wheelhouse and upload to pypi.
 - Change .gitlab-ci.yml to use python 3.12.
 - Fix bug where "np" was used as a variable and an import in konno_ohmachi.
 - Allow python versions >3.9.
 - Change path in setup.py so shakemap modules start with esi_core.
 - Updates project construction to use pyproject.toml instead of setup.cfg
 - Remove .c files.
 - Add shakemap package to the build.
 - Remove unnecessary "c" subdirectory.

## 1.2.0 / 2023-06-06

- Fully implement shakemap portion of compiled code
- Alter pcontour compilation when OS is Windows
- Implement srand48 and drand48 in contour.c
- Remove `m` from libraries used in shakemap compilation
- Change path in setup.py so shakemap modules start with esi_core.
- Updates project construction to use pyproject.toml instead of setup.cfg
- Remove .c files.
- Add shakemap package to the build.
- Remove unnecessary "c" subdirectory.

## 1.0.1 / 2022-09-27

- Fixes install and dependency issues.

## 1.0.0 / 2022-09-18

- Initial release.
