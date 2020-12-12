# hw-1-code-refactor
Code refactoring work

[Deployed website](https://a-andres1.github.io/hw-1-code-refactor/) 
[Screenshot of Deployed website](.assets/images/horiseonpage.png)


The purpose of this assignment was get more familiar with refactoring. I really enjoyed the opportunity to learn more about organizing css. I find it highly interesting to see how css doesn't need to necessarily have to follow your html. In fact, based on how css works I suppose there are instances where that wouldn't make any sense. 

My original idea was to go through and change all the divs to semantic tags and then tackle the css. I didn't like that. Too many things were broken too quickly for me to feel like I would understand how to put them back. Instead, I systematically went through and edited the divs by section and then changed the cooresponding css. 

The classes that we started out with on the HTML gave us a pretty good starting place to figure out how to change the divs to semantic tags. The classes with the same css were duplicated, so as I changed the semantic tags, I also deleted unnecessary css. 

To be honest this css file was very overwhelming at first. I started with the footer. That only requied two semantic tag changes; from div to footer and then div to h4. Shoutout to John, Brandon, and Tyler for the assist with the heading tags. 

Once I had changed my footer from a div class="footer" to just a tag of footer, it was no longer center aligned. I might have deleted something in the css, but I control z-ed a lot without any headway, so it's unclear to me why that didn't work. Google didn't offer an explanation, but I did find a solution. I added a width of 100% and text-align: center and we were back in business. 

After that I dealt with the nav bar. This presented some intersting problems because there were a lot of classes floating around in the header, formerly div class="header", element that you really had to pick apart to figure out what went with whom. The links were all over the place for a little while, but I finally got the float in the correct place.

The main section was next. That was a mess. The divs - now sections - had classes and ids, so at first I deleted them both. Then I figured out the id's for the main sections were necessary to get the links in the nav to work. Perhpas there's a better way to make that work, but my Google searches were pretty fruitless in that department. I asked the group, but they were of the same opinion, we needed the ids.  

I considered changing class 'float-left' and 'float-right' on the sections in main, but after what we talked about in class/what I read reguarding keeping classes to use for later styling for other elements, I decided against changing them. 

I did change the class seo in Horiseon in the header to an id since that felt like a very specific instance. 

Next was the aside. As I mention in my HTML, I left the classes on aside so that I could override the main section css. 

At that point I felt that I had added as many semantic tags as I could and my page wasn't completely broken so I moved on to the css. 

Reminder that the entire time I was messing with the HTML, I was renaming/editing/deleting unnessecary css, so at this point it was really about figuring out how it was supposed to be structured. Our assignment said that our css should be structured "logically" without taking the sequence of the html into account. Which seemed weird at first but then I found a [great page](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Organizing) over at mdn that helped explain what that mean. 

It was suggested on mdn that we use something easily searchable that doesn't appear in our code to desonate sections. I used || as that isn't something that appears in my css. 

I feel good about the sections in the css that I've made and that they feel logical and easily searchable. This css page does feel very long to me, I''m still on the fence currently about whether or not it would be less annoying as two pages. For me I'd leave all the regular html tag styling on one page and split the classes/ids up onto another page. That feels like a rabbit hole I could easily fall down because then what is stopping me from making a "body styling" page? Nothing. 

I'm not going to do that though because I'm not convinced this length of css is worth the trouble of splitting up. It might be more annoying to need to constantly flit back and forth between windows. I'm sure more experience will help with these decisions. 
