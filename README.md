# Altavista Well-being Centre
Altavista Well-being Centre is a holistic health and mindful living place. It is committed to enhancing mental, emotional, and physical well-being. Altavista offers peaceful retreat support groups, inviting individuals to group Pilates classes. The users are offered free audio samples written on the website to invite to the transformative journey of self-discovery. There is also an option to check the schedule for current classes. If the user subscribes to the email program, he is offered 2 free Pilates classes, which is an advantage for the user. And in such way, the centre can attract new customers. The website is suitable for adult people who are searching for inner peace and care about their well-being.

# FEATURES
## Landing page
Altavista Well-being Center Landing Page Overview:
The landing page is creating a positive first impression to the user. The landing page shows that Altavista offers mindfulness programs, Pilates training, and other well-being offerings. Clear and concise text ensures that users can quickly understand the site's scope and relevance. The prominent feature of the landing page is a photograph that serves a dual purpose. Firstly, it visually showcases the essence of Altavista, giving users a glimpse of connection to happy restful life like a flower. Secondly, the image incorporates text overlay, providing the name of the centre.
Landing page image
![Landing page](readmeimages/pic1.jpg)

## Navigation through the website

The navigation of the Alta Vista Well-being Centre website is designed to provide users with easy access to different sections and information.
![Landing page](readmeimages/pic2.jpg)
The "Home" link is the first option in the navigation bar, likely serving as a way to return to the main or introductory section of the website. This next navigation section Pilates provides information about Pilates training offered at Altavista. Users can learn about the unique experience provided at the well-being centre and get familiar with current schedule.
![Landing page](readmeimages/pic3.jpg)
![Landing page](readmeimages/pic4.jpg)
Mindfulness Programs section of navigation bar brings the user to the appropriate section of the main page which focuses on Mindfulness Awareness Programs offered in the centre, emphasizing the importance of finding inner peace in today's fast world. Users can join one of programs by email to cultivate mindfulness and reduce stress.
![Landing page](readmeimages/pic5.jpg)
The Altavista audio link directs users to a separate page ("audio.html") where they can access free daily audio resources aimed at promoting mindfulness and relaxation. The content includes audio practices like "Calm of Cosmos", "Dreamlike tranquility" etc.
![Landing page](readmeimages/pic6.jpg)
![Landing page](readmeimages/pic7.jpg)
The Subscribe section bring the user to specific section on index page and encourages users to subscribe to Alta Vista's Free Mindful Awareness Email Program. By subscribing, users can receive two free Pilates lessons in the studio. The subscription form includes fields for the user's first name, last name, email, and phone number which makes the process easy to follow.
![Landing page](readmeimages/pic8.jpg)
“Reviews” section provides feedbacks from different customers, so it engages new users to attend Altavista Mindful Centre.
![Landing page](readmeimages/pic9.jpg)
The "Contact Us" navigation section provides the link to the information placed on the Home page on how users can physically visit Alta Vista Well-being Centre. It includes the address details, inviting individuals to start their transformative soul journey at the centre.
![Landing page](readmeimages/pic10.jpg)
The header shows the name of the centre. Firstly the colour I chose was pink which had bad visibility, so I had to change it to purple.
About us section

# Features left to implement

The Submit form needs to congratulate the user after pressing SUBMIT button and present details entered, so JavaScript should be involved.

# Testing
Responsiveness of website on different sizes of gadgets was checked with the help of Google Website Responsiveness Checker extension:
<https://sites.google.com/view/website-responsiveness-checker>
#### Resolution 496*600
![Landing page](readmeimages/pic11.jpg)
![Landing page](readmeimages/pic12.jpg)
####Resolution 800*600
![Landing page](readmeimages/pic13.jpg)
![Landing page](readmeimages/pic14.jpg)
![Landing page](readmeimages/pic15.jpg)
####Resolution 1024*600 for tablet
![Landing page](readmeimages/pic16.jpg)
![Landing page](readmeimages/pic17.jpg)
![Landing page](readmeimages/pic18.jpg)
####Resolution for iPad mini
![Landing page](readmeimages/pic19.jpg)
![Landing page](readmeimages/pic20.jpg)
####Resolution for Laptop
![Landing page](readmeimages/pic21.jpg)
![Landing page](readmeimages/pic22.jpg)
# Validator Testing
####W3C validator
Index.html
![Landing page](readmeimages/pic41.jpg)
Audio.html
![Landing page](readmeimages/pic42.jpg)
Schedule.html
![Landing page](readmeimages/pic43.jpg)
####CSS Validator
![Landing page](readmeimages/pic44.jpg)
####Form checking
The form asks for input if nothing is provided by user.
![Landing page](readmeimages/pic45.jpg)
####Lighthouse
The website was also checked with Lighthouse
![Landing page](readmeimages/pic46.jpg)

# Bugs faced

Code anywhere website would be down for a while during critical moments, which would slow down the progress.
![Landing page](readmeimages/pic23.jpg)
![Landing page](readmeimages/pic24.jpg)
There was pink color of welcoming text, but it was needed to search for alternative color for better readability.
![Landing page](readmeimages/pic25.jpg)
The main issue was with footer which has fixed position and would cover Contact us block.
![Landing page](readmeimages/pic26.jpg)
The issue was solved by adding padding-bottom in main section according to article:

Payne, S. (2023, 04 21). Resolving the Issue of Content Overlapping Footer. Retrieved from Copyprogramming: <https://copyprogramming.com/howto/how-to-fix-a-footer-overlapping-content?utm_content=cmp-true>

After fixing the bug:
![Landing page](readmeimages/pic27.jpg)
During final checks index.html and audio.html pages look fine
![Landing page](readmeimages/pic28.jpg)
![Landing page](readmeimages/pic29.jpg)

But issue with footer persisted with schedule.html page
Half of schedule was covered by footer
![Landing page](readmeimages/pic30.jpg)

It appeared the page was missing main tag. Bug was fixed successfully.
![Landing page](readmeimages/pic31.jpg)

There was congratulation message visible if no data was entered by user
![Landing page](readmeimages/pic32.jpg)
So I needed to use display: none by default.

The media queries had problem for reviews part on index.html page for tablet view
![Landing page](readmeimages/pic33.jpg)
I fixed it by adjusting media queries
![Landing page](readmeimages/pic34.jpg)

During last commits css stopped working
![Landing page](readmeimages/pic35.jpg)
Fixed this bug by adjusting root to css because it was changed during last commit.
#Fixing mistakes pointed out by potential users
From the potential users I have got feedback that index page is overwhelmed with “Subscribe now” links, so I have to remove and leave just 2.
![Landing page](readmeimages/pic36.jpg)
Also it was tested that h2 tag had bad readability on audio.html page
![Landing page](readmeimages/pic37.jpg)
So I had to change it to background footer colour:
![Landing page](readmeimages/pic38.jpg)
The navigation was after the top banner so it was not visible at once to users:
![Landing page](readmeimages/pic39.jpg)
I had to place it on top of the page for better visibility and access.

# Unfixed Bugs

After pressing Subscripe on form it brings the user to Not Allowed page
![Landing page](readmeimages/pic40.jpg)

# Deployment

Altavista Well-being centre project was deployed to a hosting platform GitHub through main branch.
•	The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here
<https://oksana0020.github.io/altavista/>
# Credits
### Payne, S. (2023, 04 21). Resolving the Issue of Content Overlapping Footer. Retrieved from Copyprogramming: <https://copyprogramming.com/howto/how-to-fix-a-footer-overlapping-content?utm_content=cmp-true>
### Google Website Responsiveness Checker extension:
<https://sites.google.com/view/website-responsiveness-checker>
### W3 validator:
<https://validator.w3.org/#validate_by_input>
### CSS jigsaw validator:
<https://jigsaw.w3.org/css-validator/#validate_by_input>
###<https://github.com/Code-Institute-Solutions/readme-template>

### Map and Social Media links are taken from Coders Coffeehouse example
<https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRR101+2021_T1/courseware/9645be8635124d76b35692f1f1f6b753/2c4f82a9ef174830aa83ff2cf10f4bc7/?child=first->
### Revising usage of different properties at
<https://www.w3schools.com/>
### All pictures and audios are taken from
<https://pixabay.com/>
