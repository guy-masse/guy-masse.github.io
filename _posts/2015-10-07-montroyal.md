---
layout: page
title: Mont-Royal Novembre 2015
category: Randonnée
thumbnail: 2015-10-07-montroyal
---

<video id="my-video" class="video-js" controls preload="auto" width="640" height="420"  data-setup="{}">
    <source src="/img/video/montroyal_video1.webm" type='video/webm'>
    <p class="vjs-no-js">
        To view this video please enable JavaScript, and consider upgrading to a web browser that
        <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a>
    </p>
</video>
Au Chalet du Mont-Royal

<video id="my-video" class="video-js" controls preload="auto" width="640" height="420"  data-setup="{}">
    <source src="/img/video/montroyal_video2.webm" type='video/webm'>
    <p class="vjs-no-js">
        To view this video please enable JavaScript, and consider upgrading to a web browser that
        <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a>
    </p>
</video>
Écureuil

<div class="diy-slideshow">
    <figure class="show">
        <img src="/img/portfolio/2015-10-07-montroyal/DSC_0002_1.jpg" width="640" /><figcaption></figcaption> 
    </figure>
    <figure>
        <img src="/img/portfolio/2015-10-07-montroyal/DSC_0004_1.jpg" width="640" /><figcaption></figcaption> 
    </figure>
    <figure>
        <img src="/img/portfolio/2015-10-07-montroyal/DSC_0008_1.jpg" width="640" /><figcaption></figcaption> 
    </figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0010_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0012_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0013_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0015_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0016_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0018_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0019_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0022_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0023_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0028_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0030_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0035_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0036_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0037_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0042_1.jpg" width="640" /><figcaption></figcaption></figure>
    <figure><img src="/img/portfolio/2015-10-07-montroyal/DSC_0043_1.jpg" width="640" /><figcaption></figcaption></figure>
  <span class="prev">&laquo;</span>
  <span class="next">&raquo;</span>
</div>  

<script>
var counter = 0, // to keep track of current slide
    $items = $('.diy-slideshow figure'), // a collection of all of the slides, caching for performance
    numItems = $items.length; // total number of slides

// this function is what cycles the slides, showing the next or previous slide and hiding all the others
var showCurrent = function(){
    var itemToShow = Math.abs(counter%numItems);// uses remainder (aka modulo) operator to get the actual index of the element to show  

    $items.removeClass('show'); // remove .show from whichever element currently has it
    $items.eq(itemToShow).addClass('show');
};

// add click events to prev & next buttons 
$('.next').on('click', function(){
    counter++;
    showCurrent();
});
$('.prev').on('click', function(){
    counter--;
    showCurrent();
});

// if touch events are supported then add swipe interactions using TouchSwipe https://github.com/mattbryson/TouchSwipe-Jquery-Plugin
if('ontouchstart' in window){
    $('.diy-slideshow').swipe({
        swipeLeft:function() {
            counter++;
            showCurrent();
        },
        swipeRight:function() {
            counter--;
            showCurrent();
        }
    });
}

</script>
