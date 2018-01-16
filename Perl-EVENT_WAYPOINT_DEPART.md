EVENT_WAYPOINT_DEPART
### Exports
**Name**|**Type**|**Description**
:-----|:-----|:-----
wp|int|
### Example
```perl
sub EVENT_WAYPOINT_DEPART {
	quest::say($wp); # returns int
}
```

### Functionality Explained

EVENT_WAYPOINT_DEPART is triggered when an NPC leaves its current grid waypoint entry.  

### EVENT_WAYPOINT_DEPART in use

```perl
sub EVENT_WAYPOINT_DEPART {

     # Use == for numeric comparison to match grid waypoint entry "0" (the spawn point of the NPC)
     if ($wp == 0) {
		quest::say("And we're off!");
	}
}
```
Generated On 2018-01-15T22:07:30-08:00