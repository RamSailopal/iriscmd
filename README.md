
AUTHOR - Raman Sailopal

BACKGROUND - Simple command line utility to interface with Intersystems IRIS environment via an IRIS session

USAGE - Parameter 1 - The instance name
        Parameter 2 - The namespace
        Parameter 3 - The objectscript command
      
  example 1:

     iriscmd "IRIS" "USER" 'S ^TEST("TEST")="TEST"'

This will set up a global TEST with a subscript TEST and a value TEST, on an instance named IRIS and in the USER namespace

  example 2:
     
     iriscmd "IRIS" "USER" 'W ^TEST("TEST")'

This will return the TEST value created in example 1

PREREQUISITES - An installed version of intersystems IRIS (See iris repo for installation with Ansible)
              - grep installed on the machine running iriscmd
	
