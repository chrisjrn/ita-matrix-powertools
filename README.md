ita-matrix-powertools
=====================
Script for greasemonkey + ITA Matrix

Main discussion here:

http://www.flyertalk.com/forum/travel-tools/1623427-ita-purchase-fares-orbitz-delta-userscript.html

***** Notice: *****

!!! Double check your chosen flights before purchasing !!!

***** Posts you should read: *****

General statement regarding this script: http://www.flyertalk.com/forum/travel-tools/1623427-ita-purchase-fares-orbitz-delta-united-userscript-4.html#post24394534

How to fix class names yourself: http://www.flyertalk.com/forum/24807572-post119.html

Problems and limitations regarding pricing itins: http://www.flyertalk.com/forum/travel-tools/1623427-ita-purchase-fares-orbitz-delta-united-userscript-9.html#post24906119



***** Usage: *****

Either add the script into your preferred script manager or copy the the RAW-Text into your debug console.
Using debug console, you may use the shortened minified version.
(Note: there is no need to reexecute the script on pagechange unless you reloaded the page)

***** Files: *****

ita-matrix-powertools.user.js -- Main userscript, install into Greasemonkey/etc but also usable in debug console.

script_minified.txt --  Compact , pastable version of the script for pasting in the debug console.

*********** Latest major changes **************

**** Version 0.16 ****

2015-12-15 Edited by Steppo ( removed UA - Hipmunk,
                                use textNode for printing (external) messages)

2015-10-12 Edited by IAkH ( added wheretocredit.com calculator )

**** Version 0.15 ****

2015-09-30 Edited by IAkH ( added additional edition flyout menu,
                                added Ebookers, 
                                added Etraveli )

**** Version 0.14 ****

2015-09-25 Edited by Steppo ( added American Airlines )

**** Version 0.13 ****

2015-06-15 Edited by Steppo ( fixed miles/passenger/price extraction,
                                 moved itin-data to global var "currentItin" -> capability to modify/reuse itin,
                                 rearranged config section,
                                 introduced wheretocredit.com,
                                 introduced background resolving of detailed distances using farefreaks.com based on data of OurAirports.com,
                                 tested on FF38, IE11, IE10 (emulated)
                                 )

**** Version 0.12 ****

2015-06-13 Edited by IAkH ( added CheapOair )

**** Version 0.11 ****

2015-04-19 Edited by Steppo (added SeatGuru,
                                added Planefinder,
                                moved translation to external var/function adding capability to add translations,
                                added possibility to print notifications,
                                added self-test to prevent crashing on class-changes,
                                set timeout of resultpage to 10s,
                                added powerfull selector-function to get desired td in itin => see findItinTarget,
                                moved exit in frames to top,
                                some cleanups,
                                moved older changelogitems to seperate file on GitHub - no one wants to read such lame stuff :-) )
