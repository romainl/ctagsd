#!/usr/bin/env sh

# Requirements:
#     git: https://git-scm.com/downloads
#     entr: http://eradman.com/entrproject/
#     ctags: http://ctags.sourceforge.net/ (Exuberant Ctags) or https://ctags.io/ (Universal Ctags)

# Usage:
#     $ cd my_project
#     $ ctagsd

while true; do
	git ls-files --modified --exclude-standard --others | entr -dnp ctags -R .;
done
