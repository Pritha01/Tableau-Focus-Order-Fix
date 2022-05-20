# Tableau Dashboard Focus Order Fix

Tableau dashboards need to follow accessibility guidelines. Fixing the 'Tab' focus order is one of the main challenges that most Tableau developers face while ensuring that the focus order is set in the desired left to right, top to bottom format. However, most of the time the focus order moves in the order in which the elements were added on Tableau dashboards creating a need to manually fix the issue as described here: https://community.tableau.com/s/question/0D54T00000C6USYSA3/how-can-i-set-the-focus-order-of-the-views-and-objects-in-a-dashboard.

This code will help you to update the zone tag ids automatically without having to use manual effort. Thanks to Kelly Gupton for sharing the 'Dashboard Focus Order.twb' using which I have been able to test the code.
