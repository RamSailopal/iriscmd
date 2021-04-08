
AUTHOR - Raman Sailopal

BACKGROUND - Simple command line utility to interface with Intersystems IRIS environment via an IRIS session

USAGE - Parameter 1 - The instance name
        Parameter 2 - The namespace
        Parameter 3 - The objectscript command
      
  example:

     iriscmd "IRIS" "USER" 'S ^TEST("TEST")="TEST"'

This will set up a global TEST with a subscript TEST and a value TEST

PREREQUISITES - An installed version of intersystems IRIS (See iris repo for installation with Ansible)
              - grep installed on the machine running iriscmd
	
