Hello stranger, my name is Evgeniya and here is my cv

## YAUHENIYA HABRYKAVA                                 
> Evgeniya Gabrikova

### Contact                                                 
**Direct line**                                                 
Belarus +37529-2418353                                          
**Whatsapp, Telegram**                                          
+37529-2418353                                                  
**Email**
gabriellji@yahoo.com or gabrielljihk@yahoo.com

### Personal Details

**Nationality**
> Belarus

**City of Residence**
> Minsk, Belarus

**Date of Birth**
> 24 January 1991

**Marital Status**
> Single

### Skills
HTML, HTML5, CSS, CSS3, Entry level of JavaScript, jQuery, 
Entry level of AngularJS, Photoshop, Entry level of Git

### Latest Code Examples
```javascript
   function lpHeader() {
            if ($(window).scrollTop() == 0) {
                $('header').addClass('top');
            } else {
                $('header.top').removeClass('top');
            }
        }
        lpHeader();
        $(window).on('load scroll', lpHeader);
        let lpNav = $('header ul');
        lpNav.find('li a').on('click', function (e) {
            let trgtSelector = $(this).attr('href');
            linkTrgt = $(trgtSelector);
            if (linkTrgt.length > 0) {
                e.preventDefault();
                let offset = linkTrgt.offset().top,
                    correction = linkTrgt.attr('data-offset') || 40;
                $('body, html').animate({
                    scrollTop: offset - correction
                }, 750);
            }
        });

```  
```javascript
  $("#arrow-down").on("click", "a", function (event) {
            event.preventDefault();
            let id = $(this).attr('href'),
                top = $('#portfolio').offset().top;
            $('body,html').animate({
                scrollTop: top
            }, 750);
        });

```
```javascript
   function lpSetNavActive() {
            let curItem = '';
            $('body > section').each(function () {
                if ($(window).scrollTop() > $(this).offset().top - 50) {
                    curItem = $(this).attr('id');
                }
            });

            let noActiveItem = lpNav.find('li.active').length == 0,
                newActiveRequired = lpNav.find('li.active a').attr('href') != '#' + curItem;
            if (noActiveItem || newActiveRequired) {
                lpNav.find('li.active').removeClass('active');
                lpNav.find('li a[href="#' + curItem + '"]').parent().addClass('active');
                $('.header').removeClass('color-undefined color-slideshow color-portfolio color-about color-travel color-pricing');
                $('.header').addClass('color-' + curItem);
            }
        }
        lpSetNavActive();
        $(window).on('load scroll', lpSetNavActive);
```
### Summary
My **end goal of this course** is to learn skills and gain confidence in programming, and to eventually open my own IT company in a technology-focused environment such as Hong Kong or Singapore. My **short term goal** is to be able to create websites with **out-of-the-box creative ideas** that give users a **unique user-experience**. I want to be able to show that **programming is also an art**, and that **coding is also a form of self-expression** for artists and creative-minded people. 

As an individual that has always been on the arts and creative side, **I have always been interested in creative ways that we experience the digital world**. But I always thought it was impossible, that coding was only a career for mathematics and science focused people. However, after taking an introduction course in 2019, I soon found new skills that allowed me to express myself through digital platforms such as my website, giving me new motivation. It is satisfying to have total control of my photography website, and being able to customize every detail to perfection.

### Experience
[My First Project](https://gabriellji.firebaseapp.com/)

### Education
**BelHard Academy**/The basics of Web Application Development
> October 2019

**IT Academy**/Computer Science
> November 2019

**BelHard Academy**/Front-End Software Developer
> December 2019

**MGEI University**/Psychology

### English Level
I have formal **English training in high school and at MGEI University**, and completed  **intermediate level of English course**. I also believe that my passion for travel and fast learning ability has allowed me to increase my level in writing and speaking English. I lived and worked in Hong Kong for a year, and it was a job requirement to speak in English. In addition, I also have a passion for languages, and I am currently learning **Mandarin** to give me a better career position for the future.
