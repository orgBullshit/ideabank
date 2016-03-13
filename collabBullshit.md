collabBullshit - No-fuss pair programming
==============

- Pair Programming package for Atom
- motepair fork
  - motepair editor functionality is good
  - motepair file management needs work
    - motepair does not automatically sync filesystem changes between pairs, devs must manually create files. 
    - need a way to implement this without stepping on any toes - possibly generate tmp directory on "local" machine and copy changes across, purging dir when the session is closed. would prevent conflicts with git
  - motepair needs fancy crypto
