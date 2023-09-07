# Event Registration Solution
This documentation shows how I built a solution in this case an app to be used to register, check-in people at events.I also built this solution on video if you want to follow along that way. https://youtu.be/cAMX7oftwL0

Apps aren't built for the fun of it rather they come about as solutions to problems. It is in this way that my critical thinking approach to development works.
I will walkthrough the business problem we sent out form so people can regsiter online for our event and to check them in on day of the event.We also need to be able to register people coming in on that day as New registrations.
Having defined the business scenario I will now take us through the solution development.

## Business Problem
We want to have an event soon and so we make a form for people to register so we know people to plan for.
When they get there want to check them in, give them food tags.
Opportunity to register afresh at the venue should also be available.

## Solution
Build an App that can be used for Event registration such that we can register new users at the venue and also check in people who signed in online.

## Build

So, 3 screens in our app  Landing screen,existing registration screen and new registration screen


### Landing screen
This screen has name of our event as well as buttons to clickthrough to new registration,existing registration pages.
![image](https://github.com/artemis1511/-Event-Registration-App/assets/107225504/1604d9a3-245e-499e-b179-4349dbdf6721)

### Existing registration screen
This page would be for people who had registered online so we can view them,search for people to check them in.

![image](https://github.com/artemis1511/-Event-Registration-App/assets/107225504/5736b615-6e95-4f1f-8380-ef8bb3e444b0)

![image](https://github.com/artemis1511/-Event-Registration-App/assets/107225504/d0414460-6ee4-4a8b-b0a4-8c7cdaaed9a4)
I used the search function on the gallery but we can see theres a warning attached to it which is that the function wouldnt work for more than 500 items but since we are only admitting 500 participants we can use it.In any case the filter function which I've commented out can do the job equally as well.I just chose to use the search function since we're only admitting 500 participants.

### New registration screen
On this page insert a form and connect it to a SharePoint List which serves as our database where data filled in by our participants from our form resides.

![image](https://github.com/artemis1511/-Event-Registration-App/assets/107225504/080a2dfa-6050-4628-9da3-b523361b2385)
