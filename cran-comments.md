RSQLite 2.3.4

## R CMD check results

- [x] Checked locally, R 4.3.2
- [x] Checked on CI system, R 4.3.2
- [x] Checked on win-builder, R devel

## Current CRAN check results

- [x] Checked on 2023-12-07, problems found: https://cran.r-project.org/web/checks/check_results_RSQLite.html
- [x] WARN: r-devel-linux-x86_64-debian-clang, r-devel-windows-x86_64 r-devel-linux-x86_64-debian-gcc, r-devel-linux-x86_64-fedora-clang, r-devel-linux-x86_64-fedora-gcc
     Found the following significant warnings:
     connection.cpp:62:7: warning: format specifies type 'int' but the argument has type 'long' [-Wformat]
     Fixed
