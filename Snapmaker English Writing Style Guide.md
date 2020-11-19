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

* Supported OS: macOS, Linux, Window 10 and above
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
* What're the repeatability, max. travel length, backlash of the linear modules of three models?
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

>Note: Parts that are replaced under the Warranty also fall under its original warranty duration and do not restart.

On closer inspection, **its** might be referring to **parts** , but as **parts** is a plural noun, the correct pronoun should be **their**.


### **Subject-verb Agreement**

Although their misuse is not as confusing as that of pronouns and antecedents, it is essential that subjects and verbs agree with each other in number. The grammatical essentials are not covered in this guide. What this guide wants to stress is agreement and consistency.

For example, the following text refers to Snapmaker 2.0 as a single noun and a plural concept at the same time:

>Snapmaker 2.0, the modular 3-in-1 3D printers that unlock] your full creative potential, from 3D printing to laser engraving, cutting, and CNC carving. Snapmaker 2.0 is smarter, faster, larger, and more powerful than ever before. It is a generation of 3-in-1 3D printers that com with everything you need!

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

>If there is no silicone pad, we will send you a new linear module for the replacement.

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

>If the linear modules stop while the machine is working for no reasons, please do as follows to check the silicone pad inside the modules as the instruction below.

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

>Attention: Rest assured that our Technical support is always available to help you out under any circumstances, even if the issue is not covered under warranty. Please feel free to contact us at support@snapmaker.com. 

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

Use semi-colons to connect two sentences that are close in meaning. Otherwise, use periods. Also, note that **then**, **therefore**, **otherwise**, and **namely** are adverbs. So separate them with the previous sentence with a semi-colon, rather than a comma. Or, alternatively, add a conjunction before them. For example, don't say:

>The firmware is updated on 8th September, therefore if you use the previous version, you may experience delay.

Instead, say:

>The firmware is updated on 8th September; therefore if you use the previous version, you may experience delay.


### Slashes **(/)**

Avoid using slash as shorthand for **or**. On rare occasions where you have to use a slash, don't use more than one. More often than not, the slashes can be replaced by commas. For example, don't say:

>You can recover any project and get perfect printing / engraving / cutting / carving results all the time.

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


<br>
<br>

# Snapmaker 英文写作风格指南

# 介绍
你好！你正在看的是《Snapmaker 英文写作风格指南》。这不是一本系统的语法手册，也不是学术写作参考。 它是为 Snapmaker 的英文文档标准化，未来复用的便利性，以及本地化的便利性服务的。

Snapmaker 希望我们的文档是尊重事实的、形式灵活的、以及用户友好的。这份指南的诞生正是基于这样的需求。它预设了读者有着不同的背景， 并且不是所有读者都是以英语为母语的。因此，这份指南有主张用简单的词汇和语法，而不是复杂和花哨的。指南里的规则有时并不符合传统的英语语法，尽管只是极少数情况。

指南包括两章，第一章是语言和语法，第二章是格式和内容规划。第一章列出的规则决定着对错，第二章列出的规则决定了好坏。每章下的各小节按照英文首字母的字母表顺序排列。

这份指南会经常更新。如果您发现错误或有任何提议，可以在我们的 Github 页面上提出 issue。另外，您也可以发邮件至 ginger@snapmaker.com。


# 语言和语法

## 缩略

首先需要区分首字母缩写（initialisms）、简写（acronyms）、略写（shortened words）和缩写（contractions）。

|**类型**|**定义**|**例**|
|:----|:----|:----|
|**首字母缩写（initialism）**|某个词组或短语的所有首字母的集合|SME (subject matter expert)|
|**简写**<br>**（acronym）**|某个词组或短语的所有首字母的集合，有自己的单独的发音|SIM (subscriber identity module)|
|**略写**<br>**（shortened words）**|某个词的一部分，或拉丁短语的一部分|app (application), Inc.(incorporated), i.e., etc., e.g.|
|**缩写（contractions）**|特定结构中，以引号替代某一两个字母|isn't, you're, it's been so long|


我们可以在所有用户体验（UX）类的文档写作中使用以上所有类型的缩略，以传达友好的语气。所以，你可以说：

* Supported OS: macOS, Linux, Window 10 and above
* the US, the UK, the UN (中间不用打点)
* app, demo, sync, docs, pics
* We're streaming!
* You'll find it exciting.
* Don't hesitate. Order it now!

虽然在UX类的文档写作中可以使用各种类型的缩略，但在说明书中尽量避免使用缩写，谨慎使用简写和略写。如果要使用，则先在括号内定义被缩略的词，再使用缩略。

举个例子，下面的文本中多次使用 **Target Temperature** 一词, 于是整个段落显得比较臃肿。

>Change the **Target Temperature** based on the filament you use (the default **Target Temperature** is 200 °C). While you wait for the temperature to rise to the **Target Temperature**, hang the filament onto the filament holder.

通过使用缩略，你可以把这个段落变得更简洁一些:



>Change the **Target Temperature** (TT) based on the filament you use (the default **TT** is 200 °C). While you wait for the temperature to rise to the **TT**, hang the filament onto the filament holder.

注意，如果你用了括号来规定某个词或短语的缩略形式，接下来提及它的时候你都应该使用缩略。不要在缩略和全称之间反复切换。但是，为了避免复用和迁移导致读者理解困难，应在每一章都重新使用一次全称。

不要使用错误的英语。比如，不要说：

* There ain't anything you can't do.
* We gon' bring you the best experience ever!
* What're the repeatability, max. travel length, backlash of the linear modules of three models?
* trynna, wanna, gonna
* pp or ppl
* w/
* ur, u'r, y'all

而应该说:

* There isn't anything you can't do.
* We're going to bring you the best experience ever!
* What are the repeatability, max. travel length, backlash of the linear modules of three models?
* try to, want to, going to
* people
* with
* your, you're, you all

如果你不确定某个词是否可以缩写或如何缩写，你可以在[American Heritage Dictionary](https://ahdictionary.com/)上查询。常规操作是想象自己是读者，如果某个缩略会导致读者的误解，那就避免使用这个缩略。

有关计量单位的缩写，查看 **Snapmaker 术语表** 的规定。

 
## 一致性

### 代词和先行词一致

代词可以替代前面提到的词或短语。为了实现语言的简洁，增加可读性，鼓励在合适的地方使用代词，而不是每次都用全称。

但是，一定要检查代词是否指代清楚，因为如果使用不当的话，反而会误导读者。举个例子，在下面的说明中，很难看出来 **its** 指代的是什么:

>Note: Parts that are replaced under the Warranty also fall under its original warranty duration and do not restart.

仔细一看，**its** 指代的可能是 **parts**, 但由于 **parts** 是复数，正确的代词应该是 **their**。

### 主谓一致

尽管主谓不一致并不像代词先行词不一致那样具有误导性，但主谓一致很重要。这份指南不讲基础的语法，而希望引起对连贯性和一致性的注意。

举个例子，下面的文本中一会儿将 Snapmaker 二代机当作单数，一会儿又当作复数：

>**Snapmaker 2.0**, the modular 3-in-1 3D **printers** that unlock your full creative potential, from 3D printing to laser engraving, cutting, and CNC carving. Snapmaker 2.0 **is** smarter, faster, larger, and more powerful than ever before. **It is** a generation of 3-in-1 3D **printers** that **come** with everything you need!

单独来看，每个句子都是对的。但这种单复数的切换会给校对、复用，和本地化带来困难。如果统一改为单数，就会好很多。

>**Snapmaker 2.0**, the modular 3-in-1 3D **printer** that **unlocks** your full creative potential, from 3D printing to laser engraving, cutting, and CNC carving. **Snapmaker 2.0 is** smarter, faster, larger, and more powerful than ever before. **It is** a new generation of 3-in-1 3D **printer** that **comes** with everything you need!

## 冠词

冠词包括不定冠词 **a**，**an**，以及定冠词 **the**。这份指南不详尽列出所有冠词的解释，而只是列出定冠词的一些用法。如果要了解详尽的冠词用法，查看 Grammarly 的 [Articles: A Complete Grammar Guide](https://www.grammarly.com/blog/articles/)。

常规做法是在指代某个群体中的特定成员时加 **the**，即，如果一个词或短语太过宽泛，需要特指，那就在它前面加 **the**。否则就用 **a** 或者 **an**，或者不用冠词。

举个例子，很多制造商，包括 Snapmaker 在内，都会使用 **auto levelling** 一词。 如果你使用 **auto levelling** 时表述的是一个功能，或一个独特的卖点，那就在它前面加 **the**，像这样：

>The auto levelling feature of Snapmaker helps you save time.

但是当这个词被当作一个宽泛的概念，或某个步骤中的一个标准操作来使用时，不要在它前面加 **the**，像这样：

>Always do auto levelling before you print anything.

尽管如此规定，很多人依然会过度使用定冠词。比如在下面这段文本中，**replacement** 前面加了一个 **the**，这就使得这句话背离了原意，读起来像 Snapmaker 提供某种独特的换货服务一样。

>If there is no silicone pad, we will send you a new linear module for the replacement. 

如果删掉 **replacement** 前面的定冠词，这句话读起来会自然得多：

>If there is no silicone pad, we will send you a new linear module for replacement.

这些细微的差别可能很难分辨，所以为了帮助判断，这一小节列出了一些应该使用 **the** 和不应该使用 **the** 的情况。

在以下情况前面加 **the**：

* 专属于 Snapmaker 的产品、软件、硬件、零件、工具、打印材料、和其他附件的名字。比如，你应该说：
    * the Snapmaker community 而非 Snapmaker community
    * the Snapmaker Artisan 而非f Snapmaker Artisan
    * the Snapmaker Luban 而非 Snapmaker Luban
    * the Snapmaker A350 User Manual 而非 Snapmaker A350 User Manual
    * the power module 而非 power module
    * the USB cable 而非 USB cable
    * the acrylic plate inside the material box 而非 acrylic plate inside material box
    
* 虽然并不专属于 Snapmaker，但是有被普遍使用的 UI 里面的元素的名称。比如，你应该说：
    * the side bar 而非 side bar
    * the drop-down menu 而非 drop-down menu
    * the dialog box 而非 dialog box
    * the window 而非 window
    * the page 而非 page

不要在以下情况前面加 **the**：

* **Snapmaker**作为一个独立的名称, 比如：
    * Snapmaker will not ask for your credit card PIN.
    * Snapmaker is an equal-opportunity employer.
* 错误的名称, 比如:
    * black screen
    * negative temperature
* 某个标准的或普遍的服务或操作，比如：
    * return
    * refund
    * replacement
    * update
* 打印机和键盘上的按键名，比如：
    * power
    * Yes
    * Enter
    * Ctrl+C
    
## 修饰语

### 错置的修饰语

修饰语应该与被修饰语紧密地放置在一起。如果它们被分隔开，有可能会造成误解。

在下面的文本中，**for no reason** 本来是要描述 **stop**，但它们之间隔了一串其他词语：

>If the linear modules stop while the machine is working for no reasons, please do as follows to check the silicone pad inside the modules as the instruction below.

读者可能会困惑：机器怎么会无缘无故地工作呢？类似这样的误解时可以避免的，只要把修饰语 **for no reason** 放在 **stop** 旁边：

>If the linear modules stop for no reason while the machine is working, please do as follows to check the silicone pad inside the modules.

### 多重修饰语

如果某个词或短语前面堆砌了超过两个修饰语，就会看起来不自然。

观察以下结构：

* An English language school teacher
* a recently rented small Council house
* the moving wheel gear casing

虽然从语法上讲，这些表达是可以的，但它们依然看起来很奇怪。如果出现类似这样的情况，先尝试删除修饰语。问一问自己：有必要用这个修饰语吗？它真的有用吗？如果没有，删掉它。

当每个修饰语都提供了不可或缺的信息所以不能省略时，尝试用介词、所有格、连字符或从句来将它们分开。不要让所有修饰语都挤在中心词的前面。所以，不要说:

* The linear module motor circuit board
* the upcoming more powerful laser module
* a regularly maintained open source software

而应该说：

* The linear module's motor circuit board
* the upcoming laser module that’s more powerful
* a regularly maintained open-source software

### 名词修饰语

不要在中心词前面放超过两个名词修饰语。比如，不要说：

* 3D printing sheet size
* printer work table height

但可以说：

* machine temperature
* heated bed temperature
* Z-axis Holder

如果中心词前面有超过两个名词修饰语，则改成所有格形式。比如，可以说:

* the size of 3D printing sheet
* the height of printer worktable

基本规则是，在有生命的东西、品牌名后面用 **'s**，而没有生命的物体的所有格用 **of** 来表示。比如，可以说：

* Michel's comment
* Snapmaker's return policy
* the specifications of the machine
* the horsepower of Tesla Model 3

## 可读性

大部分读者都是带着目的阅读我们的文档的。TA们有可能在找某一个步骤的说明，或者有可能只是在找关于发货日期的说明。不管读者要找什么，精简性和准确性能够减少文档的篇幅以及读者搜寻信息所需要的时间。

### 精简性

直奔主题。不要为了礼貌而牺牲精简性。将每个句子限制在25字以内。

一个句子只表达一个主题。尽量不要使用从句，更不要使用嵌套从句。

能用现在时就不要用过去时，因为过去时可能会有多重解读，给校对带来挑战。比如，不要说：

* Make sure you have put on CNC Safety Goggles before using the CNC function.
* If the machine failed to respond, check if the cables have been securely connected.

而应该说：

* Put on CNC Safety Goggles before using the CNC function.
* If the machine fails to respond, check if the cables are securely connected.

不要在每个操作前面都加上 **please**，**you can**，或者 **you should**。 无论采用什么语气，我们可能会无意识地过度使用 **please**。 通常情况下，避免使用 **please**，因为它们很快就会在文本中失去意义，并且会使文本臃肿。所以仅在错误出现，并且修复错误会给读者带来不便时使用 **please**。

不是文字越多越准确。只要描述够精准，尽量用更少的文字。比如，不要说：

* You can conduct a check on the machine.
* Please turn your machine off and on.
* Make sure the Heated Bed is clean and there isn't any dust or dirt on it before you place the Print Sheet.
* If you find the edges of the captured image are not aligned, you shall click **Calibration** to manually calibrate the camera.
* Snapmaker modular 3D printers are ideal choice for beginners who are just getting started, hobbyists who prefer more customized options, as well as engineers and designers who want to make large objects or accurate parts with outstanding print / engrave / cut / carve quality.

而应该说：

* Check the machine.
* Restart your machine.
* Make sure the Heated Bed is contamination-free before you place the Print Sheet.
* If the edges of the captured image are not aligned, click **Calibration** to manually calibrate the camera.
* Snapmaker modular 3D printer is the ideal choice for beginners, hobbyists who are into customization, as well as engineers and designers who want to make large objects or accurate parts with outstanding quality.

用中文构思时可有可无的表达翻译成英语后可能会更繁琐，不要用。这类例子有：

* Some
* All kinds of
* Effectively
* Improve and enhance
* Update and improve
* Powerful and strong

### 准确性

精简性很重要，但不应该以牺牲准确性为代价。毕竟如果读者不知道你在说什么，文档就成了废纸。

如果你要用多义词，先下定义再用，尤其是在纸质说明书和线上说明书中。常见的易引起歧义的多义词有：

* Shall
* Must
* Need
* Should
* May
* Can

不要用 **shall**，**need** 和 **may**，而应该用 **must**，**should** 和 **can**。如需厘清这几个概念，直接复制下面这段话并粘贴在在适当的地方即可。

>Throughout this document, **must** denotes a requirement. Failure to follow is likely to cause hazards. **Should** denotes strong recommendation. Failure to follow is likely to result in unsatisfactory printing results. **Can** demotes general recommendation, which points to resources sites.

注意 **should** 和 **can** 有双重意义。前者可以代表推荐，也可以用来判断可能性。而 **can** 除了用来应允外，也可以用来判断可能性。鉴于此，这份指南主张用 **be expected to** 而不是 **should** 来表示高可能性，以及用 **be likely to** 而不是 **can** 来表示一般可能性。所以，不要说：

* The machine should return to its original settings.
* Do not reach inside the machine while it is still in operation. An injury can be caused.

而应该说：

* The machine is expected to return to its original settings.
* Do not reach inside the machine while it is still in operation, as it is likely to cause injury.

也有例外。当 **shall** 用在法律性质的条文中时，它时不可替代的。此时应该用 **shall** 而不是 **must** 来表示必须。

避免使用太含糊或太弱的动词，而应该用更具体，更强的动词。比如，不要说：

* There is a sidebar, choose **workspace**. There is a **Connection** icon on top left. Click the **refresh button**, and the software will reload serial ports list.
* It may cause a phenomenon called **dust accumulation**.
* You should use the dust plugs to avoid the problem of dust accumulation.
* If you can't find answer to your question in FAQs, ask help from our support team at support@snapmaker.com and our technical staff will do troubleshooting for you.
* Brim, raft, and skirt are detachable structures for minimizing the problem of object adherence to the Heated Bed.

而应该说：

* From the left sidebar, enter **Workspace**. On top left, find **Connection** and click the **Refresh** button to reload serial ports list.
* It may cause dust accumulation.
* Use the dust plugs to avoid dust accumulation.
* If you can't find answer to your question in FAQs, ask help from our support team at support@snapmaker.com and our technical staff will troubleshoot for you.
* Brim, raft, and skirt are detachable structures for enhancing object adherence to the Heated Bed.

不要自己创造步骤、过程或操作的名称。先查询 **Snapmaker 术语表**。

语法方面，避免使用 **be + Verb (ing)** 来描述未来的事件，而应该用它来表示进行时。如果要描述将来的事件，用 **will + Verb** 的形式。比如，不要说：

>Follow our social media accounts and we are announcing the schedule of the online Makerathon very soon.

而应该说：

>Follow our social media accounts and we will announce the schedule of the online Makerathon very soon.

### 周密性

最重要的信息先说。用有逻辑的架构来组织信息，让读者能用最少的操作和思考获取和理解信息。

注意介词 **after** 和 **only if** 的放置顺序。把先做的操作放在前面，而不是后面。比如，不要说：

>Check whether the laser module works properly, after putting on Safety Goggles.

而应该说：

>After putting on Safety Goggles, check whether the laser module works properly.

或者说：

>Put on Safety Goggles before you check whether the laser module works properly.

但是，在使用 **if**, **in case**，和 **in order to**（或者 **to**）时，应该先告诉读者为什么，再告诉读者做什么。比如，不要说：

* Unplug the cable and reconnect, if your port does not show up on the serial port list.
* Click **reset** to restore original configurations.

而应该说：

* If your port does not show up on the serial port list, unplug the cable and reconnect.
* To restore original configurations, click **reset**.

类似地，不要使用倒装结构，因为它会增加理解的时间。记住并不是所有读者都是英语母语者。比如，不要说：

* Come Christmas, and your Snapmaker A350 can do wonders for decoration.
* Never do we stop trying. We want you to have the best experience with Snapmaker.
* Not only can you bring your ideas to reality, you can spend time with your children.

而应该说：

* When Christmas comes, your Snapmaker A350 will do wonders for decoration.
* Never do we stop trying. We want you to have the best experience with Snapmaker.
* You can bring your ideas to reality, while getting to spend time with your children.

不要预设读者具有背景知识。记得在引入新概念时要介绍背景知识，不管是以连接的形式还是段落的形式。避免说类似 **simply**，**just**，**quickly**，**you are a click away**， 和 **it's easy** 的表述，因为有的操作并不简单，你这么说会让读者有挫败感。


## **拼写**

所有场合都应使用美式拼写，但要避免使用北美的俚语。美式和英式英语在很多方面都不一样，

下面的表格提供了一个粗略的比较。

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

这份表格没有列出所有的英美式拼写的区别，如果你不确定某一个拼写是否正确，查询 [UK VS US SPELLING](http://www.tysto.com/2012/05/uk-vs-us-spelling/)。

### 数字

总体规则是，10以下的数字应该拼出来，而10及以上的则写成阿拉伯数字。除了以下情况：

* 某个数字在UI界面上怎么呈现，就怎么写这个数字。比如，应该说：
    * Work 0 instead of Work zero.
    * Z Offset instead of Z offset.
* 如果数字0可能被误认为是字母o，则在数字后面用圆括号标注 zero。 比如，应该说
    * Enter 0 (zero) in the bar，而不要说 Enter 0 in the bar。
* 有小数点的数字，即使小于10，也应该写成阿拉伯数字。 比如，应该说：
    * 3.1 而非 three point one
    * 0.12 而非 zero point twelve
* 后面有计量单位时，写阿拉伯数字。 比如，应该说：
    * -2°C 而非 minus two °C
    * 8 dB 而非 eight dB
    * 5 mm 而非 five mm
* 描述区间时，写阿拉伯数字。 比如，应该说：
    * 2–3 months 而非 two to three months
    * 1-2 minutes 而非 one to two minutes
* 不要用数字开始一个句子，尽量调整结构。如果无法避免，则把数字拼出来，无论数字是否大于10。比如，应该说：
    * Up till now, 10,000 customers have received their rewards.
    * Ten thousand customers have received their rewards.
    
### 单位

世界各地所用的计量制度并不相同。尽管大部分使用公制单位，美国使用的是英制。下面的表格提供一个粗略的比较。

|    |**Imperial System**|**Metrics System**|
|:----|:----|:----|
|**Lengths**|inch (in.), foot (ft), yard (yd), mile (mi.)|millimeters (mm), centimeters (cm), meters (m), kilometers (km)|
|**Area**|square inch (in²), square foot (ft²), square yard (yd²), acre, square mile|square millimeter (mm²), square centimeter (cm²), square meter (m²), hectare, square kilometer|
|**Volume**|ounce (oz), cup (C), pint (pt), quart, gallon|milliliter (ml), liter (L)|
|**Weights**|ounce (oz), pound (lb), ton (t)|gram (g), kilogram (kg), ton (t)|
|**Temperature**|°F|°C|
|**Speed**|feet per second (fps), miles per hour (mph)|meters per second (m/s), kilometers per hour (km/h)|

为了照顾全球的读者，不管使用公制或英制，都应该连贯地使用同一种，并在括号内提供另一种计量制度的换算值。

计量单位应使用缩略，不要拼出来，除非不拼出来会造成误解。比如，应该说：

* 120 h 而非 120 hours
* 15 mm 而非 15 milimeter
* 45 kg 而非 45 kilogram
* 20 lb 而非 20 pounds

不要在缩略词后面打点，除非被缩略的是 **inch**，这个词应该缩略成 **in.**。

如果不确定，查询 [Snapmaker 术语表](https://shimo.im/sheets/9YTQWxT6yVkxYHGp)对单位的规定。

## **语气**

一般而言，正式的语气传递出专业的形象，而非正式的语气则能拉近与读者的距离。写说明书时用正式的语气，而 UX 类的文档可以用轻快一些的语气。

但无论哪一种情况，都要尊重事实以及语气诚恳。避免太具有煽动性的宣传语，夸大其词，和口水话。类似**empower**, **solution**, **robust**, 和 **reach out to** 的口水话会给人一种装腔作势，懒得思考以及缺乏教养的印象。同时，也要使用正面的语言，强调做到了什么，而非没做到什么。

避免使用表情包，笑话，双关语，网络热词，跨文化传播有障碍的内容，以及涉及宗教的内容。

用第二人称来称呼你的读者。如果要用第三人称，记得使用更加包容的指称，而不是某个特定性别的人称。比如，不要说：

>When operating this machine, user must follow safety instructions in this guide for his own safety. Snapmaker shall not be held responsible if he fails to do so and gets injured.

而应该说：

>When operating this machine, users must follow safety instructions in this guide for their own safety. Snapmaker shall not be held responsible if users fail to do so and get injured.

或者说：

>When operating this machine, persons must follow safety instructions in this guide for their own safety. Snapmaker shall not be held responsible if persons fails to do so and gets injured.

用非正式语气时，口吻要平实。偶尔不尊重传统语法没有关系，用介词结句是 ok 的，用 **And** 或 **But** 开始一个句子也是 ok 的。


# 格式和内容规划

连贯的格式是好文档必不可缺的元素。它会加强品牌形象，以及内容创作团队和其他部门的合作。 有逻辑的内容规划则帮助减少重复沟通，以及引导读者去看你想要展示的内容。 本章包含大小写、加注、信息架构、标点，和间距的内容。

## **首字母大写**

首字母的大写分为句子式和标题式。句子式只大写第一个单词的首字母，而标题式则大写所有单词的首字母，除了冠词和短介词的首字母以外。

### 日期和时间

用12小时制表示时间。大写 **AM**，**PM**， 以及 **UTC** 中的所有字母。 因此，不要说：

>Opening hours: Monday to Friday 9:30-12:30, 14:30-18:30 (utc+8)

而应该说：

>Opening hours: Monday to Friday 9:30-12:30 AM, 2:30-6:30 PM (UTC+8)

提到12点时，要写清楚是中午还是晚上。中午说 **12 noon**，晚上说 **12 midnight**。所有字母小写。

在 UX 类文档写作中，有时需要描述某个只在特定国家开展的活动，比如北美商城的促销，这种情况下UTC-8 或 UTC-5 这类写法可能会很奇怪。此时，应该用当地常用的时间表示法来描述时间，字母全大写。即使有的国家同时在用好几种时间，我们也只用一种。详见下表。

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


### 文件名后缀

在句子中间用大写表示文件名后缀，在句子末尾则用 **.小写后缀** 的形式。比如，不要说：

* Download the pdf of User Manual.
* Upload you jpg model file.
* The extension of the file is gcode.

而应该说：

* Download the PDF of User Manual.
* Upload you JPG model file.
* The extension of the file is .gcode.

### 列表

列表里使用句子式大写，无论介绍句的结尾是逗号还是冒号。比如，不要说：

>Prerequisite:
>-a pair of tweezers
>-a glue stick
>-two spools of PLA filament

而应该说：

>Prerequisite:
>-A pair of tweezers
>-A glue stick
>-Two spools of PLA filament

如果列表是嵌在句子中的，所有首字母都应该小写。所以，不要说：

>Prerequisite: A pair of tweezers, 3-5 pieces of paper, and a spool of PLA filament.

而应该说：

>Prerequisite: a pair of tweezers, 3-5 pieces of paper, and a spool of PLA filament.

### 注解

**Note:** **Tips:** **Caution:** 和 **Warning:** 后面的句子首词用句子式大写。比如，不要说：

>Note: if your machine is not responding, check A, B and C.

而应该说：

>Note: If your machine is not responding, check A, B and C.

### 专有名词

专有名词的首字母大写根据类型可以总结为：

|**类型**|**用法**|**例**|
|:----|:----|:----|
|Snapmaker 品牌名|标题式|Snapmaker|
|Snapmaker 产品名|标题式|Snapmaker Artisan|
|Snapmaker 的软件、硬件、应用名|标题式|Snapmaker Luban|
|步骤、特色、功能名|标题式|Assembly, Initial Setup,<br>Auto Leveling, Auto Focus<br>3D Printing, CNC Carving|
|Snapmaker 的服务和政策|句子式|Snapmaker's customer service, Snapmaker's return policy|
|零件、工具、材料名|有 Snapmaker logo 的用标题式，其余全小写|Laser Module, Heated Bed, Calibration Card;<br>screwdriver, clamp set, acrylic plate|
|键盘名|与键盘上一致|Ctrl, En|
|错误名|全小写，任何时候都不大写|black screen|
|X Axis, Y Axis, Z Axis 以及它们的复数形式|不作定语时，大写 **Axis** 或 **Axes** 的首字母 A，作定语时加连字号且不大写 a|Z Axis, Z-axis Extension Module|

中间有连字符的专有名词用句子式。

### 表格中的文字

在表格中，表头（纵向最上和横向最左）文字都用标题式，其余文字的处理同正文。类似这样：

|    |**Standard Deviation**|**Standard Error**|**Decision**|
|:----|:----|:----|:----|
|**Treatment A**|1.76643 (low)|0.233|PASS|
|**Treatment B**|4.76423 (too high)|1.232|FAIL|
|**Treatment C**|3.78789|0.467|TO BE CONFIRMED|



### 题目和标题

题目和各级标题用标题式。


### 单位

所有计量单位的所有字母都用小写，除了以下情况：

* Decibels (dB)
* Celsius degree (**°C**)
* Fahrenheit degree （**°F**)
* Milliwatt (mW)
* Megawatt (MW)


## **加注**

### 注解

尽可能简洁。不要把注解变成段落。不要叠加多个注解。如果有很多信息要说明，尝试把它们加到正文中。比如，不要这样写：

![图片](https://uploader.shimo.im/f/vvT2MA9jKPMa1Ule.jpg!thumbnail)

这种信息布局分分钟让没耐心的读者关闭页面。注解一个叠一个，还分散在正文的各个方向，而且正文本身已经提供了很多需要消化的信息。

用 **Note** 来添加额外说明，不要用 **Attention**，**Notice**，**FYI**，或者 **PS**。比如，不要说：

>Attention: Rest assured that our Technical support is always available to help you out under any circumstances, even if the issue is not covered under warranty. Please feel free to contact us at support@snapmaker.com.

而应该说：

>Note: Snapmaker online support is here to help you, whether the issue is related to parts covered by warranty. Contact us at support@snapmaker.com.

区分说明和警告，能用说明时不要用警告。不要过度使用 **Caution** 和 **Warning**，否则它们会失去警戒作用。

你可能偶尔需要用星号（\*）来添加脚注。但注意，仅用星号来为某个词或短语，而不是文本加脚注。 另外，可以用括号就不要用星号。尽管星号有不可替代的作用，但尽可能少用。

详询[Snapmaker 术语表](https://shimo.im/sheets/9YTQWxT6yVkxYHGp)。

### 强调和提及

强调动作，或提及书名、电影名之类时用粗体。不要大写所有字母，不要用冒号，引号，斜体，下划线，右上角字体或感叹号来做强调。 比如，不要说：

>Tap "Controls" on the Touchscreen, and tap "Home Axes" to run a homing session.
>或者：

>Tap *Controls* on the Touchscreen, and tap *Home Axes* to run a homing session.

而应该说：

>Tap **Controls** on the Touchscreen, and tap **Home Axes** to run a homing session.

另外，提及 UI 上的元素时用粗体。如果增加 UI 上的符号能帮助理解，也可以和粗体一起使用。比如，可以说：

>Enter **Workspace**![图片](https://uploader.shimo.im/f/eIGGgqXtlFM3r92O.png!thumbnail). On top left, find **Connection** and click the **Refresh** button![图片](https://uploader.shimo.im/f/MS5cpizgYDWUYhJf.png!thumbnail) to reload serial ports list.

## **信息架构**

### 标题

不要在标题前面加序号，除非此标题是某个有序操作的一个步骤。各级标题之间用格式来做区分，而不要用数字。

只用1-3级标题，避免使用4-5级标题。标题层级太多会影响阅读体验。

给标题命名时越清楚越好。不要用类似 **miscellaneous**, **unspecified**, 和 **to be confirmed** 这样的含混的表述来做标题。如果希望读者能够便利地获得信息，我们应该减少读者点击——重新定向——退出——重新定向的次数，所以标题越有描述性越好。

同理，注意标题命名的逻辑。同级的不同标题下面，内容不要有重合。如果无法避免内容重合，则提供跳转链接，告诉读者，还可以在另一个地方找到此项信息。举个例子，以下列出的标题，假设出现在激光雕刻的线上说明书中，就是不合适的：

* Before you start
* Prepare your Tools
* Initial Setup
* Steps
* Troubleshooting
* FAQs

首先，**Before you Start** 太宽泛了，任何准备工作都可以归到这个标题下面。那么，**Prepare your Tools** 以及 **Initial Setup** 就应该是 **Before you Start** 下一级的标题. 同样，**FAQs** 通常都会包括 **Troubleshooting**，也就是说，它们不应该作为同级标题。

你可以用句子做标题，也就是说，你可以在标题中使用动词。但是，同级标题应该使用同样的语法结构。比如，不要说：

* Connecting to your PC
* Calibrate
* Loading Filament
* Editing Model File
* Start Printing

而应该说：

* Connecting to your PC
* Calibrating the Heated Bed
* Loading Filament
* Editing Model File
* Start Printing

另外，和可读性原则里提到的要求一样，不要用俚语、行话、和另一种语言来给标题命名。

### 链接

在 UX 类文档写作中，如果要加入链接，把链接加在关键词下面，而不要单独放出来。在非 UX 类的写作中，用介词 **at** 或 **from** 来引出链接，而不要用冒号。如果链接太长，就重新组织语言，把链接放在一行内。

### 列表

尽量避免嵌在句子当中的列表。如果你的写作中有好几个有共同之处的对象，用列表把它们列出来，这有利于快速浏览。举个例子，以下这个句子包含一个内嵌的列表：

>Snapmaker A350 and Luban lets you customize your own design by adding support, adhesion and surface, generate a G-code and export it to your PC, send files to the machine via Wi-Fi, and stop the machine when an error occurs.

如果把内嵌列表里的对象单独列出来，这个句子会更易读：

Snapmaker A350 and Luban lets you:

* Customize your design by adding:
    * support
    * adhesion
    * surface
* Generate G-code.
* Export G-code to your PC.
* Send files to the machine via Wi-Fi.
* Stop the machine when an error occurs.

有序列表在迁移时可能会导致格式错乱，而子弹型列表不会。因此，仅在描述步骤时使用有序列表，其他时候使用无序列表。

### 表格

用表格来做对比。不要用它来描述术语、步骤或报告系统更新情况。

不要给表格起名字，因为迁移时可能会造成混乱。表格应该紧邻其介绍段。

表头内容用粗体。


## **标点**

### 和符号（&）

除非必要，避免使用此符号来替代 **and**。

### 星号（\*）

Use asterisks when adding footnote. See Notation.

### 冒号（:）

以下情况使用冒号：

* 添加注释
* 介绍联系方式

正文中，用 **at** 而不要用 **:** 或者 **at:** 来介绍联系方式。在 **Contact Us**，**Support**，**Detail** 页面和网站主页的最下角，用冒号来介绍联系方式。

不要在 **including**，**excluding**，**except for**，**other than**，**apart from**，**such as**，和 **for example** 的后面加冒号。

### 逗号（,）

以下情况使用逗号：

* 内嵌列表中，**and** 前面
* 祈使句中，**and** 前面
* 复杂句中，作状语的分词前面
* 复合句中，连词前面
* 同一个句子中有两个问题，**or** 前面
* **too**,**neither**,**either** 前面
* 超过三位的数字中，从右往左，每三个数字之间。

比如，不要说：

* We represent detail-orientedness, creativity and passion.
* Before using CNC carving put on safety goggles.
* Take off the dust plugs and you will see the USB port.
* You will make your Snapmaker more versatile adding the latest rotary module.
* Have you ever wandered: do I buy a 3D printer? Or do I buy a 3-in-one fabrication machine?
* We feel disheartened by this terrible news too.
* 2100 mm

而应该说:

* We represent detail-orientedness, creativity, and passion.
* Before using CNC carving, put on safety goggles.
* Take off the dust plugs, and you will see the USB port.
* You will make your Snapmaker more versatile, adding the latest rotary module 或者——
* Adding the latest rotary module, you will make your Snapmaker more versatile.
* Have you ever wandered: do I buy a 3D printer, or do I buy a 3-in-one fabrication machine?
* We feel disheartened by this terrible news too.
* 2,100 mm

### 省略号（...）

英文省略号是三个句号，用来表示省略或犹豫。不要用。

### En dash（–）
此符号比连字符稍长。用 en dash 来表示区间，而不要用波浪线 **~** 。比如，不要说：

>Operating Temperature	-20℃ ~ 50℃ (-4°F~122°F)

而应该说：

>Operating Temperature	-20℃–50℃ (-4°F–122°F)

打 en dash 的方式如下：

* 如果是 Mac 键盘，同时按下 **Alt** 键和 **减号（-）** 键。
* 如果是 Windows 键盘, 同时按下 **开始** 键和 **句号（.）** 键，点击上方的 **omega** 符号，下拉可找到 en dash。

### Em dash （—）
此符号是 en dash 的两倍长. 用 em dash 来表示对话，和在文本中加说明。

打 em dash 的方式如下：

* 如果是 Mac 键盘，同时按下 **Alt** 键，**Shift** 键，和 **减号（-）** 键。
* 如果是 Windows 键盘, 同时按下 **开始** 键和 **句号（.）** 键，点击上方的 **omega** 符号，下拉可找到 em dash。

### 感叹号（!）
少用。

### 连字符（-）

|**类型**|**是否使用**|**例子**|
|:----|:----|:----|
|工具名|否|USB disk, Z axis|
|步骤名|否|auto leveling, auto calibration|
|错误名|否|power outage, connection failure, black screen|
|动词加副词|作名词用，否; 作形容词用，是|plugin, add-on|
|名词加过去分词|否|computer controlled|
|副词加过去分词|否|newly released|
|形容词加名词|作名词用，否; 作形容词用，是|high quality, high-precision|
|有前缀的动词|否，除非影响理解|preorder, remeasure, defocuse, re-adjust，re-create|
|有前缀，前缀为 Non-|是|non-European, non-American, non-standard|
|有前缀，前缀为 Anti- 或 Counter-|是|anti-clockwise, counter-clockwise, counter-intuitive|
|X Axis, Y Axis, Z Axis 以及它们的复数形式|否，除非作定语|Z Axis, Z-axis Extension Module|


### 括号 ()

少用。如果删除括号内的内容不影响句子意思的完整性，不要用。

### 句号（.）

没有停顿的长篇大段是很难读的。以下是一个极端的案例：

>Keep adjusting the height of the nozzle using Up and Down buttons until there is slight resistance when you pull out the calibration card and it should be wrinkled when you push it forward.

加上一些逗号和句号，整个段落会更好理解：

>Keep adjusting the height of the nozzle using Up and Down buttons, until there is slight resistance when you pull out the calibration card. When you push it forward, the card should be wrinkled.

用句号，而不是逗号来连接两个完整的句子。比如，不要说：

>Cut the bending end of the filament using the diagonal pliers, then insert the filament into the 3D printing module.

而应该说：

>Cut the bending end of the filament using the diagonal pliers. Then insert the filament into the 3D printing module.

如果一个句子由一个链接结束，别忘了在链接后面打句号。

不要在题目和标题结尾打句号，即使它们读起来是完整的句子。

### 双引号（""）

不要用双引号来提及UI里面的元素，用粗体。如果需要引用一个整段，用 markdown 语法，而不要用双引号或单引号。

### 分号（;）

两个完整句子之间如果意思相近，用分号连接。否则用句号。此外，需注意 **then**，**therefore**，**otherwise**，以及 **namely** 是副词。所以应该用分号而不是逗号把它们和前一个句子隔开。或者，在它们前面加上连词。比如，不要说：

>The firmware is updated on 8th September, therefore if you use the previous version, you may experience delay.

而应该说：

>The firmware is updated on 8th September; therefore if you use the previous version, you may experience delay.

### 斜杠（/）

不要用斜杠来代替 **or**。如果非用不可，也不要多个并排用，因为大部分情况下可以用逗号替代多个斜杠。比如，不要说：

>You can recover any project and get perfect printing / engraving / cutting / carving results all the time.

而应该说：

>You can recover any project and get perfect printing, engraving, cutting or carving results at any time.

不要用斜杠来间隔日期和时间。用连字符来间隔年月日，用冒号来间隔时分秒。比如，不要说：

>We will host an orientation on 07/12/2020. Don't miss it!

而应该说：

>We will host an orientation on Monday, December 7th, 2020. Don't miss it!

避免使用反方向的斜杠。

## **间距**

间距不对有可能会造成误解，并且给人不专业的印象。

遵循以下原则：

* 数字和单位之间空一格。
* 切换语言时，引入语和主体语言之间空一格。
* 两个段落之间空一行。

有标点时，注意它们与文字前后的间距。 一般而言，在标点后面，文字前面空一格。除了以下情况：

* 斜杠或连字符与文字之间不空格。
* 如果括号结束一个句子，左括号前空一格，右括号和句号之间不空格。
* **&** 符号前后各空一格。
* 乘号前后各空一格。

如果你要用拼音，不要在同一个词的拼音内加空格。


