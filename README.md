# Human & Resource Allocation Management

This system is designed to be non-specific about the allocation of humans and resources (physical, knowledge, etc.).  It could (theoretically) be used for more than this, but we had to draw the line somewhere.

This will include discussions of:

* __Things__ (human, physical, knowledge, etc.)
* __Time__ (must include a specific beginning and end)
* __Space__ (must include a physical space)

These can be associated in a number of ways:

* __Allocations__ (assignments of a Thing to a Time & Space)
* __Requests__ (desired assignments [holds] of a Thing [in a Time & Space or indefinite])
* __Opportunities__ (availability of a Thing [in a Time & Space or indefinite])
* __Priorities__ (rankings of Things, Requests or Opportunitys)
* __Reviews__ (ratings of a Thing or Allocation)

These can be controlled based on `Read/Write` or `Read-Only` permissions that are:

* System-wide
* Subset only (e.g. within a building)
* Individual access


## VIEWS (i.e. Displays)
----
* Index (lists of things)
* Show (display a things)
* New (create a thing)
* Edit (edit a thing)


## ACTIONS (i.e. Requests)
----
* Index (display a list of things)
* Show (display a thing )
* New (display the "new thing" form - so it can be entered)
* Create (accept the new submission and save it)
* Edit (display the "edit a thing" form)
* Update (accept the edited submission and save it)
* Destroy (accept the delete request and delete it)
* Batch Create (accept a list of new submissions and save them)
* Batch Update (accept a list of edited submissions and save them)
* Batch Download (request a list of things)


## VIEWS IN DETAIL
----
__Index-List__

* Things
* Times
* Spaces
* Allocations
* Requests
* Opportunities
* Priorities
* Reviews


Postings (by category, by time)
  * available to everyone
  * available to this user
  * booked by this user
    * per day
    * per school
    * per day
    * per week
    * per month (calendar)
    * per 3-months (calendar)
* All not-available days
  * by person
* All people (by role)
  * system-wide Administrators
  * system-wide viewers
  * school Administrators
  * school Administrative Assistants
  * Supply members
  * staff members
* All schools
  * by district
  * by area
  * by El/Md/Sr - age/grade/category
  
__Show__ (show available and booked bookings)

* A posting (Supply/TASupply/Teacher/TA/Admin/Assistant/SysAdmin)
* A not-available day (Supply/TASupply/SysAdmin)
* A person (Supply/TASupply/Teacher/TA/Admin/Assistant/SysAdmin)
* A preferred school (Supply/TASupply/SysAdmin)
* A school (Admin/SysAdmin)  
  
__New-Create/Edit-Update/Delete-Destroy__

* A posting (Supply/TASupply/Teacher/TA/Admin/Assistant/SysAdmin)
* A not-available day (Supply/TASupply/SysAdmin)
* A person (Supply/TASupply/Teacher/TA/Admin/Assistant/SysAdmin)
* A preferred school (Supply/TASupply/SysAdmin)
* A school (Admin/SysAdmin)

