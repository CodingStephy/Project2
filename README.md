Project Links
https://github.com/CodingStephy/Project2
https://project2-git-master-codingstephy.vercel.app/
Project Description
For this project, I plan to make a multiple-choice trivia game. I will use React's Link and Source to provide access to instructions, the game itself, and a leaderboard. The questions and possible answers will be populated using an API call. The leaderboard will be stored on a Google Sheet and also viewed through an API call.

API
https://cdn.contentful.com//spaces/nbe8tmkxy59u/environments/master/entries?access_token=ynfiaMt1N5Skp8U-uq7Z49Xc9OSl6g-je6-cEcapCqU&content_type=exhibition

{
        "exhibition": "Adornment: Jewelry of South Asia’s Nomadic Cultures",
        "date": "2019-11-02",
        "endDate": "2021-10-05",
        "exhibitionImage": 
        "exhibitionLink":
},
Wireframes
https://res.cloudinary.com/dt5zbnwvr/image/upload/v1627657840/M523ba0d9c3b3a47da438f1599d2883d21627612747104_jpflw4.png
Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Also, define the the React components and the architectural design of your app.

wireframes
https://res.cloudinary.com/dt5zbnwvr/image/upload/v1627660005/Me2d4dc0f8d0814a74b1c5ec44bce0ee41627659888551_jlzdts.png
MVP/PostMVP - 5min
The functionality will then be divided into two separate lists: MPV and PostMVP. Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.

MVP 
Fully functional, interactive, exhibitions lists
populate the exhibition information by API call
Add favorites to the exhibitions 
Create a fav exhibitions list 
Navbar with options that link to the to-go page 
Options that filters the exhibition 
Button  that filters the exhibition according to dates 
Instructions page
PostMVP 
Carousel that displays the exhibitions
Videos and Location 

Components
Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.
Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components.

Component	Description
App	Sets up app with React Router
Header	Renders the header, including the nav
Footer	Renders the footer
Main	Contains Switch/Routes for content
Exhibitions	Renders the list of exhibitions, including Onclicks to add the exhibitions to my list 
AExhibition	Renders a single exhibition via API call 
MyList 	Renders the list received through props

Time frames are also key in the development cycle. You have limited time to code all phases of the game. Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe. Also, put a gif at the top of your Readme before you pitch, and you'll get a panda prize.

Unless otherwise noted, time is listed in hours:

Component	Priority	Estimated Time	Time Invetsted	Actual Time
Create React app and files for all components	H  1  
Basic Navbar & Footer	H	1	
Set up basic React routing	H	1	
Make exhibitions API call, parse important data	H	1   
Display Lists of Exhibition using Card	H	5
Add love button to Exhibition Sections H   2
Add the Exhibition to My List	H	1	
Delete the Exhibition from My List	H	1	
Display the My List Page    H   3
My List Buttons to filter   H	2	
re-organize Exhibition by Date 	H	2
Incorporate the date sort   M   4
Additional styling for main (to mimic the actual wesbite)	L	4
Additional styling for Navbar, Footer	L	3
Total	H	32
Additional Libraries
Bootstrap 

Code Snippet
Use this section to include a brief code snippet of functionality that you are proud of and a brief description. Code snippet should not be greater than 10 lines of code.

The below code is how the leaderboard is populated. The shorter the name, the more dots are added between the name and score. The font size is set progressively smaller for each entry.
