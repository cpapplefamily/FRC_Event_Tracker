# FRC_Event_Tracker
Web based application to track and map different states a team or robot transitions through at an event.  

## Vision
Initial vision is to create an application to dynamically create a map of teams using the pit layout at an event for volunteers to track the status of a team through the process of Load-In and Load-Out. 

## Other Possible Uses 
* Robot Inspection
* Pit Scouting

## Wants
* Use Event Code for TBA synchronization
* Event Modes
    * Load In
    * Load Out
    * Inspection 
* Team States in above Modes
    * Load In Que
        * Unloading
        * Unload Complete
        * Unload Complete Will return in the morning to Set up
    * Load Out
        * Pit/Team Ready for Load Out
        * Vehicle in Load Out Que
        * Vehicle Loading Out
        * Load Out complete
    * Inspection
        * Inspection Ready
        * Inspector Assined (With Name)
        * Inspection Started
        * Inspection Paused
        * Inspection Complete
        * Notes
* Other things to track
    * Vehicle Size and type
* General Notes section

# Possible GUI actions
* Use multiple image types to overlay colored team state boxes of teams in the different event modes
* Use Dynamic Value: Par format to define regions of the map for highlighting states and accessing Notes.
* View Only mode



