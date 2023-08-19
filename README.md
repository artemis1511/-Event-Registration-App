# -Event-Registration-App
This documents how I built an app to be used to register , check-in people at events.

Apps aren't built for the fun of it rather they come about as Solutions to problems. It is in this way that my critical thinking approach to development works.
I will walkthrough the business problem we sent out form so people can regsiter online for our event and to check them in on day of the event.We also need to be able to register people coming in on that day as New registrations.
Having defined the business scenario I will now take us through the solution development.

## Business Problem
We want to have an event soon and so we make a form for people to register so we know people to plan for.
When they get there want to check them in, give them food tag
Opportunity to register afresh at the venue should also be available.

## Solution
Build an App that can be used for Event registration such that we can register new users at the venue and also check in people who signed in online.

## Build

So, 3 screens in our app
Landing page
Existing registration 
New registration


On Landing page just have name of our event

Existing registration  page would be for people who had registered online so we can view them,search for people to check them in.

New registration
On this page insert a form and connect it to a SharePoint List which serves as our database where data filled in by our participants from our form resides.
