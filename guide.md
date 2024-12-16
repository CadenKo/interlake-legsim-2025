# legsim guide

this guide explains how to set up a legsim chamber and the basic process of passing legislation. 

this assumes you have already have legsim running and have a system user account. see the [setup.md](setup.md) for more information.

## create a course

log in as a system user. go to "Courses" > "Create New Course". fill in the form and click "Create Course".

## create a chamber

on the course page, click "Create New Chamber". fill in the form and click "Create Chamber". you should now see the chamber on the course page.

## create a student user

copy the chamber's "Member Code" from the course page. go to the user sign in page at `/users/sign_in`. click "Create New Account" and fill in the form. Use the "Member Code" from earlier for the "Chamber Authorization Code" field.

the sign up button may not work so you may have to press enter inside a text field to submit the form.

if you get an error when signing up, you may have to manually confirm the user. in the system menu, go to the "Users" tab, click on the chamber, find the user, and click "Manage". there should be a button to "Manually Confirm User".

the student user should now be able to log in and do normal legislative stuff.

## create an administrator user

in order to actually progress legislation, you will need access to the leader's desk.

creating an administrator user is similar to creating a student user, except you will have to use the "Administrator Code" instead of the "Member Code" when creating an account.

once the administrator user is logged in, you can access the leader's desk under "Floor". Note that the leader's desk is also referred to as "Chamber Management" in some pages.

## create an executive user

executive users can access the white house, where they can sign/veto legislation. they are not strictly necessary for the simulation, since administrators can also sign/veto legislation (but not create governing priorities or a personal statement)

however, if you would like students to simulate this aspect of the legislative process, you can create an executive user by using an "Executive Code" instead of a "Member Code" when creating an account.

## make a student user the chamber leader

only administrators can access the leader's desk by default, but administrators can assign a student user to be the chamber leader, giving them access as well.

in a classroom setting, you may want students to nominate their chamber leader. they can do this by going to "Clerk" > "Chamber Leadership".

to actually assign a chamber leader, go to "Floor" > "Leader's Desk" > "Committee/Chamber Management". committee leaders can be assigned here as well, giving them the ability to manage individual committees.

## creating legislation

students can create and submit legislation by going to "Clerk" > "Submit Legislation". Once submitted, legislation will be visible in "Clerk" > "Browse Legislation".

## referring legislation to committee

the leader can refer legislation to committees by going to "Floor" > "Leader's Desk" > "Committee Referrals". Note that you have to actually click on the legislation name (it will be highlighted in blue) to select it.

## passing legislation through committee

either the chamber leader or a committee leader can do this step.

committee leaders can directly access their committee by "Committees" > "Committee on X". the chamber leader can access all committees from "Committees" > "Committees Directory" > "Committee on X"

once on the committee page, click "Manage Committee". the steps on this page detail how to pass legislation through the committee. 

click "Step 1: Open a hearing on the bill". you should see the legislation referred earlier under "Referrals". click "Open Hearing" to allowing students to discuss the legislation. 

"Step 2: Draft a committee report" links to the same referral management page as Step 1. you can click "Draft Report" to end the hearing and create a report for the committee. complete the form and click "Submit Draft Report".

next, click "Step 4: Schedule a vote to adopt the drafted committee report". this will bring you to the committee vote page. 

you can schedule a vote by clicking "Schedule Vote" and filling in the form. Make sure you select the right motion type, as only "Adopt Committee Report" votes will actually pass legislation out of committee.

scheduling votes does not actually run the vote, but you can use it as a reminder. the only way to complete a vote is to click "Enter Previous Vote" and record the results. Make sure to select the right motion type again. For the "Vote Recorded by:" field, "Voice Vote" is the easiest option, as it lets you directly record "Passed" or "Failed".

once a piece of legislation has passed a "Adopt Committee Report" vote, it is officially out of committee.

## putting legislation onto the calendar

make sure you have created a calendar for the chamber. go to "Leader's Desk" > "Manage Calendars" > "Create New Calendar". Fill in the form and click "Create Calendar".

on the "Manage Calendars" page, under "Legislation Awaiting Calendar Placement", you should see the legislation. check the box next to it and click "Add to Selected Calendar".

## floor votes

once legislation is on the calendar, floor votes can be scheduled. go to "Leader's Desk" > "Manage Floor Votes", and you should see options to both "Schedule Vote" and "Enter Previous Vote". this works the same as committee votes. make sure you select the right motion type, as only "Final Passage" votes will actually pass legislation.

## the white house

once legislation has passed the chamber, it must be signed by the executive to officially become law. this can be done on the "White House" page, which can be accessed by either executive users or administrators.

legislation that has passed the chamber should show up under "Enrolled Legislation", with buttons to either "Sign" or "Veto" the legislation.

