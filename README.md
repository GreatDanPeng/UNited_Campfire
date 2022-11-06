# UNited_Campfire
UNited Campfire, an all-round campus forum for students at UNC-Chapel Hill.


## Inspiration
As we were browsing through emails from unc, Instagram, reddit and heel life, I wondered if there could be a platform that could bring all of them together. In my opinion, each information network is like a campfire where people congregate around to chat and exchange ideas. If many campfires could gather together, it would be even more exciting! The information gap that is detrimental to many students will also disappear... Thus, we designed **UNited Campfire**.

## What it does
**UNited Campfire** has several functions.

###Homepage
1. **Banner**: The user can view recent sports news, art performances, student store discounts, other interesting but niche events, etc...
2. **Recommended Topics**: Show different topics based on campus hotness.

###Sidebar
3. **Search**: Search for topics or keywords you want to know about (Designed). 
4. **Profile**: Show personal information and recent posts. 
5. **Post**: You can type in what you want to share and upload local files.
6. **Notifications**: Remind the update of favorite topics.
7. **Favorites**: Favorite topics of interest.

## How we built it
We primarily coded this project by using the common web development languages, html5, css3 and JavaScript. The webpage layouts were designed and made with CSS and HTML and the Sidebar animation and link connections were created with JavaScript. Learning to use HTML's <meta> and <inframe> was our greatest gain, though we also learned a lot about creating and calling functions in JS! When most of the content on a page is the same, such as the header and bottom of a page, we can use the <iframe> tag to embed the duplicate parts into the page. This effectively reduces code redundancy. We finally combined our code and linked them together on GitHub.

## Challenges we ran into
Since half of us has almost no coding experience in web design and development, it’s really tough for us to design the layouts and functions…And we even thought of giving up this project and turning to another one, built in our familiar languages. However, our inspiration brought us back and prompted us to stay focused on specific challenges. In these 25 hours (no typo, winter time gave us an extra hour lol), we encountered three huge challenges: messy page layouts, partial online pages, and non-activated buttons. 

Due to our initial failure to understand the relationship between Margin, Border and Padding in CSS, all the page layouts were not centered and were all crammed on the left. Later, by adjusting these parameters, we made the page more beautiful.

For some of the pages that already exist (like the Kenan-Flagler Datathon site), we thought that carrying them to UNited Campfire would also be a very effective way to share information. In fact, it was a bit tricky. Unfortunately, it was very slow to update the pages and the layouts were weird. Then we asked the mentor and learned how to use the <meta> and <inframe>. This was very useful in fixing this bug that had been bothering us for a long time.

We planned to hide the link to other html files behind the “More” buttons. Unfortunately, for <button> with multiple response animations, we were not able to add rhef inside. Later, we figured out that we could build functions in script.js and call them in the <button>, thus avoiding some “misunderstandings” between the code.

## Accomplishments that we're proud of
As beginners in web design, we are very proud to have completed such a meaningful demo and appreciate HackNC for giving us this opportunity to network and learn. We hardly learn anything about web development in our current freshman computing courses. We are also glad to make such a pretty page, hopefully it will attract several students to click on it (if we can build the backend)!

## What we learned
In the REACT workshop, we learned how to build a calculator! It was very cool! Although we didn't get to use react in our project, it's definitely going to be in our future ones! In addition to improving our coding skills, we also learned how to stay focused on multiple tasks (many features need to be implemented in a short amount of time!) and effective communication in teamwork.

## What's next for UNited Campfire
We will continue to update more front-end modules and try to add domains and databases. Have **UNited Campfire** REALLY work in UNC!
