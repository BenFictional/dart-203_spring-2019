You're probably familiar with the idea of multi-page websites from a lifetime browsing the web, but it's important to plan out the content of your site efficiently, and avoid having too many pages. Make sure that the content is laid out in a logical way, so users don't have any trouble finding information.

Here's a sample hierarchy of pages:

* About
* Store
  * Shirts
  * Pants
  * Shoes
    * Boots
    * Sneakers
* Contact
* Support
  * FAQ
  * Contact

The design of children pages could be identical or unique. In this example, the children pages below "Store" would probably look identical expect for **metadata **like the item's name, cost, description, and an image. However the children pages below Support might look different... "FAQ" would probably have a big list of questions that users can click on, while "Contact" would have some sort of web form that users could fill out. 

Visual design should help a user locate where they are in a design; each page should feel different, and yet maintain a clear relationship to the website identity. 

With a Content Management System \(CMS\) like Wordpress, you can just design a single page for "Store items" and let Wordpress dynamically fill in the metadata. Webflow can do this too, which you can learn about on the Advanced Webflow page below.

Some navigation menus also show children pages in a submenu when you hover over the relevant parent page. This helps users go directly to the page they want without having to load interstitial pages, but it can be unwieldy if you have a lot of pages.

![](/assets/lesson-5/nightmare-submenu-400.gif)

This hilariously bad **flyout **submenu has some glitchy behavior, but the sheer number of pages is overwhelming and certainly doesn't make it easy for Pennsylvania residents to file their taxes.

### Navigation Menus

Some quick thoughts on navigation menus, which we haven't talked about much yet, because we've focused on one-page websites. "Nav" menus are pretty self-explanatory, but you'll have to make a few decisions as you imagine your site layouts:

**Horizontal or vertical?**

* Most sites arrange navigation links in a horizontal row at the top of the page, but you will also see sites stack the links in a vertical column, usually located on the left side of the screen.
* Vertical nav menus make it easier to add more links in the future
* Most people scan websites from top to bottom, and are less likely to look at side navigation menus.
* Here's an interesting article from [Smashing Magazine](https://www.gitbook.com/book/psu-arts-arch/dart-203/edit#) on the debate, that argues for horizontal menus but still identifies some effective uses of vertical menus.

![](/assets/lesson-5/menu-comparison.jpg)

**Static or fixed?**

* The default behavior of any HTML element is to sit in the document flow and allow the user to scroll up and down \(or left and right\).
* Elements like nav menus can be "fixed" in place, so they remain visible as the user scrolls through the page.
* This is accomplished with the CSS property
  `position: fixed;`

**Top or bottom?**

* Almost all sites put their nav menus at the top, for the reason mentioned above, that people scan websites from top to bottom.
* Some sites put the menu at the bottom for a unique effect. This forces users to look at your content before they even consider going to another page.

**Mobile behavior?**

* Unless a site only has a few top level pages, the nav menu will need to adapt to fit on smaller screens.
* The typical solution is to use an icon \(three horizontal lines a.k.a. a "hamburger"\) to show/hide the nav menu.
* Here are some [alternative methods](https://www.gitbook.com/book/psu-arts-arch/dart-203/edit#) for mobile nav menus, and some reasons to [consider hamburger alternatives](https://www.gitbook.com/book/psu-arts-arch/dart-203/edit#)
  .

![](/assets/lesson-5/giphy-downsized.gif)

