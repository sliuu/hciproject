---
title: Usability Testing Review
excerpt: ""
---

## Usability Test #2
Our second usability test participant was Liam Bardong, who was also an interview subject during the contextual inquiry research. We chose Liam because he is familiar with the purpose of the app and its use case. We started the test by laying out a brief scenario of being in the museum and approaching a painting, for which he didn’t really understand. This test was conducted in Sawyer Library, a quiet space. Cliff conducted the test, and Joyce took notes.

## Usability Test #3
Our third usability test participant was Elizabeth Sullivan. We chose Elizabeth because she expressed interest in the app, as she does find herself not understanding some of the pieces she sees in art museums. She has taken a few art history courses and so is not unfamiliar with the subject matter. Because she did not know anything about the project, we prefaced the test by giving a same scenario explaining that the app was meant to learn more about art pieces. However, we chose not to communicate the specifics goals in order to compare how users interact with design without clearly defined goals. The test was also conducted in Sawyer. Joyce conducted the test, and Stephanie took notes.

## Revisions
## Favoriting
Favoriting and adding artworks to the user’s profile was not readily apparent. Although Liam was able to discover this feature after exploring the application and browsing his user profile, the discovery was only in hindsight after he had already left the artwork profile screen. This incident was negative. Because favoriting artworks is one of our six primary tasks and the main feature of the user profile, this feature needed to be made more obvious.
Severity: 4
<figure>
<img src="../assets/images/favorite_old.jpg" alt="Old Favorite" style="max-width: 50%;"/>
<figcaption>Old favorite button</figcaption>
</figure>
Our solution was to change the favorite button into a more visible “like” button right underneath the work’s title. The action of “favoriting” can be made even more obvious with an animation of a picture disappearing into the profile tab.
<figure>
<img src="../assets/images/favorite_new.jpg" alt="New Favorite" style="max-width: 50%;"/>
<figcaption>New favorite button</figcaption>
</figure>

## Museum Profile
Upon opening the application and being shown the initial screen for the “Search mode,” Elizabeth, like Liam, first went to the “Museum Profile” for the purposes of initially exploring the application. This incident was negative, as the order of interaction was not intuitive to our test users. Starting with this mode may be more ideal; it places the app within the user’s settings by communicating that the app is museum-specific and clearly defining what artwork is covered. Although not directly part of a primary task, the museum profile orients the user toward accomplishing the task of searching art pieces.
Severity: 4

## User Vocabulary
Some of the syntax employed resulted in negative incidents, as they did not successfully translate their ascribed functionality. In particular, at the search page, Elizabeth didn’t understand the difference between being in the “Search” mode and the button option to “Search.” Additionally, she did not recognize that the “Threads” section of the User Profile would display the threads she participated in. Changing these words to that which better suits the user’s vocabulary increases the usability of these key interactions. 
Severity: 1

<figure>
<img src="../assets/images/search_old.jpg" alt="Old Search" style="max-width: 50%;"/>
<figcaption>Old search syntax</figcaption>
</figure>

<figure>
<img src="../assets/images/search_new.jpg" alt="New Search" style="max-width: 50%;"/>
<figcaption>New search syntax</figcaption>
</figure>

<figure>
<img src="../assets/images/threads_old.jpg" alt="Old Thread" style="max-width: 50%;"/>
<figcaption>Old thread syntax</figcaption>
</figure>

<figure>
<img src="../assets/images/threads_new.jpg" alt="New Thread" style="max-width: 50%;"/>
<figcaption>New thread syntax</figcaption>
</figure>

## QR Code Search Tutorial
Both Liam and Elizabeth did not understand the capability to scan QR codes, which was another negative incident. However, once this feature of being able to scan the QR codes displayed on artwork placards was explained to them, both preferred to use this over the text search.
Severity: 2

<figure>
<img src="../assets/images/tutorial_old.jpg" alt="Old Tutorial" style="max-width: 50%;"/>
<figcaption>Old initial search screen</figcaption>
</figure>

To solve this problem of not allowing users to easily look up artworks, upon launching the “Search” mode for the first time, a tutorial overlay page outlines the QR code look-up process for the user.

<figure>
<img src="../assets/images/tutorial_new.jpg" alt="New Tutorial" style="max-width: 50%;"/>
<figcaption>New initial search screen</figcaption>
</figure>

## Overview of Revised Prototype
<figure>
<img src="../assets/images/overview-pic-updated.jpg" alt="Revised Overview" style="max-width: 100%;"/>
<figcaption>Revised paper prototype overview</figcaption>
</figure>

The application has three primary modes: the museum profile, search, and user profile. The yellow highlighted box indicates which mode the user is in. Initially opening the application brings the user to the Museum profile mode page, as shown below.
<figure>
<img src="../assets/images/ppf_homepage.jpg" alt="homepage" style="max-width: 50%;"/>
<figcaption>Launch screen</figcaption>
</figure>


## Task 1: Learn more context and background information to better understand the meaning behind artworks

From this page, users can start their search. Opening the Search mode for the first time prompts a tutorial, as shown in Screen 1.1.0, detailing how to look up an image using a QR code. In Screen 1.1.1, users can then choose between a text (Screens 1.2-1.3) or QR search (Screens 1.4-1.6). Both lead to a results page, in Screen 1.7, where the desired artwork can be chosen.

<figure>
<img src="../assets/images/ppf_search.pdf" alt="Revised Search" style="max-width: 100%;"/>
<figcaption>Revised search</figcaption>
</figure>

Clicking on the artwork opens a nested art profile page with “About,” “Learn More,” and “Discussion” tabs the user can toggle between to support the first task of discovering more context about artworks. The “About” tab contains drop-down menus of further background information, including “Context,” “Inspiration,” “Genre,” and “Related Works” that can be collapsed and expanded, as shown in Screen 2.2-2.3.

<figure>
<img src="../assets/images/ppf_art_profile_1.pdf" alt="Revised Art Profile" style="max-width: 100%;"/>
<figcaption>Art profile</figcaption>
</figure>

## Task 2: Discuss artwork with others in order to further engage with the pieces
<figure>
<img src="../assets/images/ppf_art_profile_2.pdf" alt="Revised Art Profile 2" style="max-width: 100%;"/>
<figcaption>Art profile (cont.)</figcaption>
</figure>

The “Discussion” tab (Screen 2.6) supports the task of discussing art with others. In this tab, users can post and reply to other users’ comments about this artwork, as shown in Screens 2.7-10.

<figure>
<img src="../assets/images/ppf_user_profile.pdf" alt="Revised User Profile" style="max-width: 100%;"/>
<figcaption>User profile</figcaption>
</figure>

Clicking on the User Profile mode displays the initial Screen 3.1. The user profile displays a header containing a user profile picture, name, and bio. The body of the page consist of “Favorites” and “Threads” tabs that are toggled between. The “Favorites” tab displays favorited artworks. Clicking on any of these artworks, in Screen 3.2, brings the user to a nested art profile page, in Screen 3.3. The “Threads” tab (Screen 3.5) displays a list of discussions the user has participated in and highlights those with unread replies. Clicking on any of these comments, in Screen 3.6, opens a nested discussion page, as shown in Screen 3.7.
