=== Plugin Name ===
Contributors: anibalwainstein
Donate link: http://www.effectmaker.com/buyit.html
Tags: announcement, reel, scroll, scroller, Text scroll, effect, effects, extension, javascript, easy insertion, no programming, free scrolling, jquery, ticker, slide shows, slides, widget, images, image, content, embed, flash, gallery, media, photo, photos, picture, pictures, slider, slideshow, posts, show, skins, wordpress slider, themes, responsive, responsive slider, java applets, presentation
Requires at least: 3.9.1
Tested up to: 4.3.1
Stable tag: 1.2.1
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Extend Wordpress with this JavaScript web effect creation system.

== Description ==

The Effect Maker allows you to customize JavaScript effects like scrollers, slide shows and messengers with your own texts, fonts and images. No JavaScript development skills are needed. With a few clicks you can start creating your own effects. You can have several customizations of one type of effect in your site. All standard web fonts are supported and if you like you can specify your own custom font if you support it by your HTML/CSS3 setup or template. To see the effects in action [look at our gallery](http://www.effectmaker.com/effectgallery/). Get the [Pro edition](http://www.effectmaker.com/buyit.html) for even more effects.

The following effects are included:

- [Rotating Gallery](http://www.effectmaker.com/effectgallery/rotatinggallery/) - rotate your images around in a carousel giving them a real 3D feeling
- [Image Scroller](http://www.effectmaker.com/effectgallery/imagescroller/) - Scroll a selection of images vertically or horizontally
- [Horizontal Scroller](http://www.effectmaker.com/effectgallery/horizontalscroller/) - a ticker effect with side fading
- [Vertical Scroller](http://www.effectmaker.com/effectgallery/verticalscroller/) - a vertical ticker effect width side fading
- [Image Fader](http://www.effectmaker.com/effectgallery/imagefader/) - a simple slide show that fades images into each other
- [Text Fader](http://www.effectmaker.com/effectgallery/textfader/) - a messenger where texts are fading into each other
- [Scramble Message](http://www.effectmaker.com/effectgallery/scramblemessage/) - Your message is hurrying to scramble in and out
- [Falling Text](http://www.effectmaker.com/effectgallery/fallingtext/) - Your message is falling down!
- [Water Drop Show](http://www.effectmaker.com/effectgallery/waterdropshow/) - Let drops of water fall on your slides with one big splash showing the next.
- [Shuffle Show](http://www.effectmaker.com/effectgallery/shuffleshow/) - Shuffle your slides like a card deck with this effect

Effect Maker is integrated into Wordpress as a plugin. It inserts an option in the administration menu which you click to create your configurations. Configurations are saved in the wordpress database. Images and media are selected from the standard Wordpress media gallery.

Your effects can then easily be inserted into your posts by specifying the location in the editor and then clicking on "add effect" with the configuration that you made. An effect icon marks the location of your effect.

Multiple configurations effects are supported in a single wordpress site, thanks to the JavaScript instancing technology in Effect Maker.

Important Note! If you need to integrate the JavaScripts into your Wordpress themes or headers then we recommend using the desktop versions of Effect Maker which generates physical standalone .js files and which you can download [here] (http://www.effectmaker.com/download/).

Internet Explorer 9.0, Chrome, Opera and Firefox supported. Some effects may work on earlier versions of Internet Explorer down to version 8.0.

== Installation ==

1. Upload the plugin to wordpress
2. Activate it
3. You will see a new option "Effect Maker" in your dashboard left menu, click on it
4. Select any effect from the gallery
5. Click on the Help button to see the tutorial and to quickly get started

== Frequently Asked Questions ==

= Where can I get support? =

If you have any problems with the software, whether it is the basic or pro version or you just want to give feedback, don't hesitate to contact us at [Mandomartis support](http://www.mandomartis.com/contact.html). 

= I see strange behaviour when inserting the same configuration name into a page several times =

Only a single configuration name is supported per page. This happens because the function names and variables are named the same in the scripts, thus conflicting with each other. However as a workaround, you can open the configuration in Effect Maker, save it under another name and insert it together with the first configuration, even if you didn't do any changes.

= My images appear strange and too big for the effect =

Make sure that the images you upload are of roughly the same size like the effect area (width and height fields).

= My image based effect doesn't work =

Make sure that the images you have specified really exist in your upload folder or image gallery. Some effects (like Image Scroller) crashes if the images don't exist. This could happen if you delete images from your upload folder or image gallery and you have effects that depend on those images.

= How do I get more effects in my Effect Maker library? =

If you have the basic edition which is the free, upgrade to the [pro edition](http://www.mandomartis.com/products.html) which has many more effects!

= I have other questions! =

Click on the help button in Effect Maker and check the online FAQ. It will answer more questions than this readme file.

== Screenshots ==

1. The Effect Maker intergrated in the Dashboard
2. The font selector field
3. The list field used for effect with multiple items like slide shows and messengers
4. The gallery in horizontal mode
5. The configuration name field showing the Image Scroller
6. Three inserted Effect Maker effects in one page

== Changelog ==

= 1.2.1 =
* Tested and works for Wordpress version 4.3.1

= 1.2 =
* Added four new free effects: Water Drop Show, Scramble Message, Shuffle Show and Falling Text (now a total of 10 effects)
* Tested and works for Wordpress version 4.2.2

= 1.1.1 =
* Added the new effect Rotating Gallery (now a total of 6 effects)
* Bug when displaying too many effects in a category fixed and horizontal category bar is now displaying tooltips
* Bug in single file fields fixed which was causing empty values to be generated
* Added support for constant fields (not customizable by the user) which were needed for effects using support images
* Added feature to check for new images added into the media library every 15 seconds
* Centering bug in Image Fader fixed

= 1.0.3 =
* Tested and works for Wordpress version 4.1

= 1.0.2 =
* Site breaking bug fixed which could affected sites running earlier PHP versions.

= 1.0.1 =
* Reload button feature fixed.

= 1.0 =
* Initial version containing 5 effects in total

