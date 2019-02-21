# Technopedia-GSoC-2019
## Project Proposal for GSoC 2019

<b>"It has become appallingly obvious that our technology has exceeded our humanity."</b>

— Albert Einstein
## Introduction

Our society is now being reshaped by rapid advances in information technologies—computers, telecommunications networks, and other digital systems—that have vastly increased our capacity to know, achieve, and collaborate. These technologies allow us to transmit information quickly and widely, linking distant places and diverse areas of endeavor in productive new ways, and to create communities that just a decade ago were unimaginable.

But at times we,specially Tier 2 or Tier 3 college students and other beginners cannot keep a track of these events and opportunities because no such platform is available, often ending up getting information about them when the deadline have passed or when there is a short period left for the deadline to end thereby not having enough preparations. A combined platform like an android application would help everyone to dive better in the tech world.

## Idea

* Android Application that features all new opportunities, internships, scholarships, grants, open-source sessions, programming events, and ongoing research papers (more categories can be added) all at one place.
* A platform where people who carry some sort of familiarity in these domains can contribute by sharing their experiences and preparations they did and help newcomers in tech industry.
* A platform to eradicate the professor requirement condition for working on research papers at college level.

## Primary Features

* Category based segregation of events and opportunities
* Filtrations based on user preferences
* View saved events and app activities
* Reminder notifications
* Contribute module integration
* Browse profiles of users
* Crash reporting feature
* Analytics support to track app usage
* Attractive UI interface

## Secondary Features

* Users can select their areas of interests based upon which opportunities can be filtered for them.
* App guidance tour at first app launch.
* Theme Selection feature for UI enhancements.

## Implementation Strategy

The App would showcase various categories namely - Internships, Scholarships, Grants, Meetups, OSS,Programs, Research Papers.

There would be filtrations based on Location,Date(Past,Upcoming(This Month, This Week, Today)), Technology Based(Machine Learning, Web Development, Artificial Intelligence, etc ….), Gender Based( Specially in grants ).

User can view events and Like, Share to peers , Bookmark them. All Bookmarked events by the user would be displayed in a separate tab.

Reminder Notifications for the Bookmarked events on periodic basis ex. One month and one week before the deadline.

Disable Notifications and accessibility of the bookmarked feature is the deadline is gone. An additional option to permanently delete event from the bookmark tab or request pop-up for next year registrations of the event.

Ability for newcomers to connect with past scholarships, grants and other opportunities holders and people to contribute by sharing their experiences of the same.They can start by sharing their preparations, tips proposals etc.

People can contribute by adding new opportunities they know and want to share with their peers worldwide.Each contribution would be counted as a contribution to Systers Community.

Crash Reporting Feature - Users can send the cause of the app crash via mail to the organisation which then could work upon the issues.

People can showcase and put up their research papers and can get contributors and can form a team to work upon it.

Users can browse profiles of other users if their app to see their achievements, contributions and general profile.

## Tech Stack

### Backend

* APIs in Node.js 
* API Response in JSON Format
* Database - Realtime Firebase or MySQL
* Hosted on Heroku
* MVVM Architecture
* Notifications - Firebase Notifications
* Google Analytics - Firebase Analytics
* Crash Reports - Firebase Crashlytics

### Frontend

* Programming Language - Java
* Libraries - Glide , Retrofit , Dagger, BindView, RxJava
* Apis - Google maps API(for location filters)

## Data Flow Diagrams

[Conceptual Level](https://drive.google.com/open?id=1P_pqMnr5bdi6vV9O74DlbIAuwtr0nGUd)

[Level-1](https://drive.google.com/open?id=1pXsTwwire8emFBpSb4ce4X-BjYsjY1U4)

[Level-2](https://drive.google.com/open?id=197gdQy8eeSOywR6mNggzgEGO2uIuS7Z4)

So i plan to propose this project for GSoC 2019. Looking forward for feedbacks and suggestions.

#Thankyou!!

