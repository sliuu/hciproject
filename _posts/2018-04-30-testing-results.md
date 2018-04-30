---
title: Testing Results and Revisions
excerpt: ""
---

## Heuristic Evaluations
The heuristic evaluations demonstrated the following major problems and consequent revisions:

## 1. Unclear initial search page
### Before:
We received feedback that a primary function of our application, which allows the user to scan a QR code using the mobile phone’s camera, was not clear. The camera icon was too close to the search bar, and the camera did not provide any indication that it would be used to scan QR codes. This issue violates the visibility of system heuristic, and received a severity rating of 3.

<figure>
<img src="../assets/images/paper-prototype-search.jpg" alt="cam" style="max-width: 50%;"/>
<figcaption>Search menu</figcaption>
</figure>

### After:  
To clarify the two search options and provide more context on functionality, we labelled and separated the two components in a large button menu.
<figure>
<img src="../assets/images/pp-cam-1.jpg" alt="cam" style="max-width: 50%;"/>
<figcaption>Two separated components with clear labeling</figcaption>
</figure>

## 2. Missing back button(s)
### Before:
Our evaluators pointed out that after navigating to inspiration, it was unclear how to get back to the main about section. They felt stuck. This violated the User Control and Freedom heuristic, and received a severity rating of 1.
<figure>
<img src="../assets/images/paper-prototype-inspo.jpg" alt="cam" style="max-width: 50%;"/>
<figcaption>Inspiration section of "Learn more" </figcaption>
</figure>

### After:
Revision: A back button was added.
<figure>
<img src="../assets/images/pp-about-inspo.jpg" alt="cam" style="max-width: 50%;"/>
<figcaption>Back button added</figcaption>
</figure>

## 3. Unnecessary screen components
### Before: 
Always having the bottom toolbar felt redundant to evaluators in certain contexts. This added clutter and made the design difficult to navigate. This violated the Aesthetics and Minimalist Design heuristic, and received a severity rating of 2.
<figure>
<img src="../assets/images/paper-prototype-cam.jpg" alt="About" style="max-width: 50%;"/>
<figcaption>Camera screen</figcaption>
</figure>
<figure>
<img src="../assets/images/paper-prototype-discuss.jpg" alt="Learn More" style="max-width: 50%;"/>
<figcaption>Discussion screen</figcaption>
</figure>

### After:
Revision: The design should only provide information that is needed and is helpful to the user. We decided to drop the bottom bar wherever it was easy for the user to still go back one page and find the bottom bar easily should they need it.
<figure>
<img src="../assets/images/pp-cam-2.jpg" alt="About" style="max-width: 50%;"/>
<figcaption>Camera screen removes toolbar</figcaption>
</figure>
<figure>
<img src="../assets/images/pp-discuss.jpg" alt="Learn More" style="max-width: 50%;"/>
<figcaption>Discussion screen removes toolbar</figcaption>
</figure>

## Usability Testing Results
We encountered the following critical incidents from our usability tests, broken down by each usability test in order:

## Results from Test 1
## 1. Re-organizing the “About More” and “Learn More” content
### Before:  
While trying to navigate to a page that contained the inspiration for an artwork, we realized that it wasn’t clear to a general user whether the inspiration information should be under “about” or “learn more.” This led us to believe we may want to put more information about the inspiration and context under the “about” tab, and leave very in-depth understanding to the “learn more” section (e.g. further information about the artist and the history of the movement).
<figure>
<img src="../assets/images/paper-prototype-about.jpg" alt="About" style="max-width: 50%;"/>
<figcaption>About screen under artwork profile</figcaption>
</figure>
<figure>
<img src="../assets/images/paper-prototype-learnmore.jpg" alt="Learn More" style="max-width: 50%;"/>
<figcaption>Learn More screen under artwork profile</figcaption>
</figure>

### After:
Revision: The “About” page was modified to contain information that used to be in the “Learn More” section, and the “Learn More” section was modified to be a series of very in-depth information.
<figure>
<img src="../assets/images/pp-about.jpg" alt="cam" style="max-width: 50%;"/>
<figcaption>New About Page</figcaption>
</figure>

<figure>
<img src="../assets/images/pp-learn-more.jpg" alt="cam" style="max-width: 50%;\
"/>
<figcaption>New Learn More Page</figcaption>
</figure>

## 2. QR code scanner
### Before:
While trying to “fake” taking a scan of the QR code, our user noted that he didn’t really know where to put the QR code, and that it would be nice to have a box on the camera screen so the user knows exactly where to put it.
<figure>
<img src="../assets/images/paper-prototype-qrscan.jpg" alt="QR Scanner" style="max-width: 50%;"/>
<figcaption>QR Scanner</figcaption>
</figure>

### After:
Revision: Adding a box/grid layout to indicate where the QR code should be captured.
<figure>
<img src="../assets/images/pp-cam-2.jpg" alt="About" style="max-width: 50%;"/>
<figcaption>QR code screen indicates placementr</figcaption>
</figure>

## 3. Discussion
<figure>
<img src="../assets/images/paper-prototype-discussion-1.jpg" alt="Discussion" style="max-width: 100%;"/>
<figcaption>Discussion</figcaption>
</figure>

### Incident:
This was a positive incident; our user was quickly and easily able to locate the “discussion” section and understand the gist of the interface and how it would operate. This is likely because discussions like this exist in similar formats on other platforms. 

## Results from Test 2
## 1. Favoriting artworks
### Before:
Favoriting and adding artworks to the user’s profile was not readily apparent. Although participant 2 was able to discover this feature after exploring the application and browsing his user profile, the discovery was only in hindsight after he had already left the artwork profile screen. Because favoriting artworks is one of our six primary tasks and the main feature of the user profile, this feature needed to be made more obvious.
<figure>
<img src="../assets/images/favorite_old.jpg" alt="Old Favorite" style="max-width: 50%;"/>
<figcaption>Old favorite button</figcaption>
</figure>

### After:
Revision:  Our solution was to change the favorite button into a more visible button right underneath the work’s title. We also added some more explicit text to make this functionality even more obvious.
<figure>
<img src="../assets/images/favorite_new.jpg" alt="New Favorite" style="max-width: 50%;"/>
<figcaption>New favorite button</figcaption>
</figure>

## 2. QR Code Search Tutorial
### Before:
Both participants two and three did not understand the capability to scan QR codes, which was another negative incident. However, once this feature of being able to scan the QR codes displayed on artwork placards was explained to them, both preferred to use this over the text search.
<figure>
<img src="../assets/images/tutorial_old.jpg" alt="Old Tutorial" style="max-width: 50%;"/>
<figcaption>Old initial search screen</figcaption>
</figure>

### After:
Revision: To solve this problem of not effectively communicating the ability to use QR codes to look up artworks, upon launching the “Search” mode for the first time, a one-time tutorial overlay page outlines the QR code look-up process for the user.
<figure>
<img src="../assets/images/tutorial_new.jpg" alt="New Tutorial" style="max-width: 50%;"/>
<figcaption>New initial search screen</figcaption>
</figure>

## Results from Test 3
## 1. Confusing syntax
### Before:
Some of the syntax employed resulted in negative incidents, as they did not successfully translate their ascribed functionality. In particular, on the search page, participant 3 didn’t understand the difference between being in the “Search” mode and the button option to “Search.” Additionally, she did not recognize that the “Threads” section of the User Profile would display the threads she participated in.
<figure>
<img src="../assets/images/search_old.jpg" alt="Old Search" style="max-width: 50%;"/>
<figcaption>Old search syntax</figcaption>
</figure>

<figure>
<img src="../assets/images/threads_old.jpg" alt="Old Thread" style="max-width: 50%;"/>
<figcaption>Old thread syntax</figcaption>
</figure>


### After:
Revision: Words were changed to better suit the user’s vocabulary and increase the usability of these key interactions. We changed the text for searching by text to “Text Search” instead of just “Search,” and changed the “Threads” tab to say “Your Threads”.
<figure>
<img src="../assets/images/search_new.jpg" alt="New Search" style="max-width: 50%;"/>
<figcaption>New search syntax</figcaption>
</figure>

<figure>
<img src="../assets/images/threads_new.jpg" alt="New Thread" style="max-width: 50%;"/>
<figcaption>New thread syntax</figcaption>
</figure>

## 2. Launch screen
### Before:
Upon opening the application and being shown the initial screen for the “Search mode,” the user went to the “Museum Profile” for the purposes of initially exploring the application. This incident was negative, as the order of interaction was not intuitive to our test users. 

### After:
Revision: A launch screen was added to be an initial museum profile screen. It communicates that the app is museum-specific and clearly defines what the purpose of the "museum" tab is. The museum profile orients the user toward accomplishing the task of searching for individual art pieces.
<figure>
<img src="../assets/images/ppf_homepage.jpg" alt="homepage" style="max-width: 50%;"/>
<figcaption>Launch screen</figcaption>
</figure>

## Summary & Key Revisions

One of the key revisions we made was the search functionality. First, we added in clear and large buttons to delineate the difference between the text search and the QR search. Then we added more explicit text so that the users could distinguish between the kinds of search and understand why they were different. Lastly, we added in a one-time tutorial of how the QR search functionality would work. All of these changes helped make the search function much clearer and improve the usability. Since searching for the artwork to pull up its artwork profile is a key functionality of our design, this was very important to us to change. Another key revision was changing how the "About" and "Learn More" pages were divided, and we found that after the first usability test, we needed to make this distinction more intuitive. We decided to modify what kinds of information would be located under each tab. We noticed in our second and third usability tests, this distinction was a lot more clear to our users, and they had no problem finding what they needed with this modification. Thus, we found this change to be incredibly important for our design and usability. Obviously, since finding background information is a key task we are trying to support, making it as easy as possible for the user to find the background information they are explicitly looking for is important to us. Lastly, adding the launch page to be the museum profile was a key revision for us, because it helps orient the user and helps her understand what the other tabs are for. We didn't realize that the "Museum Profile" tab might be confusing to the user if they are not brought their first, so this was another key revision. It helps the user build a correct "mental model" of how the app works.

