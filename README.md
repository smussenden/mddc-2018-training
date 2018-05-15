# mddc-2018-training

In this training session, I'm going to walk you through using two free, open-source storytelling tools from [Knight Lab](https://knightlab.northwestern.edu/projects/), [Soundcite.js](https://soundcite.knightlab.com/) -- a tool for embedding audio in-line in text stories -- and [Juxtapose.js](https://juxtapose.knightlab.com/) -- a tool for comparing changes in photographs.

You may already be familiar with another Knight Lab tool,  [Timeline.js](http://timeline.knightlab.com/), an interactive timeline tool.

## Juxtapose.js

Juxtapose uses a slider to compare two photographs (or animated GIFs), typically showing visual change over time.

Here are some great examples of how news organizations have used the tools. As you review them, consider why these are examples of effective storytelling?


* ESPN: [Comparing young and old Floyd Mayweather](http://www.espn.com/espn/feature/story/_/id/12748163/floyd-mayweather-prepares-2-fight-seal-legacy)
* Chicago Tribune: [Tornado damage](http://www.chicagotribune.com/chi-tornado-damage-washington-illinois-infographic-20141112-htmlstory.html)    
* Boston Globe: [New Half Dollar](http://www.bostonglobe.com/metro/2014/10/23/returning-jackie-kennedy-vision/t7TCSfcdkjcQNBBkdbuvEO/story.html)


### Trying out Juxtapose

For today's lesson, we're going to build a simpler version of a graphic that accompanied this story, about the [reconstruction of an island in the Chesapeake Bay over a period of 15 years](http://cnsmaryland.org/2015/02/12/maryland-island-once-diminished-reconstructed-with-dredged-material/), Poplar Island.

When you're finished, it should [look like this](http://cnsmaryland.org/interactives/spring-2018/mddc/juxtapose/index.html).

#### What you'll need

You'll need the links to the before and after photographs, which I've hosted at the following URLs:

* Before: [https://raw.githubusercontent.com/smussenden/mddc-2018-training/master/juxtapose/1998.jpg](https://raw.githubusercontent.com/smussenden/mddc-2018-training/master/juxtapose/1998.jpg)
* After: [https://raw.githubusercontent.com/smussenden/mddc-2018-training/master/juxtapose/2012.jpg](https://raw.githubusercontent.com/smussenden/mddc-2018-training/master/juxtapose/2012.jpg)

*Note: when making your own, you'll need to make friends with someone at your internship who has server access, and can host them for you at a dedicated URL.  Bring them donuts, maybe?*

You'll also need the text to label each photograph:

* Before: Poplar Island 1998
* After: Poplar Island 2012

And the source credit for each photograph:

* Before: Google Earth
* Before: Google Earth

Headline for embedding: `<h1>POPLAR ISLAND REGROWS in the BAY</h1>`

Subhead for embedding: `<h4>By 1998, the Chesapeake Bay's Poplar Island had dwindled to several pieces of fewer than 10 total acres -- from over 1,100 acres in the mid-1800s. Later that year, construction started to rebuild the island using clean dredged material from the Maryland Bay Channels, which allow ships to access the Port of Baltimore. Now the island has been restored to nearly 1,100 acres and plans have been approved to expand the island another 575 acres.</h4>`

#### Let's make a Juxtapose

**Step 1:** Visit [juxtapose.knightlab.com](https://juxtapose.knightlab.com)

**Step 2:** Click the green "Make a Juxtapose" button.

**Step 3:** Fill out the form with the image URLs, text and credit information. Hit the preview button.

**Step 4:** Make some changes to the options, and hit preview to see the changes.

**Step 5:** When you're finished, hit publish and copy the embed code iframe.  

**Step 6:** If you were at your internship, you'd paste this code into your CMS.  To replicate that process today, open a text editor (Atom or Sublime text), paste in the code, and the headline and subhead below. Save the file as index.html and then open that file in Google Chrome.  To get it to show up properly, you may need to change the height of the iframe to 800px.  

#### Future use

* What else could you imagine using this tool for?
* What would you need to do to gather material?   

## Soundcite.js

Soundcite is a cool tool that allows you to seamlessly blend audio clips with text in an unobtrusive way.  It's a great way to use sound to:

* Allow readers to hear what a person being quoted in a story sounds like.
* To provide a sense of place.
* Share music and other things that cannot be effectively communicated with text alone.

Here are some great examples of news organizations using the tool.  As you listen, consider why these are examples of effective storytelling.

* Al Jazeera: [Treasured Island](http://projects.aljazeera.com/2014/tangier-island/)       
* The New York Times: [The Ballad of Geeshie and Elvie](https://www.nytimes.com/interactive/2014/04/13/magazine/blues.html)
* Macleans: [What Happened in Ottawa](http://www.macleans.ca/news/canada/interactive-timeline-what-happened-in-ottawa/)

### Trying out Soundcite

To show how easy it is to use the platform, we're going to embed a clip from Martin Luther King, Jr.'s notable ["I Have a Dream" speech in Washington on March 28, 1963](https://www.archives.gov/press/exhibits/mlk.html).

When you're finished, it should [look like this](http://cnsmaryland.org/interactives/spring-2018/mddc/soundcite/index.html).

#### What you'll need

An edited audio clip, which I've hosted at the following URL:
[https://raw.githubusercontent.com/smussenden/mddc-2018-training/master/soundcite/mlk-dream-content.mp3](https://raw.githubusercontent.com/smussenden/mddc-2018-training/master/soundcite/mlk-dream-content.mp3)

*Note: As with Juxtapose, when making your own, you'll need to make friends with someone at your internship who has server access, and can host them for you at a dedicated URL. It's also best to edit your clip in an audio editor first.*

The text of the clip:

"I have a dream, that my four little children will one day live in a nation where they will not be judged by the color of their skin but by the content of their character."

#### Let's make a Soundcite

**Step 1:** Visit [Soundcite.knightlab.com](https://Soundcite.knightlab.com)

**Step 2:** Click the green "Make a clip" button.

**Step 3:** Paste in the audio clip URL and hit the blue load button.

**Step 4:** Leave the "start time" and "end time" and "plays" fields the same.

**Step 5:** In the link text block, paste in the text of the clip from above. Then click the blue "Create clip" button.

**Step 6:** To replicate the process of embedding a clip in your news organization's CMS, open a blank HTML document in a text editor and save it as index.html. Paste in the embed code.  

**Step 7:** Go back to the Soundcite page. Find the embed codes for the required JavaScript file and the required CSS file. In your HTML document, at the top of the page, above your embed code, paste in the links. Then open that index.html file in a browser.     

#### Future use

* What else could you imagine using this tool for?
* What would you need to do to gather material?   
