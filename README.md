# RBDC Package for PlatformIO

This is a PlatformIO (PIO) package to automatically import the RBDC and his dependencies as libraries in PIO.

This is mostly a github submodule link to the RBDC, but it adds the necessary PIO manifest file `library.json`.

To add the library to your PIO project, you will need to add this line in your project lib dependencies:

``````
[env]
lib_deps =
; This will include the RBDC and all his dependencies :
  https://github.com/catie-aq/pio_rbdc-package.git#v0.2.0
``````
