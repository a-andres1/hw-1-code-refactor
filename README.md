# hw-1-code-refactor
Code refactoring work

My original idea was to go through and change all the divs to semantic tags and then tackle the css. I didn't like that. Too many things were broken too quickly for me to understand how to put them back. I systematically went through and edited the divs by section. 

The classes gave us a pretty good starting place to figure out how to change the divs to semantic tags. The classes with the same css were duplicated, so as I changed the semantic tags, I also deleted unnecessary css. 

I considered changing class 'float-left' and 'float-right' but after what we talked about in class/what I read reguarding keeping classes to use for later styling for other elements I decided against changing them. 

The id's for the main section were necessary as I couldn't figure out a better way to get the links in the nav to work without ids. 

I did change the class seo in Horiseon to an id since that felt like a very specific instance. 

It was suggested on mdn that we use something easily searchable that doesn't appear in our code to desonate sections. I used || as that isn't something that appears in my css. I did also straight up take it from the mdn page that suggested it. 
