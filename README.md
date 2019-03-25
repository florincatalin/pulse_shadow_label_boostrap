# pulse_shadow_label_boostrap
Pulse Shadow Label for Typesetter CMS (Boostratp 3)

„The <blink> tag is a non-standard element used to create an enclosed text, which flashes slowly. Blinking effect is used very rarely, as it is quite annoying for users to watch a piece of text constantly turning on and off. (...) The <blink> tag is obsolete. Though some browsers may still support it, it is in the process of being dropped. Do not use this element, otherwise your pages may be broken.“ [https://www.w3docs.com/learn-html/html-blink-tag.html]

„World Wide Web Consortium (W3C) guidelines on flashing on websites
The W3C was created in October 1994 to develop protocols and guidelines that ensure long-term growth for the Web. The Web Content Accessibility Guidelines 2.0 were published in 2008 in an effort to improve the accessibility of the web for disabled people.
In connection with photosensitive epilepsy, as part of good practice, it recommends that web pages do not:

    Contain anything that flashes more than three times in any one second period or
    Flash below the general flash and red flash thresholds
    
In addition, they suggest:
    Reducing contrast for any flashing content
    Avoiding fully saturated reds for any flashing content
    Reducing the number of flashes even if they do not violate thresholds
    Providing a mechanism to suppress any flashing content before it begins
    Slowing down live material to avoid rapid flashes (as in flashbulbs)
    Freezing the image momentarily if three flashes within one second are detected
    Dropping the contrast ratio if three flashes within one second are detected
    Allowing users to set a custom flash rate limit

If the user is unable to control the flickering, blinking and moving (this includes stopping these effects from starting), then these effects should not be used.“
[https://www.w3.org/TR/2008/REC-WCAG20-20081211/#seizure]

To attain blinking effect you can use CSS3 animation property defined with @keyframes rule. An acceptable effect can be obtained by changing the shadow using CSS. 
Igor Shegolev [https://codepen.io/igorsheg/pen/MBpwGw] has a very interesting ideea. My code is a adaptation for using with bootstrap 3 labels in Typesetter CMS.
[https://www.typesettercms.com/]. Just add css style at the end of the text on page and the add class pulse to label. CSS animations work with IE11, Microsoft Edge 17+, Chrome 49+, Firefox 61+, Safari 11.1+, iOS Safari 10.3+, Chrome for Android 67+ and Samsung Internet 4+. Demo here: 

https://florincatalin.000webhostapp.com/demo_pulse_shadow_label
