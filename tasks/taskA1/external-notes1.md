# EXTERNAL RSS FEED FOR IMAGE CAROUSELS:  

## Notes using digital.usfsp.edu as an example.

### 1. Using digital.usfsp.edu as an example, the following url is the location of the xml data that's needed to capture the information to be displayed remotely:

http://digital.usfsp.edu/events/slidefeed.rss

http://digital.usfsp.edu/slideshow/recent.rss

### 2. If you want to be able to display images as well as text from digital.usfsp.edu, you must use the link,

http://digital.usfsp.edu/slideshow/recent.rss

### 3. In the case of http://digital.usfsp.edu/slideshow/recent.rss, below is a sample block of the xml tags used to display the images in the rotating carousel.

```

<rss xmlns:atom="http://www.w3.org/2005/Atom" xmlns:media="http://search.yahoo.com/mrss/" version="2.0">
<channel>
<title>USFSP Library Events</title>
<atom:link href="http://digital.usfsp.edu/events/recent.rss" rel="self" type="application/rss+xml"/>
<copyright>
Copyright (c) 2017 University of South Florida St. Petersburg All rights reserved.
</copyright>
<link>http://digital.usfsp.edu/events</link>
<description>Recent documents in USFSP Library Events</description>
<language>en-us</language>
<lastBuildDate>Thu, 10 Aug 2017 13:57:18 PDT</lastBuildDate>
<ttl>3600</ttl>
<item>
<title>USFSP Library Hosts Guide Dogs-in-Training</title>
<link>http://digital.usfsp.edu/events/5</link>
<description>
<![CDATA[
<img src="http://digital.usfsp.edu/events/1004/preview.jpg"> <p>Keep an eye out around the library for Juno (4 months) and Conway (5 months) our on-site guide dogs-in-training. Valeria, a student worker and <a href="http://library.usfsp.edu/staff-member/stephanie-fuhr/" >Steph</a>, an Instructional Designer, and are both puppy raisers for the South-Eastern Guide Dogs organization.</p>
]]>
</description>
<pubDate>Thu, 10 Aug 2017 13:29:54 PDT</pubDate>
<guid>http://digital.usfsp.edu/events/5</guid>
<enclosure type="image/jpeg" url="http://digital.usfsp.edu/events/1004/fullsize.jpg" length="0"/>
<media:content url="http://digital.usfsp.edu/events/1004/fullsize.jpg" type="image/jpeg" medium="image"/>
<media:credit/>
<media:thumbnail url="http://digital.usfsp.edu/events/1004/fullsize.jpg"/>
<media:title type="plain">USFSP Library Hosts Guide Dogs-in-Training</media:title>
</item>
```
