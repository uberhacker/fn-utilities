# fn-utilities
"F-n" or "f end" amazing utilities

dprf - Resets the Drupal login password of the user specified.
       If no user is provided, the default is the name of uid 1.

flf - Find all files with a size larger the \# megabytes.

gitf - Search git logs for authors or commit message strings.

vif - Locate any Drupal function or class method and edit the
      file at the start line containing that function or method.
      It will locate core as well as contrib or even custom module
      functions and methods.

# Installation
```
$ git clone https://github.com/uberhacker/fn-utilities.git
$ sudo cp fn-utilties/* /usr/local/bin
```

# Preconditions
Read the comments at the top of each script.

# Usage
dprf \<password\> \[\<user\>\]

flf \#

gitf \<string\>

vif \<Drupal function or class method\>

# Examples
```
$ cd /path/to/my/drupal/root/directory
$ dprf admin
```
  *Reset the admin user password to admin*

```
$ cd /path/to/my/drupal/root/directory
$ dprf secret bob
```
  *Reset the bob user password to secret*

```
$ flf 100
```
  *Find all files with a size larger than 100 megabytes*

```
$ gitf hello
```
  *Find all authors or commit messages with the word hello in the git logs*

```
$ vif user_access
```
  *Locate the user_access function and open in vim*

```
$ vif view::update
```
  *Locate the view::update class method and open in vim*
