#
# .bash_profile file by Alexander Chernyy
#
# http://chernyy.[ru|com]
# alex@chernyy.ru
#

# Color table
# http://www.cyberciti.biz/faq/bash-shell-change-the-color-of-my-shell-prompt-under-linux-or-unix/

# Color generator
# http://terminal-color-builder.mudasobwa.ru

# Background & text color for prompt, 7 means white/gray color
# Recommended theme: Basic
# export PS1="\[$(tput setab 7)$(tput setaf 0)\]\h:\W \u\$\[$(tput sgr0)\] "

# Background & text color for prompt, 6 means cyan color
# Recommended theme: Half-hacker
export PS1="\[$(tput setab 6)$(tput setaf 0)\]\h:\W \u\$\[$(tput sgr0)\] "
