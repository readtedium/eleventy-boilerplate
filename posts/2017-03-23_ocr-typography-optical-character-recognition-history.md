---
uuid:             b1804020-ab5b-4ce5-85d3-78cca43a731c
layout:           post
title:            'Seek And Spell'
slug:             ocr-typography-optical-character-recognition-history
subtitle:         'Teaching computers to read was one of the 20th century''s great challenges. At first, the secret to optical character recognition was purpose-built type.'
date:             '2017-03-23 03:24:00'
updated:          '2017-06-04 21:59:14'
author:           'Ernie Smith'
author_slug:      ernie
header_img:       'http://tedium.imgix.net/2017/03/tedium032317.gif'
status:           published
language:         en_US
meta_title:       'OCR History: The Original Machine Learning'
meta_description: 'Teaching computers to read was one of the 20th century''s great challenges. At first, the secret to optical character recognition was purpose-built type.'
tags:
  - computer-history
  - typography
  - fonts
  - ocr
  - optical-character-recognition
  - ocr-a
  - ray-kurzweil
  - david-h-shepard
  - jacob-rabinow

---

[whitebox]

[big]**Today in Tedium:** We live in a world where facial recognition has become so sophisticated that we’re being forced to ask very serious ethical questions about it. (In the U.S., the depth of the FBI’s facial-recognition capabilities [are raising some serious questions](http://www.vocativ.com/413934/fbi-facial-recognition-program/) from Congress. In China, it’s being used [to detect toilet paper theft](http://www.chicagotribune.com/bluesky/technology/ct-facial-recognition-toilet-paper-theft-wp-bsi-20170321-story.html). To each country their own.) But I want to take a step back from the big hairy ethical questions and consider how we started on this road—with typography. Optical character recognition, or OCR, is a technology that came up with computing in general. In a lot of ways, it still feels like magic—even though it’s a problem we solved long ago. Today’s Tedium tells its story. *— Ernie @ Tedium*[/big]

[/whitebox][redbox]

[number]
### 1954
[/number]

**The year that** the first commercial optical character recognition machine was installed in a business—fittingly, [the office of Reader’s Digest](https://books.google.com/books?id=tuarbEnfF_0C&pg=PA501), though it wasn’t used for books. At the time, the big use of OCR was seen as automating business tasks, and in the case of Reader’s Digest, the technology [was used to manage subscriber sales data](https://books.google.com/books?id=-ZXJDQAAQBAJ&pg=PA13) and convert that data into a punch card format. At this early point, the technology only supported characters in a specific typeface.

[/redbox][whitebox]

![OCR-A at the Museum of Modern Art](http://tedium.imgix.net/2017/03/0323_ocra.jpg)

*The OCR-A typeface, shown at the Museum of Modern Art. ([Eric Fischer/Flickr](https://www.flickr.com/photos/walkingsf/6867057058/))*

### How the challenges of making fonts readable by machines influenced typography

American Type Founders, trust of 23 different type foundries that defined typography in the U.S. for decades, has a lot of fonts to its name, many of them incredibly well known and of high-quality. Franklin Gothic, Century Schoolbook? Both of them credited to ATF typographers. (We’ll overlook the fact that the foundry is responsible for [Hobo](https://hobosightings.wordpress.com/).)

But just one of its fonts has a spot in the Museum of Modern Art’s collection, [and that font is OCR-A](https://www.moma.org/collection/works/139567), a typeface created in 1966 to be read for a very specific audience: machines.

![OCR-A font specimen](http://tedium.imgix.net/2017/03/0323_ocra2.jpg)

And the machines of the time did not have the ability to differentiate between fonts, making such a font necessary. As the 1999 document [*Optical Character Recognition: An illustrated guide to the frontier*](https://pdfs.semanticscholar.org/bea5/75337bdd78f80af9ed687df8ce1d7d77cb0e.pdf) explains:  

> Many of the typefaces used today are derived from medieval calligraphy, only slightly modified by the limitations of early printing technologies (wood blocks and moveable type). To imitate fine penmanship, vertical strokes are thick compared to horizontal strokes, and NW-SE diagonals are thicker than NE-SW diagonals. Therefore curved strokes may vary in width according to their local orientation. In contrast, typefaces specifically designed for accurate OCR, such as OCR-A and OCR-B fonts, have uniform stroke widths and exaggerated distinctions between similar symbols such as Ο and 0 or 1 and l. 

OCR-A wasn’t the first font to tackle these machine-scanning issues, but it was a major step forward in that it was a complete alphabet that was readable by both machines and humans. Previously, the most well-known use for such technology involved something you’re probably familiar with if you’ve cashed a check sometime in the last 60 years: Magnetic Ink Character Recognition, or MICR.

![E-13B](http://tedium.imgix.net/2017/03/0323_MICR.jpg)

*An E-13B font specimen, as shown in a 1995 patent filing. ([Google Patents](https://www.google.com/patents/EP0651345A2?cl=en))*

Developed in the 1950s by the banking industry, the fonts—there are two, used exclusively of one another in different countries—are made up of the numbers 0-9 and a few specific codes that are designed to communicate specifically to computers. If you’re in North America or the U.K., you’ve likely seen E-13B, which relies on unique shapes for each individual character. If you’re in France, Spain, or South America, you might be more familiar with CMC-7 font, which integrates white dashes into the numbers. The ink is also magnetically charged to ensure scanners look for the numbers.

![](http://tedium.imgix.net/2017/03/0323_credit.jpg)

*A credit card, with its number displayed in the Farrington B typeface. You mean yours is, too? ([Ed Ivanushkin/Flickr](https://www.flickr.com/photos/barsen/3714941137/))*

Another notable font of this nature is Farrington B, a numeric typeface conceived [by early OCR developer David H. Shepard](http://www.nytimes.com/2007/12/11/us/11shepard.html) that’s still in use to this day on credit and debit cards everywhere.

(These fonts, side note, directly inspired other very blocky fonts, such as the one [used on the *Byte* magazine logo](https://fontsinuse.com/uses/7902/byte-magazine-covers-1976-84) , directly leading [thick rounded-stroke design](https://www.mercerdesign.com/true-story-westminster-font/) to be closely associated with early computing.)

OCR-A, which you might have seen on a piece of junk mail or two over the years, expanded on the basic idea of MICR by creating a character set that could be detected by either a computer or a set of eyes. The problem was, however, that it was a better fit for computers and had a strongly stylized design, which some found not so appealing.

“The result is a font that mixes serif with sans-serif characters, shifts its axes and internal symmetry arbitrarily, and is easy to recognize with its acute angularity,” University of Washington associate professor Zach Whalen [explained in an essay on the font](http://www.zachwhalen.net/posts/ocr-and-the-vestigial-aesthetics-of-machine-vision/). “In these ways, OCR-A is an ugly font, but of course that ugliness—a human consideration—makes it less ‘invisible’ than, say, Helvetica, in a way that links its technical function with its use in graphic design.”

That led to a second attempt to take on the problem by Swiss typographer Adrian Frutiger, released in 1968.

![OCR-B type specimen](http://tedium.imgix.net/2017/03/0323_ocrb.jpg)

*An OCR-B type specimen. ([Identifont](http://www.identifont.com/similar?SS))*

Frutiger was tasked to the problem by the European Computer Manufacturers’ Association (ECMA), which felt OCR-A wasn’t built for humans’ sake. In a piece [on the Linotype blog](https://www.linotype.com/793-12663/the-big-ocr-b-project.html), the late typographer, who died in 2015, recalled that he had somewhat of an advantage as OCR reader technology had improved significantly, and was able to pick up finer details. The result is that OCR-B looks far closer in design to a standard European font than OCR-A’s more stylized look ever did.

Not that it was easy—Frutiger notes that, for example, it was a challenge to ensure the “8” and “B” characters were read as unique characters.

The fruit of Frutiger’s work is what it was eventually picked up as a global standard by the International Standards Organization (ISO), while OCR-A had to settle for the American National Standards Institute’s standardization.

These fonts aren’t technically necessary anymore—starting in the 1970s, omni-font OCR solutions became common—but they’re still used pretty much everywhere.

[/whitebox][redbox]

[quote]
### “I happened to sit next to a blind gentleman on a plane flight, and he explained to me that the only real handicap that he experienced was his inability to read ordinary printed material. It was clear that his visual disability imparted no real handicap in either communicating or traveling. So I had found the problem we were searching for.”
[/quote]

**— Technologist Ray Kurzweil,** [describing the chance encounter](http://www.kurzweiltech.com/kcp.html) that gave a purpose the project that he was working on at the time. This led Kurzweil to build his company’s technology around this specific use case, the result becoming the Kurzweil Reading Machine. The device could scan a given page, parse the text on the page, and recite them to the person who wanted to read the page. It was a definite upgrade [from vinyl books](http://tedium.co/2016/02/18/audiobooks-blind-vinyl-history/), and it [helped generate excitement](http://www.nytimes.com/1976/06/14/archives/us-pressing-for-devices-to-help-blind-read-faster-us-urging-devices.html) about OCR technology in the mid 1970s.

[/redbox][graybox]

![Reading Edge](http://tedium.imgix.net/2017/03/0323_readingedge.jpg)

*The Kurzweil Reading Edge. (via the [American Federation for the Blind](http://www.afb.org/aw/aw040205.asp))*

### Five key points in the evolution of optical character recognition

1. **In 1952, onetime National Security Agency employee David H. Shepard** started a company called Intelligent Machines Research Corporation to help commercialize a product that could read. “We built it in my attic,” [he told the Associated Press in 1954](https://www.newspapers.com/clip/9771704/david_h_shepard_ocr_machine/).
2. **Also in the 1950s,** Jacob Rabinow, an employee of the National Institute of Standards and Technology, built a reading machine of his own, this one built on an approach called “best match,” which detected the letter by comparing it to every character in the alphabet and suggesting an answer. “It enabled us to read very poor printing that could not be read by any other means,” [Rabinow recalled](https://www.nist.gov/pao/postwar-years-highlights). It could only read one character a minute, but soon, it got much better.
3. **In 1965, the U.S. Postal Service,** which had (since 1957) been [using a sorting machine](http://nistdigitalarchives.contentdm.oclc.org/cdm/singleitem/collection/p16009coll42/id/112) built by Rabinow, [installed an OCR machine](https://about.usps.com/publications/pub100/pub100_042.htm) at the Detroit Post Office. The devices, according to [a 1970 Post Office video](https://www.youtube.com/watch?v=cdfYrpRHqJ0), are expected to read at a speed of 42,000 addresses per hour.
4. **In 1980, Ray Kurzweil** [sold his company Kurzweil Computer Products](http://www.afb.org/aw/aw040205.asp) to Xerox, which further developed his technology into something that proved valuable to the business world. The base company, later sold off by Xerox, still exists to this day [under the name Nuance](http://www.nuance.com/index.htm).
5. **In the early 1990s, hand-held scanners,** which relied on careful movement on the part of the user, became very popular among computer users, [selling hundreds of thousands of units per year](https://books.google.com/books?id=y1AEAAAAMBAJ&pg=PT48). These products, popular with desktop publishing, further gained usage after [the TWAIN standard](http://www.twain.org/twain-initiative/) helped bring a sense of consistency to the scanner market. Eventually, flatbed scanners—which offer better quality and more consistency—took over the market.

[/graybox][redbox]

[number]
### nine
[/number]

**The number of seconds** it takes the average person to solve a CAPTCHA, [according to Luis von Ahn](https://phys.org/news/2012-06-captcha-story-squiggly-letters.html), one of the creators of the technology, which was built at Carnegie Mellon University effectively to turn OCR’s weaknesses into a form of security. (Von Ahn is now the CEO of [DuoLingo](https://www.duolingo.com/), a language-education service.) The technology, bought by Google in 2009, eventually became sort of a failsafe for Google’s own OCR needs, for things like Google Books and Street View. Google recently announced, however, that it was moving away from CAPTCHAs entirely, [instead using automatic detection techniques](https://arstechnica.com/gadgets/2017/03/googles-recaptcha-announces-invisible-background-captchas/).

[/redbox][graybox]

**These days, OCR is way more capable** than when it first came into being—we do it on phones and over the web these days. That said, there are always ways to improve the process. Including, of course, through typography.

Last year, a company called [Anyline](https://www.anyline.io/), which sells a software development kit for OCR on mobile devices, decided to [take a fresh stab at the OCR font](https://www.anyline.io/free-ocr-font/) in an attempt to update it for the modern day.

![AnyOCR](http://tedium.imgix.net/2017/03/0323_anyocr.jpg)

*The AnyOCR font.*

“After 58 years we thought it was time for a new and better looking OCR font. That is why we simply designed one ourselves,” [the company’s Sophie Kreuzer wrote last September](https://www.anyline.io/blog/2016/09/02/anyocr-new-ocr-font/). “Even if you think that OCR fonts are outdated because almost every computer-written font is readable, there are still quite some advantages about it. And through our experience a lot of sectors still use OCR-A/B for their product specifications.”

The company made it available for free, maintaining its focus on the goals of the original fonts—to make the letters just as readable for machines as they are for humans.

It’s hard to say whether MoMA will give them a place in their collection, but it’s an impressive start.

[/graybox]
