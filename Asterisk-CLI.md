# Asterisk CLI
The Asterisk command line interface (CLI) is reached by using the Linux shell command
``asterisk -r`` or ``rasterisk ``

If you want debugging output, add one or many v:s
``asterisk -vvvvvr``

The Asterisk server has to be running in the background for the CLI to start.

## General Commands

- !command: เรียกใช้คำสั่ง Shell ของ Linux เช่น การเคลียร์หน้าจอ ใช้คำสั่งดังนี้ !clear 
- abort halt: Cancel a running halt
- add extension: Add new extension into context
- add ignorepat: Add new ignore pattern
- add indication: Add the given indication to the country
- agent show: Show status of Asterisk Agents
- debug channel: Enable debugging on a channel
- dont include: Remove a specified include from context
- help: Display help list, or specific help on a command
- include context: Include context in another context
- load: Load a dynamic module by name
- logger reload: Reopen log files. Use after rotating the log files.
- mixmonitor {start|stop|list}: Execute a MixMonitor command.
- no debug channel: Disable debugging on a channel
- originate: originate a call.
- remove extension: Remove a specified extension
- remove ignorepat: Remove ignore pattern from context
- remove indication: Remove the given indication from the country
- save dialplan: Overwrites your current extensions.conf file with an exported version based on the current state of the dialplan. A backup copy of your old extensions.conf is not saved. The initial values of global variables defined in the [globals] category retain their previous initial values; the current values of global variables are not written into the new extensions.conf. Using “save dialplan” will result in losing any comments in your current extensions.conf.
- dialplan save (1.4): BROKEN, doesn’t parse correctly. Overwrites your current extensions.conf file with an exported version based on the current state of the dialplan. A backup copy of your old extensions.conf is not saved. The initial values of global variables defined in the [globals] category retain their previous initial values; the current values of global variables are not written into the new extensions.conf. Using “save dialplan” will result in losing any comments in your current extensions.conf.
- set verbose: Set level of verboseness
- show applications: Shows registered applications
- show application: Describe a specific application
- show channel: Display information on a specific channel
- show channels: Display information on channels
- show codecs: Display information on codecs
- show conferences: Show status of conferences
- show dialplan: Show dialplan
- show hints: Show registered hints
- show image formats: Displays image formats
- show indications: Show a list of all country/indications
- show locals: Show status of local channels
- show manager command: Show manager commands
- show manager connect: Show connected manager users
- show parkedcalls: Lists parked calls
- show queues: Show status of queues, see details here
- show switches: Show alternative switches
- show translation: Display translation matrix
- soft hangup: Request a hangup on a given channel – in Asterisk 1.6.2: “channel request hangup <name>”
- show voicemail users: List defined voicemail boxes
- show voicemail zones: List zone message formats
- devstate change: Change state of a custom device (new in Asterisk 1.6.0)
  
