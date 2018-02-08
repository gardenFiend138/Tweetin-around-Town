# What's the Word in San Jose?

## Motivations
### [__Code for San Jose__](http://www.codeforsanjose.com/)

> 'Code for San José is a volunteer organization made up of makers,    > designers, developers, activists, and subject matter experts who come 
> together to use tech to solve civic problems.'

This project was conceptualized by the founder, Michelle Thong, with the ['SonicRunway'](https://www.mercurynews.com/2017/11/04/sonic-runway-brightens-san-jose-city-hall-plaza/) at City Hall in mind. We thought it would be interesting to see what residents and visitors were tweeting about while visiting this public art installation. 

## Overview 

This project will consist of three main parts: 

1. A heatmap of Tweets laid over a map of San Jose.

2. A data visualization of hashtags by frequency, represented by bubbles, with their size being dependent on how many times that particular hashtag has been used. The hashtag will be visible in the center of the bubble.

3. A live feed of Tweets within San Jose, which will be tied to both of the data visualizations, so they change in real time to match what's being talked about in San Jose.

### Wireframe 

![Wireframe for Twitter San Jose](https://github.com/gardenFiend138/Tweetin-around-Town/blob/master/wireframes/twitter_sj.png)

## Technologies Used 

This project will use Rails on the backend, utilize web sockets to connect to the Twitter API, Google Maps API for the map of San Jose and the heatmap, and D3.js for the secondary data visualization of trending Tweets. The backend will be written in Ruby, and the frontend will be written in JavaScript, with the help of the D3 library. 

* [Rails](http://guides.rubyonrails.org/)
  * may not need a whole rails backend--look into what would be most lightweight
* [Web Sockets in Ruby](https://ruby-doc.org/stdlib-1.9.3/libdoc/socket/rdoc/Socket.html)
* [Twitter API](https://developer.twitter.com/en/docs)
* [Google Maps API](https://developers.google.com/maps/)
* [D3.js](https://github.com/d3/d3/wiki)
* [Ruby](http://ruby-doc.org/)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## Highlights 
This will be updated as the project goes on.

## Action Items 
- [x] Add links to technologies used 
- [ ] Research Twitter and Google Maps APIs
- [x] Design Wireframes
- [ ] Get backend started