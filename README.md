# fn-utilities
"F-n" or "f end" amazing utilities

gitf - This script will search git logs for authors or commit message strings

vif - This script will locate any Drupal function or class method and
      edit the file at the start line containing that function or method.
      It will locate core as well as contrib or even custom module
      functions and methods.

# Installation
Copy into your scripts directory (ex. ~/bin)

# Preconditions
Read the comments at the top of each script

# Usage
gitf \<string\>

vif \<Drupal function or class method\>

# Examples
gitf hello

vif user_access

vif view::update
