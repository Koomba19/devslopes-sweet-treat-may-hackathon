# Dev Notes
While the repo was made earlier, I never really gave this any time. It's currently 6/2. The hackathon is due in less than 31 hours from the time of writing. I finally entered a period of time where I can, responsiblity free, take all the time in the world to work on this. Might as well also try out this polyphasic sleep pattern I heard about. Apparently humans can go off of catnaps for a week or two at a time. Thomas Edison was reported to do this, so that's a stamp of approval if I've ever heard one.  

## Big Steps  

- [x] Layout - Done 6:09 PM
- [x] Setting up Header - Done 8:20 PM
- [ ] Setting up Footer
- [ ] Laying out the aside
- [ ] Making the Cash Register
- [ ] Making the Flavor Stand
- [ ] Create the Flavor Cards
- [ ] Make the Price Sheet
- [ ] Rig up logic to position Price Sheet
- [ ] Make the Easel Pictures
- [ ] Link the logic
- [ ] Build Guy
- [ ] Final Color and Happiness Touchup
- [ ] Build a readme

## Extra Steps  
To be made as they come up  

## Plan  
So grid the first 9 tiles. 
- Top row, Header 
- Bottom row, Footer
-  Center row: Cash Register, Flavor, Easel.  
I'm thinking of trying to make it so that you can only pick one flavor and one kind of cone at a time, utilizing radio buttons on two input forms.  
The footer will have a pretty picture under the flavor column, and a shoutout or something for under the register. A stylized price thingamajig will exist on the flavor counter.  
Upon thinking longer on it, and messing with the grid. I'm thinking I should probably instead rename the grids, and leave out the semantic footer html tag.  

## Ongoing notes  
I tried using Adobe illustrator to make the svg, then discovered that it is pay to play. Not for me. Then I tried out some free software I saw online, drawsvg.com or something. I was thinking, wow this is worse than ms paint. Then I realized, I should just use ms paint. So I did, made the header using that. And then I Converted it from png to svg using, you guessed it, pngtosvg.com. free software is so nifty. Thank you everyone that makes free stuff.  
Had a lot of hard times with actually inserting the darn SVG. I eventually stumbled upon object-fill. I was also under the impression that svg images stretched without issue. And while I'm right, I didn't realize that the viewBox needed a preserveAspectRatio value of none, which wasn't how I downloaded it. I injected that myself, and now it works great. I just wish it didn't look like AI made it, but that's the rub when it comes to svg converters. It most likely was an AI on the server side.

## Random Thoughts  
Layout in vscode is fun. Right now I have left third as these dev notes, right two-thirds/upper half the html, and right two-thirds/ bottom half css. I'm digging it.  
We all lift together - Keith Power has no need to go that hard.