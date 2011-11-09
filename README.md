# Human & Resource Allocation Management

This system is designed to be non-specific about the allocation of humans and resources (physical, knowledge, etc.).  It could (theoretically) be used for more than this, but we had to draw the line somewhere.

The __delimiters__ will be:

* __Thing Class__
  * __User__ (Someone who logs in to makes or breaks Allocations of Things.  May also be a Thing [see below].)
  * __Thing__ (Something that can be allocated: a person, object, room, cyberspace location, body of knowledge, etc.)
  * __Time__ (Some finite time when the allocation begins and ends)
  * __Space__ (Somewhere to which a thing can be allocated: a place albeit physical, cyber, imaginary, etc.  May also be a Thing.)
* __Relationships__
  * __Allocation__ (Tying a Thing to a Time and Space)
  * __Privilege__ (Some restriction placed on a User with regard to Things or Categories [see below])
  * __Category__ (Some groupings of Things)
  * __Preference__ (Some rankings of Things or Categories)
  * __Qualification__ (Some requirements of Things being Allocated)
  * __Review__ (Some ratings of Things or Allocation transactions [see below])
* __Allocation States__
  * __Availability__ (unrequested and unassigned Things [nil Allocation])
  * __Opportunity__ (requested but unassigned Allocations [pending Allocation])
  * __Override__ (unrequested and assigned Allocations [manual-override Allocation])
  * __Booking__ (requested and assigned Allocations [expected-process Allocation])


## BREAKDOWN OF TASKS

----
### VIEWS (i.e. Displays)

* __Index__ (list of things)
* __Show__ (display a things)
* __New__ (create a thing)
* __Edit__ (edit a thing)


----
### ACTIONS (i.e. Requests)

* __Index__ (display a list of things)
* __Show__ (display a thing )
* __New__ (display the "new thing" form - so it can be entered)
* __Create__ (accept the new submission and save it)
* __Edit__ (display the "edit a thing" form)
* __Update__ (accept the edited submission and save it)
* __Destroy__ (accept the delete request and delete it)
* __Batch Create__ (accept a list of new submissions and save them)
* __Batch Update__ (accept a list of edited submissions and save them)
* __Batch Download__ (output a list of things)

