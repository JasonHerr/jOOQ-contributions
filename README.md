jOOQ-Contributions
==================

This repository contains hosted third party contributions to jOOQ, licensed under the terms of the ASL 2.0. Unless otherwise stated, the respective contributors retain their copyrights to their contributions. By contributing such extensions, contributors agree to the jOOQ Contributor License Agreement [TODO: Link here]

Contributors are required to provide contributions in the following directory layout:

```ini
# All contributions go into this directory structure. [contribution-name] may be
# chosen freely, but most not infringe any third-party trademark rules. If names
# contain "jOOQ", they will be reviewed by Data Geekery
/contributions/[contribution-name]/

# All contributions must contain a property file containing the following info:
# name=A plain text name for your contribution
# description=A short description (140 characters) describing your contribution
# author=Your first and last name, and E-Mail address. E.g. Lukas Eder <lukas.eder@datageekery.com>
/contributions/[contribution-name]/contribution.txt

# This mandatory file will contain your custom GitHub style markdown text
# with your contribution description, help page, guides, etc.
/contributions/[contribution-name]/description.md

# This directory contains all downloadable files to be published on www.jooq.org
# For example, it can contain .jar, .zip files, etc.
/contributions/[contribution-name]/[version]/files

# This optional file may contain file descriptions in the following form:
# [file-name.zip]=A plain text description
/contributions/[contribution-name]/[version]/files.txt
```

More information about the GitHub markdown style can be seen here:
https://help.github.com/articles/github-flavored-markdown
