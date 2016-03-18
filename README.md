# Anti Web Design Manifesto

Based on <span xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/" about="http://brandon.invergo.net/news/2013-03-10-Anti-web-design-Manifesto.html"><span property="dct:title">Anti-Web-Design Manifesto</span> by <a rel="cc:attributionURL" property="cc:attributionName" href="http://brandon.invergo.net">Brandon Invergo</a>, licensed <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a></span>.

## Introduction

The web is becoming a crappy place. It always kind of has been since designers first used HTML tables to display page layout. Recently, a war has broken out between content creators on content consumers, whose goals are growing ever more apart. The following points are meant as an overaching guide to keep online content sane.

### Completely Override-Able CSS

If your website cannot be viewed properly with a custom user CSS file, it is broken. Over-dependence on div tags to get the site to look exactly the way you want it is guaranteed to make it difficult to read for some of your visitors. Designers, it may come as a surprise to you, but not everyone loves your work. Many people use custom CSS files to force a style that is easy on their eyes. Yet, a surprising number of sites fail to render properly if their CSS is overridden. In my perfect world, no websites would provide CSS files; all styling would be done by the user. Of course, since most people do not use their own stylesheets, everyone would complain about how horrible all these plain black-and-white sites look. So at a minimum, your CSS should be minimal, such that overriding it causes little disruption to the flow of your site.

### No Client-Side Scripts

If your website cannot be viewed properly with Javascript disabled, it is broken. There is absolutely no reason that your website should run a script on the visitor's computer, especially if the user cannot view the full source somewhere. No one is to be trusted online, not even you. For a normal, text-displaying website, using scripts is completely unnecessary since you can just store the text in an HTML document. That's what HTML is for. If you are trying to make a web application, just stop. Build a native application. It's nicer for everyone.

### No Proprietary Plugins

If your website requires the installation of a proprietary plugin, it is broken. The endless stream of news about security holes found in proprietary plugins like Java and Flash should be an immediate hint to you that you shouldn't be using them. The fact that they're proprietary means that we cannot benefit from the careful eye of other developers who can spot such flaws. Not only that but support for such software is limited only to what the company that produces it chooses to support, potentially leaving many visitors out. It is not safe to assume that everyone who visits your site can even run such plugins, due to said lack of support or due to lack of computing resources (not everyone in the world can afford a fast computer).

### No Advertising

This is a touchy point but words will not be minced. Advertising is manipulative and obtrusive. Most people do not need to buy anything in particular at any given moment and they even less likely need to buy whatever is being advertised to them at that time. Further damning is that advertising is a common source of malicious content on the web, in the form of tracking cookies and cross-site scripting. Cramming advertising into your site in order to generate some kind of income is lazy at best. Some will argue that, since sites depend on advertising revenue to survive, then somehow blocking ads is immoral. It is simple: if your business model is simply to attach some "content" to advertising space, your business deserves to fail. Honestly, it will be no big loss to have such sites go out of business. The world does not need so many vapid link aggregating sites, press-release-rehashing review sites, or echo-chamber journalism sites. If you really must host advertisements, be respectful of your visitors. Host the ads on your own server; do not fetch them remotely. Do not use moving images, pop-ups, audio, video, "click-through" links, or anything else that serves to distract the visitor from what they actually came to your site to see.

### No Frames, Multi-Columns or Other Visual Clutter

If your main text is drowned out by the surrounding content, your site is broken. Trying to read an article when the text is crammed between navigation menus, advertisements, links to more articles, link-sharing widgets, blogrolls, and whatever other things you squeeze into your site to try to keep the visitors attention is an absolute pain. If your site were well-organized to begin with, none of these would be necessary. In fact, such layouts are absurd in that your site is competing with itself for the reader's attention! One single column of text is the most comfortable reading experience you can give your visitor. As for all that other junk, simply make your site well-organized enough for it to be easily discoverable without having to shove it in the visitor's face.

### No Non-Standard Fonts

If your website absolutely depends on a particular font, it is broken. Fonts are subtle, in that most people probably do not pay much attention to which one is in use. That said, some people are absolute fanatics about fonts. Most web browsers allow the user to force the usage of their favorite one. Normally this is not a problem. However, increasingly websites are starting to use custom fonts with special glyphs that serve as icons on the site, presumably for bandwidth reasons (see Github project pages, for example). This completely subverts the user's right to select his or her own, preferred font. As in the above case of CSS, never presume that you have a better idea of what your visitor wants to see. If they do have a better idea, then you should not thwart their ability to implement it for themselves.

### No Tracking

If your website leaks private information of your visitors to anyone, it is broken. This should go without question. You have no right to perform any behavioral metrics on your visitors. Their right to privacy should be paramount. Your revenue streams are irrelevant to them. Even more egregious is to allow third parties to do the tracking on your site and worse yet if it is done without any notification to the user. Nobody wants their every move tracked, be it in the web or in the real world. Respect your visitors' privacy and do not do any form of tracking. A word about cookies: unless you are providing a service that requires user log-in, you do not need to send them. Period.

### No Unnecessary Pagination

If your website cannot fit a normal-length article on one page, it is broken. Web browsers, unlike books, have this amazing ability to scroll. Unless you are presenting a genuinely long document, you should not need pagination (though, clearly for very long documents, some pagination is desirable to easily mark one's place). Nevertheless, these days many sites unnecessarily break relatively short articles into several pages. This is tightly coupled to advertising: the more pages the visitor has to visit to read the article, the more ads can be presented. With no advertising, as suggested above, this problem would disappear.

### No Abusive Account Requirements

Many websites require accounts these days, for example to participate in some social aspect like a forum or comments, or to accommodate paying subscriber fees. This is fine. What is not fine is how much information is often required to subscribe. Under very few circumstances do you actually need the visitor's email address. Real names and mailing addresses are likely only necessary for online payment, which should be held quite separately from normal user information. In any case, if a login is required, take the absolute minimum of necessary information, ideally only a login name and a password.

### No New Annoyances

The web is a swiftly changing thing and there is no way this paltry list can cover all the corner cases or future annoyances. Before you implement anything, know that we probably neither need it nor want it. Please spare us from having yet another thing to curse about. Remember, all we want to do is read what you have to say. Anything else is just in the way.
