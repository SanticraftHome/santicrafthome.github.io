# Project Notes

Local website build would reset the changes of _site due to it being ingored. _site is only used to build the website and not to make changes.

* changes in layout/_masthead.scss. 
  * background positioning
* _pages.scss modifications:
  * a (markdwon text and privacy policy), .text-primary(service buttons)
* _masthead.scss modification:
* commented out code:
  * team.html
  * timeline.html
* added homes_background.png
* Modified contact section: class="section-subheading" style="color: darkblue;">{{ site.data.sitetext[site.locale].contact.text | markdownify }}
* Modified navbar header for mobile screens.