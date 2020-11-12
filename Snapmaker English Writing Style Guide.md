# Introduction

Welcome! This is the official **Snapmaker English Writing Style Guide**. It is not a comprehensive grammar handbook, nor an academic writing reference book. It proposes rules that help standardize Snapmaker's documentations that are written in English, and prepare them for future reuse and localization.

This guide is compiled based on the need for our documentations to be factual, versatile, and user-friendly. It assumes readers come from varying backgrounds, and not all of them are native English speakers. As such, it prefers simple words and grammatical structures over complicated and fancy ones; it includes rules that violate traditional English grammar, though very rarely.

The **Language and Grammar** chapter outlines rules that govern right or wrong, while the **Formatting and Content Planning** chapter stipulates rules that determine good or bad. The sections are organized in alphabetic order. The latter half is a Chinese translation of the guide.

This guide is updated regularly. To report bugs or propose ideas, file an issue on [our GitHub page](https://github.com/Snapmaker), or email at ginger@snapmaker.com.


# Language and Grammar

## **Abbreviation**

It is helpful to distinguish between **initialisms**, **acronyms**, **shortened words**, and **contractions** first.

|**Type**|**Definition**|**Examples**|
|:----|:----|:----|
|**Initialism**|The first letters of words.|SME (subject matter expert)|
|**Acronym**|The first letters of words that's pronounced as a word.|SIM (subscriber identity module)|
|**Shortened words**|Part of a word or phrase, including Latin abbreviation.|app (application), Inc.(incorporated), i.e., etc., e.g.|
|**Contractions**|Part of a phrase, with a few letters replaced by an apostrophe.|isn't, you're, it's been so long|

To achieve a friendly tone, we use all types of abbreviation in our user experience (UX) writing. So it's okay to say:

* Supported OS: MacOS, Linux, Window 10 and above
* the US, the UK, the UN (with no **.** in between)
* app, demo, sync, docs, pics
* We're streaming!
* You'll find it exciting.
* Don't hesitate. Order it now!

While it is okay to use all types of abbreviations in UX content, avoid using contractions in Quick Start Guides and User Manuals. Use acronyms and shortened words with caution. And always define the term first; then include the abbreviated term in the following parenthesis.

For example, in this text, **Target Temperature** is used several times, which makes the whole paragraph look cluttered:

>Change the **Target Temperature** based on the filament you use (the default **Target Temperature** is 200 °C). While you wait for the temperature to rise to the **Target Temperature**, hang the filament onto the filament holder.

You can clean up the mess by using abbreviation:

>Change the **Target Temperature** (TT) based on the filament you use (the default **TT** is 200 °C). While you wait for the temperature to rise to the **TT**, hang the filament onto the filament holder.

Note that you should use the abbreviated phrase for subsequent mentions within the chapter, and don't switch between abbreviations and full forms. But, to avoid confusion in content reuse, provide full form in a parenthesis after the abbreviation once every chapter.

Don't use incorrect English. For example, don't say:

* There ain't anything you can't do.
* We gon' bring you the best experience ever!
* [What're the repeatability, max. travel length, backlash of the linear modules of three models?](https://support.snapmaker.com/hc/en-us/categories/360001781913-Snapmaker-2-0)
* trynna, wanna, gonna
* pp or ppl
* w/
* ur, u'r, y'all

Instead, say:

* There isn't anything you can't do.
* We're going to bring you the best experience ever!
* What are the repeatability, max. travel length, backlash of the linear modules of three models?
* try to, want to, going to
* people
* with
* your, you're, you all

If you are not sure about what is the accepted abbreviation of a certain word, check [American Heritage Dictionary](https://ahdictionary.com/). And as a rule of thumb, place yourself into your readers' shoes. If using abbreviation is likely to cause confusion, don't use it.

Regarding units of measure and their abbreviation, see [Snapmaker Glossary](https://shimo.im/sheets/9YTQWxT6yVkxYHGp).


## **Agreement**

### **Pronoun-antecedent Agreement**

A pronoun is used to refer to a noun or noun phrase previously mentioned. To achieve word economy, as well as increase readability, it is encouraged that you use pronouns where appropriate, instead of spelling out the whole term all the time.

However, do check whether your reference is clear after you finish writing, as pronouns can mislead your audience when used inappropriately. In the following note, for example, it is hard to tell what **its** refer to:

>[Note: Parts that are replaced under the Warranty also fall under its original warranty duration and do not restart.](https://support.snapmaker.com/hc/en-us/articles/360051069934-Snapmaker-s-Limited-Warranty)

On closer inspection, **its** might be referring to **parts** , but as **parts** is a plural noun, the correct pronoun should be **their**.


### **Subject-verb Agreement**

Although their misuse is not as confusing as that of pronouns and antecedents, it is essential that subjects and verbs agree with each other in number. The grammatical essentials are not covered in this guide. What this guide wants to stress is agreement and consistency.

For example, the following text refers to Snapmaker 2.0 as a single noun and a plural concept at the same time:

>[Snapmaker 2.0](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[, the modular 3-in-1 3D ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[printers](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ that ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[unlock](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ your full creative potential, from 3D printing to laser engraving, cutting, and CNC carving. ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[Snapmaker 2.0 is](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ smarter, faster, larger, and more powerful than ever before. ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[It](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[is a](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ new ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[generation](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ of 3-in-1 3D ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[printers](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ that ](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[come](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)[ with everything you need!](https://shop.snapmaker.com/products/snapmaker-2-0-modular-3-in-1-3d-printers)

Independently, each sentence in the text is correct, but this kind of switching creates difficulty for proofread, content reuse, as well as localization. It can be improved by being more consistent with agreement:

>**Snapmaker 2.0**, the modular 3-in-1 3D **printer** that **unlocks** your full creative potential, from 3D printing to laser engraving, cutting, and CNC carving. **Snapmaker 2.0 is** smarter, faster, larger, and more powerful than ever before. **It is** a new generation of 3-in-1 3D **printer** that **comes** with everything you need!
## **Articles**

Articles include indefinite articles **a**, **an**, and definite article **the**. This guide does not provide an exhaustive explaination of all three articles. Rather, it delineates some of the rules regarding the use of the definite article. For a more detailed usage guide, check out [Articles: A Complete Grammar Guide](https://www.grammarly.com/blog/articles/) by Grammarly.

The rule of thumb is to put a **the** before one or more particular members of a group that you want to address. That is, use **the** if the noun or noun phrase at issue is too generic and needs to be specified. Otherwise, use **a** or **an**, or don't use any article.

For example, numerous manufacturers use the term **auto levelling**, Snapmaker included. When you use **auto levelling** as a feature, or a distinctive selling point, put a **the** before it, as in:

>The auto levelling feature of Snapmaker helps you save time.

Whereas when it is used as more of a generic term, a standard process which is part of a whole procedure, don't precede it with a **the**, as in:

>Always do auto levelling before you print anything.

This being said, many people tend to overuse the definite article. In the following text, for  instance, **replacement** is preceded by a **the**, with the unintended consequence of making it sound like Snapmaker offers a non-standard type of replacement.

>[If there is no silicone pad, we will send you a new linear module for the replacement.  ](https://support.snapmaker.com/hc/en-us/articles/360051985253-What-should-I-do-if-some-linear-modules-stop-working-randomly-)

This sentence will look a lot more natural by deleting the definite article before **replacement**:

>If there is no silicone pad, we will send you a new linear module for replacement.

These nuances seem tricky to identify, so in order to help you navigate the world of articles, this section outlines a few common situations where **the** should or shouldn't be used.

Add **the** before:

* Names of products, services, software and firmware, parts, tools, printing materials, and other accessories that is unique to Snapmaker. As such, say:
    * the Snapmaker community instead of Snapmaker community
    * the Snapmaker Artisan instead of Snapmaker Artisan
    * the Snapmaker Luban instead of Snapmaker Luban
    * the Snapmaker A350 User Manual instead of Snapmaker A350 User Manual
    * the power module instead of power module
    * the USB cable instead of USB cable
    * the acrylic plate inside the material box instead of acrylic plate inside material box
* The elements in the UI which are not given a specific name by Snapmaker but have widely accepted names. As such, say:
    * the side bar insteadof side bar
    * the drop-down menu insteadof drop-down menu
    * the dialog box insteadof dialog box
    * the window instead of window
    * the page insteadof page

Don't add **the** before:

* A stand-alone **Snapmaker**, as in:
    * Snapmaker will not ask for your credit card PIN.
    * Snapmaker is an equal-opportunity employer.
* The name of errors, such as:
    * black screen
    * negative temperature
* A standard or universal service or operation, such as:
    * return
    * refund
    * replacement
    * update
* The name of buttons on the printer, and keys on the keyboard, such as:
    * power
    * Yes
    * Enter
    * Ctrl+C
    
## **Modifiers**

### Misplaced Modifiers

Modifiers should be put adjacent to the words they modify. When you separate the modifier with the word it describes, it can create confusion.

In the following text, **for no reason** is intended to describe **stop**, but they are separated by a string of words:

>[If the linear modules stop while the machine is working for no reasons, please do as follows to check the silicone pad inside the modules as the instruction below.](https://support.snapmaker.com/hc/en-us/articles/360051985253-What-should-I-do-if-some-linear-modules-stop-working-randomly-)

The audience can't help but wonder how can the machine be working for no reason. This kind of confusion can be avoided by moving **for no reason** next to **stop**:

>If the linear modules stop for no reason while the machine is working, please do as follows to check the silicone pad inside the modules.


### Multiple Modifiers

When a noun or noun phrase is preceded by more than two modifiers, it begins to look hard on the eyes.

Look at the following structures:

* An English language school teacher
* A recently rented small Council house
* The moving wheel gear casing

Grammar-wise, these expressions are okay, but they look awkward nonetheless. In situations like this, try and reduce the number of modifiers first. Ask yourself: is this modifier really necessary? Does it serve your purpose? If not, omit it.

Where each modifier provides indispensible information and can't be editted out, separate them with a preposition, a possessive form, a hyphen or a clause. Don't jam them all together before the nouns or pronouns they describe. So don't say:

* The linear module motor circuit board
* The upcoming more powerful laser module
* A regularly maintained open source software

Instead, say:

* The linear module's motor circuit board
* The upcoming laser module that’s more powerful
* A regularly maintained open-source software


### Noun Modifiers

Don't put more than two nouns before the central noun or noun phrase. For example, don't say:

* 3D printing sheet size
* Printer work table height

But it is okay to say:

* Machine temperature
* Heated Bed temperature
* Z-axis Holder

Where there are more than two nouns modifying the central noun or noun phrase, use possessive. For example, say:

* The size of 3D printing sheet
* The height of printer worktable

A general rule is to use **'s** after a living organism and a brand, while use **of** for possessive of a lifeless object. To be specific, use **'s** after Snapmaker as a brand name, and use **of** to indicate possessive for Snapmaker's products, tools, and services. For example, say:

* Michel's comment
* Snapmaker's return policy
* The specifications of the machine
* The horsepower of Tesla Model 3


## **Readability**

Most readers have a purpose in mind when browsing our documentations. They could be looking for guidance on certain steps, or they could simply be looking for shipping dates. Either way, simplicity and clarity reduces the volume of documentations and time your audience spend on locating needed information.


### Be Brief

Get to the point fast. Don't aim for politeness at the expense of efficiency. Limit each sentence to less than 25 words.

Write one sentence to express one idea. Avoid using clauses where possible. And avoid multiple clauses at all cost.

Prefer present tense over past tenses, as past tenses are more ambiguous and pose challenge for proofread. For example, don't say:

* Make sure you have put on CNC Safety Goggles before using the CNC function.
* If the machine failed to respond, check if the cables have been securely connected.

Instead, say:

* Put on CNC Safety Goggles before using the CNC function.
* If the machine fails to respond, check if the cables are securely connected.

Don't say **please**, **you can**, or **you should** at the beginning of every step. It is easy to unconsciously overuse **please**, regardless of tone. Refrain from using it in regular situations, because they lose meaning shortly and the content will become cluttered. Use it only when errors occur and fixing them can cause inconvenience for the user.

More words are not always more accurate. Always use less words when they are precise enough. For example, don't say:

* You can conduct a check on the machine.
* Please turn your machine off and on.
* Make sure the Heated Bed is clean and there isn't any dust or dirt on it before you place the Print Sheet.
* If you find the edges of the captured image are not aligned, you shall click **Calibration** to manually calibrate the camera.
* Snapmaker modular 3D printers are ideal choice for beginners who are just getting started, hobbyists who prefer more customized options, as well as engineers and designers who want to make large objects or accurate parts with outstanding print / engrave / cut / carve quality.

Instead, say:

* Check the machine.
* Restart your machine.
* Make sure the Heated Bed is contamination-free before you place the Print Sheet.
* If the edges of the captured image are not aligned, click **Calibration** to manually calibrate the camera.
* Snapmaker modular 3D printer is the ideal choice for beginners, hobbyists who are into customization, as well as engineers and designers who want to make large objects or accurate parts with outstanding quality.

Don't use expressions that are already ubiquitous in Chinese language. It's likely they will appear redundant in English as well, when translated. These expressions include:

* Some
* All kinds of
* Effectively
* Improve and enhance
* Update and improve
* Powerful and strong


### Be Precise
Being simple is important, but it should not come at the expense of clarity. After all, if the readers don't understand what you mean, a documentation becomes useless. 

If you have to use homonyms, define them first, especially in Quick Start Guides and User Manuals. The most commonly used homonyms that can be confusing include:

* Shall
* Must
* Need
* Should
* May
* Can

Avoid using **shall**, **need**, and **may**. Use **must**, **should**, and **can** instead. For clarification of these three words, copy and paste the following text where applicable:

>Throughout this document, **must** denotes a requirement. Failure to follow is likely to cause hazards. **Should** denotes strong recommendation. Failure to follow is likely to result in unsatisfactory printing results. **Can** demotes general recommendation, which points to resources sites.

Note that **should** and **can** carries double meanings. **Should** denotes recommendation, as well as probability. Similarly, **can** is used to grant permission, as well as denote possibility. For clarity, use **be expected to** instead of **should** to denote probability, and use **be likely to** instead of **can** to denote possibility. So, don't say:

* The machine should return to its original settings.
* Do not reach inside the machine while it is still in operation. An injury can be caused.

Instead, say:

* The machine is expected to return to its original settings.
* Do not reach inside the machine while it is still in operation, as it is likely to cause injury.

An exception is when **shall** is used in legal notices. In that case **shall** is used in place of **must**.

Avoid using words that are too vague or too weak to mean anything. Use specific and strong verbs instead. For example, don't say:

* There is a sidebar, choose **workspace**. There is a **Connection** icon on top left. Click the **refresh button**, and the software will reload serial ports list.
* It may cause a phenomenon called **dust accumulation**.
* You should use the dust plugs to avoid the problem of dust accumulation.
* If you can't find answer to your question in FAQs, ask help from our support team at support@snapmaker.com and our technical staff will do troubleshooting for you.
* Brim, raft, and skirt are detachable structures for minimizing the problem of object adherence to the Heated Bed.

Instead, say:

* From the left sidebar, enter **Workspace**. On top left, find **Connection** and click the **Refresh** button to reload serial ports list.
* It may cause dust accumulation.
* Use the dust plugs to avoid dust accumulation.
* If you can't find answer to your question in FAQs, ask help from our support team at support@snapmaker.com and our technical staff will troubleshoot for you.
* Brim, raft, and skirt are detachable structures for enhancing object adherence to the Heated Bed.

Don't create names for steps, processes or procedures. Check the [Snapmaker Glossary](https://shimo.im/sheets/9YTQWxT6yVkxYHGp) first.

In terms of grammar, avoid using **be + Verb (ing)** to describe future event. Use **be + Verb (ing)** to indicate progressive tense, while use the less confusing **will + Verb** to express future. For example, don't say:

>Follow our social media accounts and we are announcing the schedule of the online Makerathon very soon.

Instead, say:

>Follow our social media accounts and we will announce the schedule of the online Makerathon very soon.


### Be Thoughtful

Present the most imortant information first. Organize it in a way that is logical and requires minimum effort and brain gymnastics on audience's part.

Pay attention to the conjunctions **after** and **only if**. Put what's to be done first at the beginning of the sentence, not the opposite. For example, don't say:

>Check whether the laser module works properly, after putting on Safety Goggles.

Instead, say:

>After putting on Safety Goggles, check whether the laser module works properly.

Or:

>Put on Safety Goggles before you check whether the laser module works properly.

However, when using **if**, **in case**, and **in order to** (or **to** for that matter), let the reader know why, before giving instructions. For example, don't say:

* Unplug the cable and reconnect, if your port does not show up on the serial port list.
* Click **reset** to restore original configurations.

Instead, say:

* If your port does not show up on the serial port list, unplug the cable and reconnect.
* To restore original configurations, click **reset**.

Similarly, avoid using sentence inversion. It costs extra time for comprehension. Remember that not all audience are native speaker. For example, don't say:

* Come Christmas, and your Snapmaker A350 can do wonders for decoration.
* Never do we stop trying. We want you to have the best experience with Snapmaker.
* Not only can you bring your ideas to reality, you can spend time with your children.

Instead, say:

* When Christmas comes, your Snapmaker A350 will do wonders for decoration.
* Never do we stop trying. We want you to have the best experience with Snapmaker.
* You can bring your ideas to reality, while getting to spend time with your children.

Don't assume your audience know. Always provide background information when you introduce a concept, whether it is a link or a paragraph. Avoid expressions such as **simply**, **just**, **quickly**, **you are a click away**, and **it's easy**, as they can make users feel stupid.


## **Spelling**

Write in American English in all occasions, but avoid using North American slangs. American English can differ from British English in a variety of ways. The following table provides an overview.

|    |**American Spelling**|**British Spelling**|
|:----|:----|:----|
|**ou vs. ous**|color, flavor, favorite|colour, flavour, favourite|
|**g vs. gue**|catalog, dialog|catalogue, dialogue|
|**m vs. mme**|program|programme|
|**ze vs. se**|customize, organize|customise, organise|
|**er vs. re**|center, fiber|centre, fibre|
|**ce vs. se**|licence, practice|license, practise|
|**ll vs. l**|traveling, leveling|travelling, levelling|
|**e vs. ae**|encyclopedia|encyclopaedia|

This is not an exhaustive list of the differences. When in doubt, check this website: [UK VS US SPELLING](http://www.tysto.com/2012/05/uk-vs-us-spelling/).


### Numbers

As a general rule, numbers less than 10 should be spelled out, while 10 and anything larger should be written in numerals. A few exceptions should be noted:

* Write about numbers in UI as they are displayed. As such, say:
    * Work 0 instead of Work zero.
    * Z Offset instead of Z offset.
* Where 0 could be misread as the letter o or O, follow it with a spelled out zero in a parenthesis. For example, say:
    * Enter 0 (zero) in the bar, instead of Enter 0 in the bar.
* Write numerals for numbers less than 10 but have more than one digit. As such, say:
    * 3.1 instead of three point one.
    * 0.12 instead of zero point twelve.
* Write numerals when numbers are used together with units of measure. As such, say:
    * -2°C instead of minus two °C.
    * 8 dB instead of eight dB.
    * 5 mm instead of five mm.
* Write numerals when describing ranges. As such, say:
    * 2–3 months instead of two to three months.
    * 1-2 minutes instead of one to two minutes.
* Don't start a sentence with a numeral. Restructure the sentence instead. If you have to start your sentence with a number, then spell it out. As such, say:
    * Up till now, 10,000 customers have received their rewards.
    * Ten thousand customers have received their rewards.
    
    
### Units of Measure

Different systems of measurement are used across the world. While most of the world use the metric system, the US uses the imperial system. The following table provides an overview of their common differences.

|    |**Imperial System**|**Metrics System**|
|:----|:----|:----|
|**Lengths**|inch(in.), foot (ft), yard (yd), mile (mi.)|millimeters (mm), centimeters (cm), meters (m), kilometers (km)|
|**Area**|square inch (in²), square foot (ft²), square yard (yd²), acre, square mile|square millimeter (mm²), square centimeter (cm²), square meter (m²), hectare, square kilometer|
|**Volume**|ounce (oz), cup (C), pint (pt), quart, gallon|milliliter (ml), liter (L)|
|**Weights**|ounce (oz), pound (lb), ton (t)|gram (g), kilogram (kg), ton (t)|
|**Temperature**|°F|°C|
|**Speed**|feet per second (fps), miles per hour (mph)|meters per second (m/s), kilometers per hour (km/h)|

To cater to a global audience's needs, stick to one system of measurement throughout your writing, and provide conversions in brackets.

Abbreviate units of measure terms. Do not spell them out, unless you want to avoid confusion.

For example, say:

* 120 h instead of 120 hours
* 15 mm instead of 15 millimeter
* 45 kg instead of 45 kilogram
* 20 lb instead of 20 pounds

Don't follow the abbreviation with a period, unless the term is **inch**. In that case, write it as **in.**.

Consult [Snapmaker Glossary](https://shimo.im/sheets/9YTQWxT6yVkxYHGp) when in doubt.


## **Tone**

Generally, a formal tone shows professionalism, while an informal tone engages your audience. Take a formal tone when writing Quick Start Guides and User Manuals, whereas your UX writing can be a little more light-hearted.

In both cases, be factual and candid. Avoid promotional hype, exaggerations, and buzz words. Buzz words such as **empower**, **solution**, **robust**, **reach out to** give an impression of being pretentiousness, too lazy to think, or poorly educated. But be positive, too. Focus on what's achieved or improved, rather than what's not.

Avoid emojis, jokes, puns, internet slangs, and cultural or religious references.

Address your audience in second person. When writing in third person, use inclusive language rather than gender-specific words. For example, don't say:

>When operating this machine, user must follow safety instructions in this guide for his own safety. Snapmaker shall not be held responsible if he fails to do so and gets injured.

Instead, say:

>When operating this machine, users must follow safety instructions in this guide for their own safety. Snapmaker shall not be held responsible if users fail to do so and get injured.

Or, say:

>When operating this machine, persons must follow safety instructions in this guide for their own safety. Snapmaker shall not be held responsible if persons fails to do so and gets injured.

With an informal tone, be conversational. Violate grammar once or twice. It's okay to end sentences with prepositions. And it's okay to start a sentence with **And** or **But**.


# Formatting and Content Planning

Consistent formatting is an essential part of documentation success. It strengthens brand image and improves collaboration between content creation teams and other departments. Logical organization of contents not only reduces repetitive communications, but guides the audience through what you want them to see. This chapter covers Capitalization, Notation, Organization, Punctuation, and Spacing.


## **Capitalization**

There are two types of capitalization: sentence-style and title-style. In sentence style capitalization, only the first letter of the first word is capitalized, whereas in title-style capitalization, all first letters are capitalized except for those of articles and short prepositions.


### Dates and Times

Use 12-hour clock for expression of times. Capitalize all letters in **AM**, **PM**, and **UTC**. So don't say:

>Opening hours: Monday to Friday 9:30-12:30, 14:30-18:30 (utc+8)

Instead, say:

>Opening hours: Monday to Friday 9:30-12:30 AM, 2:30-6:30 PM (UTC+8)

Refer to 12:00 as **12 noon** or **12 midnight** to avoid causing confusion. The designations **noon** and **midnight** should be lower case.

An exception is UX-writing that addresses an event taking place solely in one country, in which case elements like **UTC-8** or **UTC-5** can look odd. Use the popular time indication in the country or region instead, and in upper case. Even if some countries may have more than one standard time, only use one. Common names of time zone are listed below.

|**Country or Region**|**Name**|**Offset**|**Commence**|
|:----|:----|:----|:----|
|**Canada, the US, and Mexico**|Pacific Standard Time (PST)|UTC-8|on the first Sunday of November|
|**Canada, the US, and Mexico**|Pacific Daylight Time (PDT)|UTC-7|on the second Sunday of March|
|**The UK and Ireland**|Greenwich Mean Time (GMT)|UTC+0|on the last Sunday of October|
|**The UK and Ireland**|Brisish Summer Time (BST)|UTC+1|on the last Sunday of March|
|**Members of European Union**|Central Europe Time (CET)|UTC+1|on the last Sunday of October|
|**Members of European Union**|Central Europe Standard Time (CEST)|UTC+2|on the last Sunday of March|
|**Australia**|Australian Eastern Standard Time (AEST)|UTC+10|on the first Sunday of April|
|**Australia**|Australian Eastern Daylight Time (AEST)|UTC+11|on the first Sunday of October|


### File Name Extensions

Refer to the file type in upper case when it's in the middle of the sentence. If the name of the file type is at the end of a sentence, write it out as **.file extension**. For example, don't say:

* Download the pdf of User Manual.
* Upload you jpg model file.
* The extension of the file is gcode.

Instead, say:

* Download the PDF of User Manual.
* Upload you JPG model file.
* The extension of the file is .gcode.


### Lists

Use sentence-style capitalization in a list, whether the introducing sentence ends with a colon or a period. For example, don't say:

>Prerequisite:
>* a pair of tweezers
>* a glue stick
>* two spools of PLA filament

Instead, say:

>Prerequisite:
>* A pair of tweezers
>* A glue stick
>* Two spools of PLA filament

If the list is embedded within a sentence, use lower case in the list. For example, don't say:

>Prerequisite: A pair of tweezers, 3-5 pieces of paper, and a spool of PLA filament.

Instead, say:

>Prerequisite: a pair of tweezers, 3-5 pieces of paper, and a spool of PLA filament.


### Notes

Use sentence-style capitalization in the sentence after **Note:**, **Tips:**, **Caution:**, and **Warning:**. For example, don't say:

>Note: if your machine is not responding, check A, B and C.

Instead, say:

>Note: If your machine is not responding, check A, B and C.


### Proper Nouns

Proper nouns can be divided to the following categories.

|**Type**|**Usage**|**Example**|
|:----|:----|:----|
|Names of the Snapmaker Brand|title-style|Snapmaker|
|Names of Snapmaker's Products|title-style|Snapmaker Artisan|
|Names of Snapmaker's Software, Firmware and App|title-style|Snapmaker Luban|
|Names of Steps, Features and Functions|title-style|Assembly, Initial Setup,<br>Auto Leveling, Auto Focus<br>3D Printing, CNC Carving|
|Names of Snapmaker's Services and Policies|sentence-style|Snapmaker's customer service, Snapmaker's return policy|
|Names of Parts, Tools, and Materials|title-style for those with Snapmaker's logo;<br>lowercase for the rest|Laser Module, Heated Bed, Calibration Card;<br>screwdriver, clamp set, acrylic plate|
|Names of Keys|as displayed on keyboards, regardless of operating system|Ctrl, Enter|
|Names of Errors|lowercase at all times; don't ever capitalize|black screen, power loss|
|X Axis, Y Axis, Z Axis and their Plural Forms|capitalize the **A** in **Axis** or **Axes** when used as non-adjective, otherwise don't capitalize|Z Axis, Z-axis Extension Module|

Note that hyphenated proper nouns should be capitalized in sentence-style. Refer to **Hyphens (-)** for more information.

### 
### Texts in a Table

In a table, column headers are at the topmost. They describe data in each column. Row headers are at the leftmost. They describe data in each row. You should:

* Use title-style capitalization for texts in column headers.
* Use title-style capitalization for texts in row headers.
* Treat data like the way you would in normal text.

For an illustration, see below:

|    |**Standard Deviation**|**Standard Error**|**Decision**|
|:----|:----|:----|:----|
|**Treatment A**|1.76643 (low)|0.233|PASS|
|**Treatment B**|4.76423 (too high)|1.232|FAIL|
|**Treatment C**|3.78789|0.467|TO BE CONFIRMED|


### Titles and Headings

Use title-style capitalization for titles and all levels of headings.


### Units of Measure

Use lowercase for terms of measurement, except for:

* Decibels (dB)
* Celsius degree (**°C**)
* Fahrenheit degree （**°F**)
* Milliwatt (mW)
* Megawatt (MW)


## **Notation**

### Admonitions

Be as brief as possible. Don't create a chunky paragraph out of a note. Don't add one note after another. If you have many things to note, consider weaving the information into your text. For example, don't do this:

![图片](https://uploader.shimo.im/f/IHdo2r0vpk6wsS3R.jpg!thumbnail)

This kind of information layout immediately puts an impatient reader off. The notes are scattered around the text, which is already a lot to consume in itself, and there is no good reason to pile up your notes like this.

Use **Note** to add information. Don't use **Attention**, **Notice**, **FYI**, or **PS**. For example, don't say:

>[Attention: Rest assured that our Technical support is always available to help you out under any circumstances, even if the issue is not covered under warranty. Please feel free to contact us at support@snapmaker.com. ](https://support.snapmaker.com/hc/en-us/articles/360051069934-Snapmaker-s-Limited-Warranty)

Instead, say:

>Note: Snapmaker online support is here to help you, whether the issue is related to parts covered by warranty. Contact us at support@snapmaker.com.

Separate adding information from warning your audience. Don't use a warning where a note can do the job. Don't overuse **Caution** and **Warning**, otherwise they will lose the weight they carry.

Occasionally you might need to use an asterisk (\*) to add a footnote. Use asterisk to add information on a word or phrase, not a text. And don't use it if a parenthesis can do the job.

Though it is not interchangeablewith admonitions, use it sparingly.See [Snapmaker Glossary](https://shimo.im/sheets/9YTQWxT6yVkxYHGp) for more information.


### Emphasis and Reference

Use bold text to highlight actions, or refer to book names, movie titles and the like. Don't capitalize all the letters. Don't use colons, quotation marks, apostrophes, italics, underlines, superscripts, or exclamation points as an emphasis. For example, don't say:

>Tap "Controls" on the Touchscreen, and tap "Home Axes" to run a homing session.
>Or:

>Tap *Controls* on the Touchscreen, and tap *Home Axes* to run a homing session.

Instead, say:

>Tap **Controls** on the Touchscreen, and tap **Home Axes** to run a homing session.

Also, use bold text when referring to elements in the UI. Occasionally, use icons along with bold text if it's easier to understand. For example, say:

>Enter **Workspace**![图片](https://uploader.shimo.im/f/eIGGgqXtlFM3r92O.png!thumbnail). On top left, find **Connection** and click the **Refresh** button![图片](https://uploader.shimo.im/f/MS5cpizgYDWUYhJf.png!thumbnail)to reload serial ports list.

### 
## **Organization**

### Headings

Don't put a number before the heading unless it's part of a sequential operation. Use styling rather than numbers to differentiate different levels of heading.

Use level 1–3 headings. Avoid creating level 4 and 5 headings. Too many layers of heading undermine readability.

Be as clear and simple as possible with headings. Avoid using vague language such as **miscellaneous**, **unspecified**, and **to be confirmed**. Always use more descriptive words if you can. If we want to make it convenient for our audience to find information, we should reduce times that they have to click and redirect.

Similarly, pay attention to the logic behind headings. Avoid overlap of contents under different headings of the same level. If overlap can't be avoided, provide links where the same thing are included. For example, the following headings are inappropriate for a User Manual of laser engraving:

* Before you start
* Prepare your Tools
* Initial Setup
* Steps
* Troubleshooting
* FAQs

First of all, **Before you Start** is too general. Any preparation could be swept in under it. In this sense, **Prepare your Tools** and **Initial Setup** should fall under **Before you Start**. Similarly, **FAQs** often include **Troubleshooting**; therefore it's not appropriate to list them as the same level of heading.

It's okay to name your heading in sentence form. That is, you can use verbs in headings. But do match the grammatical structure of the headings belonging to a same level. For example, don't say:

* Connecting to your PC
* Calibrate
* Loading Filament
* Editing Model File
* Start Printing

Instead, say:

* Connecting to your PC
* Calibrating the Heated Bed
* Loading Filament
* Editing Model File
* Start Printing

And just like stipulations in Readability, don't use internet slangs, jargons, and words that come from a different language in headings.


### Links

In UX writing, always introduce hyper link under the key words. In non-UX writing, introduce links with a preposition, instead of a colon. Where the link is lengthy, restructure your text to keep the link in one single line.

### Lists
 
It is helpful to check out [Google's comparison of different types of lists](https://developers.google.com/style/lists) first.

Avoid embedded lists. If your description can be sorted by a common denominator, use a list to increase scannability. For example, the following sentence contains an embedded list, and can be improved:

>Snapmaker A350 and Luban lets you customize your own design by adding support, adhesion and surface, generate a G-code and export it to your PC, send files to the machine via Wi-Fi, and stop the machine when an error occurs.

Introduce a bulleted list, and the sentence is easier to read:

Snapmaker A350 and Luban lets you:

* Customize your design by adding:
    * support
    * adhesion
    * surface
* Generate G-code.
* Export G-code to your PC.
* Send files to the machine via Wi-Fi.
* Stop the machine when an error occurs.

Ordered list tend to collapse when transferred to other authoring tools, while bulleted lists can be transferred without causing clutters. As a result, use ordered lists only if your are describing sequential operations. Otherwise, use unordered lists.


### Tables

Use tables as a means of comparing data. Don't use it to describe terms, steps, or report system updates.

Do not caption the table; as captions pose challenge to content reuse. Put the table immediately after its introductory text.

Use bold text for headers.


## **Punctuation**

### Ampersand **(&)**

Avoid using ampersand as shorthand for **and** unless absolutely necessary.


### Asterisks (*)

Use asterisks when adding footnote. See Notation.


### Colons (:)

Use colons to do the following:

* Introduce admonitions.
* Introduce contact information.

In text, use **at** instead of **:** or **at:** to introduce contact information. In footers in **Contact Us** pages, **Support** pages, **Detail** pages, and homepages, introduce contact information with colons.

Don't insert a colon after **including**, **excluding**, **except for**, **other than**, **apart from**, **such as**, and **for example**.


### Commas (,)

Include commas in the following situations:

* In an embedded list (avoid embedded lists if possible), before **and**.
* In an imperative sentence, before **and**.
* In a complex sentence, before an adverbial participle.
* In a compound sentence, before conjunctions.
* In one sentence where two questions are asked, before **or**.
* Before **too**, **neither**, and **either**.
* In numbers that have more than 3 digits.

For example, don't say:

* We represent detail-orientedness, creativity and passion.
* Before using CNC carving put on safety goggles.
* Take off the dust plugs and you will see the USB port.
* You will make your Snapmaker more versatile adding the latest rotary module.
* Have you ever wandered: do I buy a 3D printer? Or do I buy a 3-in-one fabrication machine?
* We feel disheartened by this terrible news too.
* 2100 mm

Instead, say:

* We represent detail-orientedness, creativity, and passion.
* Before using CNC carving, put on safety goggles.
* Take off the dust plugs, and you will see the USB port.
* You will make your Snapmaker more versatile, adding the latest rotary module—or better yet—
* Adding the latest rotary module, you will make your Snapmaker more versatile.
* Have you ever wandered: do I buy a 3D printer, or do I buy a 3-in-one fabrication machine?
* We feel disheartened by this terrible news too.
* 2,100 mm


### Ellipses (...)

Ellipsis is a set of three periods, used to indicate omission or hesitation. Don't use it.


### En dashes (**–**)

The en dash is slightly longer than a hyphen. Use an en dash instead of  a **~** (tilde) to indicate range. For example, don't say:

>Operating Temperature	-20℃ ~ 50℃ (-4°F~122°F)

Instead, say:

>Operating Temperature	-20℃–50℃ (-4°F–122°F)

To type an en dash, see below:

* On a Mac, press the **Alt** key and the **Minus (-)** key at the same time.
* On a PC, press the **Win** key and the **dot (.)** at the same time, click the **omega icon** at the top, scroll down to find the en dash.


### Em dashes (—)

The em dash is twice as long as the en dash. Use em dashes to indicate conversation or in place of parentheses.

To type an en dash, see below:

* On a Mac, press the **Alt** key, the **Shift** key and the **Minus (-)** key at the same time.
* On a PC, press the **Win** key and the **dot (.)** at the same time, click the **omega icon** at the top, scroll down to find the em dash.


### Exclamation points (!)

Use exclamation points sparingly.


### Hyphens (-)

|**Type**|**Use**|**Example**|
|:----|:----|:----|
|**Name of Tools**|no|USB disk, filament holder tube|
|**Name of Steps**|no|auto levelling, auto calibration|
|**Name of Errors**|no|power outage, connection failure, black screen|
|**Verb Plus Adverb**|no when used as noun; yes when used as adjective|plugin, add-on|
|**Noun Plus Past Participle**|no|computer controlled|
|**Adverb Plus Past Participle**|no|newly released|
|**Adjective Plus Noun**|no when used as noun; yes when used as adjective|high quality, high-precision|
|**Affix before Verb**|no, unless it interferes with comprehension|preorder, remeasure, defocuse, re-adjust, re-create|
|**Non-**|yes|non-European, non-American, non-standard|
|**Anti- and Counter-**|yes|anti-clockwise, counter-clockwise, counter-intuitive|
|**X Axis, Y Axis, Z Axis and their plural forms**|no, unless used as adjective|Z Axis, Z-axis Extension Module (See **Capitalization)**.|


### Parentheses ()

Use parentheses sparingly. If words in parentheses can be omitted without harming the integrity of sentence meaning, don't use them.


### Periods (.)

Long text without pause can be painful to read. The following description provides an extreme example:

>Keep adjusting the height of the nozzle using Up and Down buttons until there is slight resistance when you pull out the calibration card and it should be wrinkled when you push it forward.

Add a few commas and a period, it becomes more comprehensible:

>Keep adjusting the height of the nozzle using Up and Down buttons, until there is slight resistance when you pull out the calibration card. When you push it forward, the card should be wrinkled.

Use periods, as opposed to commas, to separate run-on sentences. For example, don't say:

>Cut the bending end of the filament using the diagonal pliers, then insert the filament into the 3D printing module.

Instead, say:

>Cut the bending end of the filament using the diagonal pliers. Then insert the filament into the 3D printing module.

Put the period after a link or parenthesis when they are part of the sentence.

Do not put a period after titles and headings, even if they are complete sentences.


### Quotation marks ("")

Don't use quotation marks to refer to elements in the UI or as emphasis. Use bold text instead. If you need to quote a whole paragraph, use the markdown grammar, instead of quotation marks.


### Semi-colons (;)

Use semi-colons to connect two sentences that are close in meaning. Otherwise, use periods. Also, note that therefore, otherwise, namely are adverbs. So separate them with the previous sentence with a semi-colon, rather than a comma. For example, don't say:

>The firmware is updated on 8th September, therefore if you use the previous version, you may experience delay.

Instead, say:

>The firmware is updated on 8th September; therefore if you use the previous version, you may experience delay.


### Slashes **(/)**

Avoid using slash as shorthand for **or**. On rare occasions where you have to use a slash, don't use more than one. More often than not, the slashes can be replaced by commas. For example, don't say:

>[You can recover any project and get perfect printing / engraving / cutting / carving results all the time.](https://snapmaker.com/product/snapmaker-2)

Instead, say:

>You can recover any project and get perfect printing, engraving, cutting or carving results at any time.

Don't write date as all numbers in MM/DD/YYYY format, or DD/MM/YYYY for that matter, as it can cause confusion. Use letters, rather than number to indicate months. Write year in four digits, and separate it with month and day with a comma. So don't say:

>We will host an orientation on 07/12/2020. Don't miss it!

Instead, say:

>We will host an orientation on Monday, December 7th, 2020. Don't miss it!

Avoid using backslashes.


## **Spacing**

Misplaced spaces can confuse your audience and give a bad impression.

While writing, follow these rules:

* Insert a space between numbers and units of measure.
* Insert a space before and after a phrase from another language.
* Insert a blank line between two paragraphs.

Pay close attention to spacing between words when they are connected by punctuation marks. Generally, insert one space after a punctuation mark, except for the following cases where you should put:

* No space adjacent to the slash or hyphen.
* One space before the opening bracket, and none between the closing bracket, if the sentence ends with parenthesis.
* One space before and after ampersand.
* One space before and after the multiplication sign.

Should you need to use Chinese Pinyin, don't put spacing within the pinyin.
