<!--
https://readme42.com
-->



[![](https://img.shields.io/badge/OS-Unix-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/v/gist-generator.svg?maxAge=3600)](https://pypi.org/project/gist-generator/)
[![](https://img.shields.io/npm/v/gist-generator.svg?maxAge=3600)](https://www.npmjs.com/package/gist-generator)[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/gist-generator/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/gist-generator/actions)

### Installation
```bash
$ [sudo] pip install gist-generator
```

```bash
$ [sudo] npm i -g gist-generator
```

#### How it works
+   description as folder name. or `description.txt` if exist
+   `gitignore` supported
+   clones `.git` after gist creation
+   skip if `.git` exists

#### Config
```bash
$ export GITHUB_TOKEN="<GITHUB_TOKEN>"
```

#### Examples
```bash
$ gist-generator .
```

private gist
```bash
$ gist-generator -p .
```

create multiple gists
```bash
$ find ~/git/gists -type d -mindepth 1 -maxdepth 1 -exec gist-generator {} \;
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
