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
