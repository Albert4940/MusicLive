MUSIC LIVE
Table of Contents
Overview
Product Spec
Wireframes
Schema
Overview
Description

MusicDemoDay is a Haitian music app on which underground artist from all over the country
 can contact us to upload their songs on the app via this Email: "musicdemoappday@gmail.com"

This app is made for underground artists who are recording good music (lyrics, sound), but unfortunately 
their music doesn't play in any radio station, in any party but only their family, friends and some people because they are unpopular artist.
so we create this app to help them share their music, so people listen to them, discover thier talents, their masterpiece.


### App Evaluation
- **Category:** Social Networking / Music
- **Mobile:** This app would be primarily developed for mobile but would perhaps be just as viable on a computer, such as tinder or other similar apps. Functionality wouldn’t be limited to mobile devices, however mobile version could potentially have more features.

Product Spec
1. User Stories (Required and Optional)
Required Must-have Stories
with this app User can 
- [X] log in 
- [X] Create new account 
- [X] Log out
- [X] view all uploaded songs
- [X] view his profile
- [X] Play audio in the background.
	Continues playing while the screen is off or the app is in the background

- [X] create  playlist.

- [X] Search and Discover music from the App.
…
Optional Nice-to-have Stories
- [ ] comment several times under a music.
- [ ] like or dislike a song.
- [ ] download music.
…
2. Screen Archetypes

Welcome 

It's like a splash screen, it will be displayed during 5 seconds


Login
[Accepting varying types of form input from user for basic login / signup 
Validation of form inputs for invalid data (i.e bad emails, duplicate emails)
Sending requests to server to authenticate or create new user accounts 
Integrating third-party connection SDKs (i.e Facebook SDK) 
Loading states during authentication or creation 

Sign Up
Input fields of various types to collect information 
Ability to validate fields for correctness before creation
Sending network request to create new valid content item 
Option to capture a photo or select from photo gallery 

Home 
Sending network requests to retrieve lists of content data to display 
Creating a list of items based on that source data including displaying text and media 
Endless scrolling which paginates as user consumes content 
Handling cases where the user wants to view more information on a piece of content 
Allowing the user to take primary actions on this content such as deleting or editing 
Optimizing the display of items such that scrolling the stream is smooth 

Search 
Sending network requests to retrieve lists of content data to display 
Creating a list of items based on that source data including displaying text and media 
Endless scrolling which paginates as user consumes content 
Handling cases where the user wants to view more information on a piece of content 
Allowing the user to take primary actions on this content such as deleting or editing 
Optimizing the display of items such that scrolling the stream is smooth 

Results
Sending network requests to retrieve lists of content data to display 
Creating a list of items based on that source data including displaying text and media 
Endless scrolling which paginates as user consumes content 
Handling cases where the user wants to view more information on a piece of content 
Allowing the user to take primary actions on this content such as deleting or editing 
Optimizing the display of items such that scrolling the stream is smooth 

PlayList 
Sending network requests to retrieve lists of content data to display 
Creating a list of items based on that source data including displaying text and media 
Endless scrolling which paginates as user consumes content 
Handling cases where the user wants to view more information on a piece of content 
Allowing the user to take primary actions on this content such as deleting or editing 
Optimizing the display of items such that scrolling the stream is smooth 

Artits songs details
Sending network request to retrieve additional details or media for the data item 
Action buttons that allow user to interact with the item 
Option for user to share the content out to other apps 
Scrollable text or media content to read about the item 

Play
Sending network request to retrieve additional details or media for the data item 
Action buttons that allow user to interact with the item 
Option for user to share the content out to other apps 
Scrollable text or media content to read about the item 

Profile
Grid or list of recent content items for user 
Images associated with the user's identity 
List of related users (followers, following)
Action items when on another user's account 


## 3. Navigation
**Tab Navigation** (Tab to Screen)

 * [Home]
 * [Search music]
 * [Playlist user]
 * [Setting]

**Flow Navigation** (Screen to Screen)

 * [Login]
   * [=>Home]
   
 * [Sign Up]
   * [=>Home]
 * [Search]
   * [=>Home]
 * [Playlist]
   * [=>Home]
 * [Setting]
   * [=>Home]
Wireframes
[Add picture of your hand sketched wireframes in this section]

[BONUS] Digital Wireframes & Mockups
This is the figma's link "https://www.figma.com/proto/sED6oJWXK3kuV1nof74XRq/Untitled?node-id=10%3A4&scaling=min-zoom"
[BONUS] Interactive Prototype
Schema
[This section will be completed in Unit 9]

Models
[Add table of models]
Networking
[Add list of network requests by screen ]
[Create basic snippets for each Parse network request]
[OPTIONAL: List endpoints if using existing API such as Yelp]
