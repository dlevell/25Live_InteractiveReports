Overview:
This report counts the total number of changes made in an event search based off the version number. 


When an event is created in 25Live, it starts with version 1. Each save after increases the change incrementally by 1. (ie. first save is version 1, second save is version 2 and so on.). 

Note: It appears that an event created in R25 starts with Version 0.

Since created events are version 1 in 25Live, you could add a filter to only look at VERSION_NUMBER > 1 and it would not show created events (except those created in R25 and edited once. :) ) 

Fields in the report:
Event Locator
Event Name
Event Title
Created Date
Last Modified Date
Last Modified User
Version number
Summary of version number
NEED TO ADD: Event Search to Footer

Parameters needed in 25Live:
Event Search

Queries used:
Q_REPORT_RUN
Q_EV_EXT_HIST

Summaries:
Sum_Version_Nbr

Formulas
F_URL_EventsExt_History (to Q_REPORT_RUN)
F_B_SumVersionNbr

Link Data Container:
Parameters/Value: P_URL_EVENTS_EXT = F_URL_EVENTSEXT_HISTORY
