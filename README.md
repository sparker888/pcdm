pcdm
======================================================================================================================

Parent/Child Data Modeling with Entities Part 2 - NO Code
Drupal Workshop, July 26, 2014. 10:00am – 5:00pm.

Trephub
907 E Strawbridge Ave, Suite 102
Melbourne, FL 32901
Phone: 321.420.1900
Email: trephub@trephub.com

Prerequisites:

Environment:
1.	 Drupal 7.28 core
2.	The following modules installed and enabled:
a.	Admin menu
b.	Auto entity label
c.	Ckeditor
d.	Ctools
e.	Date
f.	Entity
g.	Entity connect
h.	Entity reference
i.	Entity reference view widget (use the dev version 7.x-2.x-dev)
j.	Field group
k.	Module filter
l.	Pathauto
m.	Rules
n.	Token
o.	Views
p.	Views bulk operations
3.	Disabled modules:
a.	Overlay
b.	Toolbar
4.	PCDM sandbox site imported and functioning properly. 

Assumptions:

Required Knowledge:
1.	Comfortable creating/editing Drupal content types and fields.
2.	Comfortable creating/editing Drupal views.
3.	Willing to extend views knowledge by introducing relationships and contextual filters.
4.	Comfortable navigating the Drupal block system.
5.	Comfortable and willing to extend Drupal UI knowledge by following simple step based instructions.
6.	* Most Important: An open mind, well rested and a burning desire to be unique and innovative in how you model Drupal back ends.

General Agenda (subject to change):

Kickoff:
1.	Introductions
2.	Project definition and scope discussion.

Review of Part 1
1.	Documentation and the importance of following the blueprint explicitly.
2.	Getting acquainted with the documentation and thinking in documentation terms.
3.	Learning the Information Architecture by machine names.
4.	Understanding the need for Field Groups and assembling node add/edit UI’s.
5.	Inspecting existing content types, fields and field groups for understanding expansion tasks.

Prep the engine
1.	Verifying necessary modules are turned on and configured correctly.
2.	Verifying PathAuto defaults.
3.	Inspect the watchdog for potential issues.
4.	Verifying URL alias patterns.

Review the feature request write up
1.	Identify existing architecture and where requests fit in.
2.	Identify potential pitfalls and level of difficulty.
3.	Determine new module needs if necessary.
4.	Identity existing Views displays and how to accommodate new feature requests.

=======================================================================================================================

Parent Child Data Modeling with Entities Part 2 – NO Code

Feature Request(s), Changes and Addition(s) to existing data model:

1.	Create new front page.
2.	Create an Event Listings page.
3.	Remove the Tracks tab and have the sessions tab display records grouped by parent track.
4.	Add a bio content type so we can enhance the session display to show the session instructor info with a small portrait image, his/her full name and a link to see their full bio page.
5.	Enhance the Venue content type by adding room assignments. Example: A venue can have many rooms, but we only have access to B1 through B5 for an event. These rooms should display approx. square footage and maximum capacity. Add these values to the Session display.

Future Feature Request(s): Not in scope for Part 2 but worth discussion (if time allows)!
1.	Ability for users to register for sessions. Session registration should automatically conclude once a room capacity has been exhausted. Explicit site messages should be shown as well as a custom email to the user that their session registration cannot be met due to room capacity. 
2.	Add a waiting list function to closed sessions that have met capacity with workflow rules and capabilities.
