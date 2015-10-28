Mudlet Modules

The purpose of this project is to provide building blocks of a basic Imperian system, while at the same time serving as an example that people can use to develop their own Mudlet modules.  I've attempted to make the modules in this project independent of each other.  The only exception to this is the Prompt trigger, which uses state from a lot of different things to create an informative prompt display.  Modules heavily utilize events for communicating state changes to potential downstream scripts.

Project Structure
Each folder contains a number of xml files which together define the scripts, triggers and aliases used by the module.  The modules are as follows

* TargetAndPrompt - Handles setting and unsetting target, displaying target in the prompt, and checking if something is a target
* ShieldRaze - Watches the status of your target's shielding, displays visual queues when the status changes, maintains state variables and resets your queues when the target shields or puts up rebounding aura.


