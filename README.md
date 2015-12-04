# fn-utilities
"F-n" or "f end" amazing utilities

dprf - Resets the Drupal login password of the user specified.
       If no user is provided, the default is the name of uid 1.

gitf - Search git logs for authors or commit message strings.

vif - Locate any Drupal function or class method and edit the
      file at the start line containing that function or method.
      It will locate core as well as contrib or even custom module
      functions and methods.

# Installation
Copy into your scripts directory (ex. ~/bin)

# Preconditions
Read the comments at the top of each script

# Usage
dprf \<password\> \[\<user\>\]

gitf \<string\>

vif \<Drupal function or class method\>

# Examples
dprf admin

dprf secret bob

gitf hello

vif user_access

vif view::update
