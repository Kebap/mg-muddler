mg-muddler
==========

Trying to muddle code for MorgenGrauen

Upstream
--------

- muddle: 
  - https://github.com/demonnic/muddler
  - https://github.com/demonnic/muddler/wiki 
  - https://demonnic.com/?p=140
- MorgenGrauen: https://github.com/MorgenGrauen/mg-mudlet

Status
------

- Created muddle workflow file in /.github
- Copied all items (triggers, alias, etc.) from original package into muddle src files
  - Only missing is configuration of folders, incl. comments in folders, order of folders
  - Opened feature requests with demonnic upstream to possibly add those in the future
- Workflows run alright
  - "Actions" tab shows list of current and last workflows
  - Standard duration for muddle is 20-30sec, very nice
  - Errors may be obscure, but will indicate line number (not file name)
  - Note: JSON does not like trailing commas at end of lists (trigger.json)
  - Note: JSON needs every single backslash escaped, make it a double slash
- Package can be downloaded 
  - Artifact is hidden in a different space than demonnic blogged
  - Click "summary" in workflow action and scroll down to see & download
- Package seems fine
  - Noted a few differences in resulting XML file structure
  - Import .zip to Mudlet works fine, triggers seem very alike

Plan
----

- Need to judge if moving items and refactoring code becomes easier in lua files & json or not
- At least more new contributors can easier see and edit files than in between XML configuration!
- Test [Plan](#plan)
