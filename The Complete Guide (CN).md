# Snapmaker 英文写作风格指南

# 介绍
你好！你正在看的是《Snapmaker 英文写作风格指南》。这不是一本系统的语法手册，也不是学术写作参考。 它是为 Snapmaker 的英文文档标准化，未来复用的便利性，以及本地化的便利性服务的。

Snapmaker 希望我们的文档是尊重事实的、形式灵活的、以及用户友好的。这份指南的诞生正是基于这样的需求。它预设了读者有着不同的背景， 并且不是所有读者都是以英语为母语的。因此，这份指南有主张用简单的词汇和语法，而不是复杂和花哨的。指南里的规则有时并不符合传统的英语语法，尽管只是极少数情况。

指南包括两章，第一章是语言和语法，第二章是格式和内容规划。第一章列出的规则决定着对错，第二章列出的规则决定了好坏。每章下的各小节按照英文首字母的字母表顺序排列。

这份指南会经常更新。如果您发现错误或有任何提议，可以在我们的 Github 页面上提出 issue。另外，您也可以发邮件至 ginger@snapmaker.com。


# 1. 语言和语法

## 1.1 缩略

首先需要区分首字母缩写（initialisms）、简写（acronyms）、略写（shortened words）和缩写（contractions）。

|**类型**|**定义**|**例**|
|:----|:----|:----|
|**首字母缩写（initialism）**|某个词组或短语的所有首字母的集合|SME (subject matter expert)|
|**简写**<br>**（acronym）**|某个词组或短语的所有首字母的集合，有自己的单独的发音|SIM (subscriber identity module)|
|**略写**<br>**（shortened words）**|某个词的一部分，或拉丁短语的一部分|app (application), Inc. (incorporated), i.e., etc., e.g.|
|**缩写（contractions）**|特定结构中，以引号替代某一两个字母|isn't, you're, it's been so long|


我们可以在所有用户体验（UX）类的文档写作中使用以上所有类型的缩略，以传达友好的语气。所以，你可以说：

* Supported OS: macOS, Linux, Window 10 and above
* the US, the UK, the UN (中间不用打点)
* app, demo, sync, docs, pics
* We're streaming!
* You'll find it exciting.
* Don't hesitate. Order it now!

虽然在 UX 类的文档写作中可以使用各种类型的缩略，但在说明书中尽量避免使用缩写，谨慎使用简写和略写。如果要使用，则先在括号内定义被缩略的词，再使用缩略。

举个例子，下面的文本中多次使用 **Target Temperature** 一词, 于是整个段落显得比较臃肿。

>Change the **Target Temperature** based on the filament you use (the default **Target Temperature** is 200 °C). While you wait for the temperature to rise to the **Target Temperature**, hang the filament onto the filament holder.

通过使用缩略，你可以把这个段落变得更简洁一些:



>Change the **Target Temperature** (TT) based on the filament you use (the default **TT** is 200 °C). While you wait for the temperature to rise to the **TT**, hang the filament onto the Filament Holder.

注意，如果你用了括号来规定某个词或短语的缩略形式，接下来提及它的时候你都应该使用缩略。不要在缩略和全称之间反复切换。但是，为了避免复用和迁移导致读者理解困难，应在每一章都重新使用一次全称。

不要使用错误的英语。比如，不要说：

* There ain't anything you can't do.
* We gon' bring you the best experience ever!
* What're the repeatability, max. travel length, and backlash of the Linear Modules of three models?
* trynna, wanna, gonna
* pp or ppl
* w/
* ur, u'r, y'all

而应该说:

* There isn't anything you can't do.
* We're going to bring you the best experience ever!
* What are the repeatability, max. travel length, and backlash of the Linear Modules of three models?
* try to, want to, going to
* people
* with
* your, you're, you all

如果你不确定某个词是否可以缩写或如何缩写，你可以在[American Heritage Dictionary](https://ahdictionary.com/)上查询。常规操作是想象自己是读者，如果某个缩略会导致读者的误解，那就避免使用这个缩略。

有关计量单位的缩写，查看 **Snapmaker 术语表** 的规定。

 
## 1.2 一致性

### 1.2.1 代词和先行词一致

代词可以替代前面提到的词或短语。为了实现语言的简洁，增加可读性，鼓励在合适的地方使用代词，而不是每次都用全称。

但是，一定要检查代词是否指代清楚，因为如果使用不当的话，反而会误导读者。举个例子，在下面的说明中，很难看出来 **its** 指代的是什么:

>Note: Parts that are replaced under the Warranty also fall under its original warranty duration and do not restart.

仔细一看，**its** 指代的可能是 **parts**, 但由于 **parts** 是复数，正确的代词应该是 **their**。

### 1.2.2 主谓一致

尽管主谓不一致并不像代词先行词不一致那样具有误导性，但主谓一致很重要。这份指南不讲基础的语法，而希望引起对连贯性和一致性的注意。

举个例子，下面的文本中一会儿将 Snapmaker 二代机当作单数，一会儿又当作复数：

>**Snapmaker 2.0**, the modular 3-in-1 3D **printers** that unlock your full creative potential, from 3D printing to laser engraving, cutting, and CNC carving. Snapmaker 2.0 **is** smarter, faster, larger, and more powerful than ever before. **It is** a generation of 3-in-1 3D **printers** that **come** with everything you need!

单独来看，每个句子都是对的。但这种单复数的切换会给校对、复用，和本地化带来困难。如果统一改为单数，就会好很多。

>**Snapmaker 2.0**, the modular 3-in-1 3D **printer** that **unlocks** your full creative potential, from 3D printing to laser engraving, cutting, and CNC carving. **Snapmaker 2.0 is** smarter, faster, larger, and more powerful than ever before. **It is** a new generation of 3-in-1 3D **printer** that **comes** with everything you need!

## 1.3 冠词

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

* 专属于 Snapmaker 的产品、软件、硬件、零件、工具、打印材料和其他附件的名字。比如，你应该说：
    * the Snapmaker community 而非 Snapmaker community
    * the Snapmaker Artisan 而非 Snapmaker Artisan
    * the Snapmaker Luban 而非 Snapmaker Luban
    * the Snapmaker A350 User Manual 而非 Snapmaker A350 User Manual
    * the Power Module 而非 Power Module
    * the USB cable 而非 USB cable
    * the acrylic plate inside the material box 而非 acrylic plate inside material box
    
* 虽然并不专属于 Snapmaker，但是有被普遍使用的 UI 里面的元素的名称。比如，你应该说：
    * the sidebar 而非 sidebar
    * the drop-down menu 而非 drop-down menu
    * the dialog box 而非 dialog box
    * the window 而非 window
    * the page 而非 page

不要在以下情况前面加 **the**：

* **Snapmaker** 作为一个独立的名称, 比如：
    * Snapmaker will not ask for your credit card PIN.
    * Snapmaker is an equal-opportunity employer.
* 描述错误的名称，比如:
    * black screen
    * negative temperature
* 某个标准的或普遍的服务或操作，比如：
    * return
    * refund
    * replacement
    * update
* 打印机和键盘上的按键名，比如：
    * Power
    * Yes
    * Enter
    * Ctrl+C
    
## 1.4 修饰语

### 1.4.1 错置的修饰语

修饰语应该与被修饰语紧密地放置在一起。如果它们被分隔开，有可能会造成误解。

在下面的文本中，**for no reason** 本来是要描述 **stop**，但它们之间隔了一串其他词语：

>If the Linear Modules stop while the machine is working for no reasons, please do as follows to check the silicone pad inside the modules as the instruction below.

读者可能会困惑：机器怎么会无缘无故地工作呢？类似这样的误解时可以避免的，只要把修饰语 **for no reason** 放在 **stop** 旁边：

>If the Linear Modules stop for no reason while the machine is working, please do as follows to check the silicone pad inside the modules.

### 1.4.2 多重修饰语

如果某个词或短语前面堆砌了超过两个修饰语，就会看起来不自然。

观察以下结构：

* An English language school teacher
* a recently rented small Council house
* the moving wheel gear casing

虽然从语法上讲，这些表达是可以的，但它们依然看起来很奇怪。如果出现类似这样的情况，先尝试删除修饰语。问一问自己：有必要用这个修饰语吗？它真的有用吗？如果没有，删掉它。

当每个修饰语都提供了不可或缺的信息所以不能省略时，尝试用介词、所有格、连字符或从句来将它们分开。不要让所有修饰语都挤在中心词的前面。所以，不要说:

* The Linear Module motor circuit board
* the upcoming more powerful laser module
* a regularly maintained open source software

而应该说：

* The Linear Module's motor circuit board
* the upcoming laser module that’s more powerful
* a regularly maintained open-source software

### 1.4.3 名词修饰语

不要在中心词前面放超过两个名词修饰语。比如，不要说：

* 3D printing sheet size
* printer work table height

但可以说：

* machine temperature
* Heated Bed temperature
* Z-axis Holder

如果中心词前面有超过两个名词修饰语，则改成所有格形式。比如，可以说:

* the size of 3D Printing Sheet
* the height of printer worktable

基本规则是，在有生命的东西、品牌名后面用 **'s**，而没有生命的物体的所有格用 **of** 来表示。比如，可以说：

* Michel's comment
* Snapmaker's return policy
* The specifications of the machine
* The horsepower of Tesla Model 3

## 1.5 可读性

大部分读者都是带着目的阅读我们的文档的。TA们有可能在找某一个步骤的说明，或者有可能只是在找关于发货日期的说明。不管读者要找什么，精简性和准确性能够减少文档的篇幅以及读者搜寻信息所需要的时间。

### 1.5.1 精简性

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

### 1.5.2 准确性

精简性很重要，但不应该以牺牲准确性为代价。毕竟如果读者不知道你在说什么，文档就成了废纸。

如果你要用多义词，先下定义再用，尤其是在纸质说明书和线上说明书中。常见的易引起歧义的多义词有：

* Shall
* Must
* Need
* Should
* May
* Can

不要用 **shall**，**need** 和 **may**，而应该用 **must**，**should** 和 **can**。如需厘清这几个概念，直接复制下面这段话并粘贴在在适当的地方即可。

>Throughout this document, **must** denotes a requirement. Failure to follow is likely to cause hazards. **Should** denotes strong recommendation. Failure to follow is likely to result in unsatisfactory printing results. **Can** denotes general recommendation, which points to resource sites.

注意 **should** 和 **can** 有双重意义。前者可以代表推荐，也可以用来判断可能性。而 **can** 除了用来应允外，也可以用来判断可能性。鉴于此，这份指南主张用 **be expected to** 而不是 **should** 来表示高可能性，以及用 **be likely to** 而不是 **can** 来表示一般可能性。所以，不要说：

* The machine should return to its original settings.
* Do not reach inside the machine while it is still in operation. An injury can be caused.

而应该说：

* The machine is expected to return to its original settings.
* Do not reach inside the machine while it is still in operation, as it is likely to cause injury.

也有例外。当 **shall** 用在法律性质的条文中时，它时不可替代的。此时应该用 **shall** 而不是 **must** 来表示必须。

避免使用太含糊或太弱的动词，而应该用更具体，更强的动词。比如，不要说：

* There is a sidebar, choose **workspace**. There is a **Connection** icon on the top left. Click the **refresh button**, and the software will reload the serial ports list.
* It is likely to cause a phenomenon called **dust accumulation**.
* You should use the dust plugs to avoid the problem of dust accumulation.
* If you can't find the answer to your question in FAQs, ask help from our support team at support@snapmaker.com and our technical staff will do troubleshooting for you.
* Brim, raft, and skirt are detachable structures for minimizing the problem of object adherence to the Heated Bed.

而应该说：

* From the left sidebar, enter **Workspace**. On the top left, find **Connection** and click the **Refresh** button to reload the serial ports list.
* It is likely to cause dust accumulation.
* Use the dust plugs to avoid dust accumulation.
* If you can't find the answer to your question in FAQs, ask help from our support team at support@snapmaker.com and our technical staff will troubleshoot for you.
* Brim, raft, and skirt are detachable structures for enhancing object adherence to the Heated Bed.

不要自己创造步骤、过程或操作的名称。先查询 **Snapmaker 术语表**。

语法方面，避免使用 **be + Verb (ing)** 来描述未来的事件，而应该用它来表示进行时。如果要描述将来的事件，用 **will + Verb** 的形式。比如，不要说：

>Follow our social media and we are announcing the schedule of the online Makerathon very soon.

而应该说：

>Follow our social media and we will announce the schedule of the online Makerathon very soon.

### 1.5.3 周密性

最重要的信息先说。用有逻辑的架构来组织信息，让读者能用最少的操作和思考获取和理解信息。

注意介词 **after** 和 **only if** 的放置顺序。把先做的操作放在前面，而不是后面。比如，不要说：

>Check whether the Laser Module works properly, after putting on Safety Goggles.

而应该说：

>After putting on Safety Goggles, check whether the Laser Module works properly.

或者说：

>Put on Safety Goggles before you check whether the Laser Module works properly.

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
* We never stop trying. We want you to have the best experience with Snapmaker.
* You can bring your ideas to reality while getting to spend time with your children.

不要预设读者具有背景知识。记得在引入新概念时要介绍背景知识，不管是以连接的形式还是段落的形式。避免说类似 **simply**，**just**，**quickly**，**you are a click away**， 和 **it's easy** 的表述，因为有的操作并不简单，你这么说会让读者有挫败感。


## 1.6 **拼写**

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

### 1.6.1 数字

总体规则是，10 以下的数字应该拼出来，而10及以上的则写成阿拉伯数字。除了以下情况：

* 某个数字在 UI 界面上怎么呈现，就怎么写这个数字。比如，应该说：
    * Work 0 而非 Work zero.
    * Z Offset 而非 Z offset.
* 如果数字 0 可能被误认为是字母 o，则在数字后面用圆括号标注 zero。 比如，应该说
    * Enter 0 (zero) in the bar，而不要说 Enter 0 in the bar。
* 有小数点的数字，即使小于 10，也应该写成阿拉伯数字。 比如，应该说：
    * 3.1 而非 three point one
    * 0.12 而非 zero point twelve
* 后面有计量单位时，写阿拉伯数字。 比如，应该说：
    * -2°C 而非 minus two °C
    * 8 dB 而非 eight dB
    * 5 mm 而非 five mm
* 描述区间时，写阿拉伯数字。 比如，应该说：
    * 2–3 months 而非 two to three months
    * 1–2 minutes 而非 one to two minutes
* 不要用数字开始一个句子，尽量调整结构。如果无法避免，则把数字拼出来，无论数字是否大于 10。比如，应该说：
    * Up till now, 10,000 customers have received their rewards.
    * Ten thousand customers have received their rewards.
    
### 1.6.2 单位

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

## **1.7 语气**

一般而言，正式的语气传递出专业的形象，而非正式的语气则能拉近与读者的距离。写说明书时用正式的语气，而 UX 类的文档可以用轻快一些的语气。

但无论哪一种情况，都要尊重事实以及语气诚恳。避免太具有煽动性的宣传语，夸大其词，和口水话。类似 **empower**, **solution**, **robust**, 和 **reach out to** 的口水话会给人一种装腔作势，懒得思考以及缺乏教养的印象。同时，也要使用正面的语言，强调做到了什么，而非没做到什么。

避免使用表情包，笑话，双关语，网络热词，跨文化传播有障碍的内容，以及涉及宗教的内容。

用第二人称来称呼你的读者。如果要用第三人称，记得使用更加包容的指称，而不是某个特定性别的人称。比如，不要说：

>When operating this machine, user must follow safety instructions in this guide for his own safety. Snapmaker shall not be held responsible if he fails to do so and gets injured.

而应该说：

>When operating this machine, users must follow safety instructions in this guide for their own safety. Snapmaker shall not be held responsible if users fail to do so and get injured.

或者说：

>When operating this machine, persons must follow safety instructions in this guide for their own safety. Snapmaker shall not be held responsible if persons fail to do so and get injured.

用非正式语气时，口吻要平实。偶尔不尊重传统语法没有关系，用介词结句是 ok 的，用 **And** 或 **But** 开始一个句子也是 ok 的。


# 2. 格式和内容规划

连贯的格式是好文档必不可缺的元素。它会加强品牌形象，以及内容创作团队和其他部门的合作。 有逻辑的内容规划则帮助减少重复沟通，以及引导读者去看你想要展示的内容。 本章包含大小写、加注、信息架构、标点和间距的内容。

## **2.1 首字母大写**

首字母的大写分为句子式和标题式。句子式只大写第一个单词的首字母，而标题式则大写所有单词的首字母，除了冠词和短介词的首字母以外。

### 2.1.1 日期和时间

用 12 小时制表示时间。大写 **AM**，**PM**， 以及 **UTC** 中的所有字母。 因此，不要说：

>Opening hours: Monday to Friday 9:30-12:30, 14:30-18:30 (utc+8)

而应该说：

>Opening hours: Monday to Friday 9:30-12:30 AM, 2:30-6:30 PM (UTC+8)

提到 12 点时，要写清楚是中午还是晚上。中午说 **12 noon**，晚上说 **12 midnight**。所有字母小写。

在 UX 类文档写作中，有时需要描述某个只在特定国家开展的活动，比如北美商城的促销，这种情况下 UTC-8 或 UTC-5 这类写法可能会很奇怪。此时，应该用当地常用的时间表示法来描述时间，字母全大写。即使有的国家同时在用好几种时间，我们也只用一种。详见下表。

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


### 2.1.2 文件名后缀

在句子中间用大写表示文件名后缀，在句子末尾则用 **.小写后缀** 的形式。比如，不要说：

* Download the pdf of the User Manual.
* Upload your jpg model file.
* The extension of the file is gcode.

而应该说：

* Download the PDF of User Manual.
* Upload your JPG model file.
* The extension of the file is .gcode.

### 2.1.3 列表

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

### 2.1.4 注解

**Note:** **Tips:** **Caution:** 和 **Warning:** 后面的句子首词用句子式大写。比如，不要说：

>Note: if your machine is not responding, check A, B, and C.

而应该说：

>Note: If your machine is not responding, check A, B, and C.

### 2.1.5 专有名词

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

### 2.1.6 表格中的文字

在表格中，表头（纵向最上和横向最左）文字都用标题式，其余文字的处理同正文。类似这样：

|    |**Standard Deviation**|**Standard Error**|**Decision**|
|:----|:----|:----|:----|
|**Treatment A**|1.76643 (low)|0.233|PASS|
|**Treatment B**|4.76423 (too high)|1.232|FAIL|
|**Treatment C**|3.78789|0.467|TO BE CONFIRMED|



### 2.1.7 题目和标题

题目和各级标题用标题式大写，所以你需要大写名词、动词、代词、形容词和副词的首字母。注意，5 个及以上字母构成的介词和连词也需要大写首字母。但是，除非是题目或标题的第一个或最后一个词，以下词语不要大写：

* 由 4 个及以下字母构成的介词或连词；
* 冠词，无论是定冠词还是不定冠词。

所以，不要说：

* Set up your Workshop  
* The Heoroes That Walk among Us
* Easy To Assemble
* All For Your Best Experience
* Connect With Us
* Sleek Yet Powerful
* Modular And Expandable
* a Change to Look Forward to

而应该说：

* Set up Your Workshop  
* The Heoroes That Walk Among Us
* Easy to Assemble
* All for Your Best Experience
* Connect with Us
* Sleek yet Powerful
* Modular and Expandable
* A Change to Look Forward To


### 2.1.8 单位

所有计量单位的所有字母都用小写，除了以下情况：

* Decibels (dB)
* Celsius degree (°C)
* Fahrenheit degree （°F)
* Milliwatt (mW)
* Megawatt (MW)


## 2.2 **加注**

### 2.2.1 注解

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

### 2.2.2 强调和提及

强调动作，或提及书名、电影名之类时用粗体。不要大写所有字母，不要用冒号，引号，斜体，下划线，右上角字体或感叹号来做强调。 比如，不要说：

>Tap "Controls" on the Touchscreen, and tap "Home Axes" to run a homing session.
>或者：

>Tap *Controls* on the Touchscreen, and tap *Home Axes* to run a homing session.

而应该说：

>Tap **Controls** on the Touchscreen, and tap **Home Axes** to run a homing session.

另外，提及 UI 上的元素时用粗体。如果增加 UI 上的符号能帮助理解，也可以和粗体一起使用。比如，可以说：

>Enter **Workspace**. On the top left, find **Connection** and click the **Refresh** button to reload serial ports list.

## **2.3 信息架构**

### 2.3.1 标题

不要在标题前面加序号，除非此标题是某个有序操作的一个步骤。各级标题之间用格式来做区分，而不要用数字。

只用 1-3 级标题，避免使用 4-5 级标题。标题层级太多会影响阅读体验。

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

另外，和可读性原则里提到的要求一样，不要用俚语、行话或另一种语言来给标题命名。

### 2.3.2 链接

在 UX 类文档写作中，如果要加入链接，把链接加在关键词下面，而不要单独放出来。在非 UX 类的写作中，用介词 **at** 或 **from** 来引出链接，而不要用冒号。如果链接太长，就重新组织语言，把链接放在一行内。

### 2.3.3 列表

尽量避免嵌在句子当中的列表。如果你的写作中有好几个有共同之处的对象，用列表把它们列出来，这有利于快速浏览。举个例子，以下这个句子包含一个内嵌的列表：

>Snapmaker A350 and Luban let you customize your own design by adding support, adhesion and surface, generate a G-code and export it to your PC, send files to the machine via Wi-Fi, and stop the machine when an error occurs.

如果把内嵌列表里的对象单独列出来，这个句子会更易读：

Snapmaker A350 and Luban let you:

* Customize your design by adding:
    * support
    * adhesion
    * surface
* Generate G-code.
* Export G-code to your PC.
* Send files to the machine via Wi-Fi.
* Stop the machine when an error occurs.

有序列表在迁移时可能会导致格式错乱，而子弹型列表不会。因此，仅在描述步骤时使用有序列表，其他时候使用无序列表。

### 2.3.4 表格

用表格来做对比。不要用它来描述术语、步骤或报告系统更新情况。

不要给表格起名字，因为迁移时可能会造成混乱。表格应该紧邻其介绍段。

表头内容用粗体。


## **2.4 标点**

### 2.4.1 和符号（&）

除非必要，避免使用此符号来替代 **and**。

### 2.4.2 角括号 (>)

当有篇幅限制而不能用分行的段落来解释某个操作时，可以用角括号来连接一些比较小的步骤。不要用 **->**, **-->**, **--**, 或 **—→**。所以，不要说：

* You can enter Home -> Enclosure -> Settings to disable Door Detection.
* You can enter Home --> Enclosure --> Settings to disable Door Detection.
* You can enter Home —→ Enclosure —→ Settings to disable the Door Detection.

而应该说：

* You can enter **Home** > **Enclosure** > **Settings** to disable Door Detection.

### 2.4.3 星号（\*）

加脚注用星号. 见 Notation 一节.

### 2.4.4 冒号（:）

以下情况使用冒号：

* 添加注释
* 介绍联系方式

正文中，用 **at** 而不要用 **:** 或者 **at:** 来介绍联系方式。在 **Contact Us**，**Support**，**Detail** 页面和网站主页的最下角，用冒号来介绍联系方式。

不要在 **including**，**excluding**，**except for**，**other than**，**apart from**，**such as**，和 **for example** 的后面加冒号。

### 2.4.5 逗号（,）

以下情况使用逗号：

* 内嵌列表中，**and** 前面
* 祈使句中，**and** 前面
* 复杂句中，作状语的分词前面
* 复合句中，连词前面
* 同一个句子中有两个问题，**or** 前面
* **too**，**neither**，**either** 前面
* 超过三位的数字中，从右往左，每三个数字之间。

比如，不要说：

* We represent detail-orientedness, creativity and passion.
* Before using CNC carving put on safety goggles.
* Take off the dust plugs and you will see the USB port.
* You will make your Snapmaker more versatile adding the latest Rotary Module.
* Have you ever wondered: do I buy a 3D printer? Or do I buy a 3-in-one fabrication machine?
* We feel disheartened by this terrible news too.
* 2100 mm

而应该说:

* We represent detail-orientedness, creativity, and passion.
* Before using CNC carving, put on safety goggles.
* Take off the dust plugs, and you will see the USB port.
* You will make your Snapmaker more versatile, adding the latest Rotary Module 或者——
* Adding the latest rotary module, you will make your Snapmaker more versatile.
* Have you ever wondered: do I buy a 3D printer, or do I buy a 3-in-one fabrication machine?
* We feel disheartened by this terrible news, too.
* 2,100 mm

### 2.4.6 省略号（...）

英文省略号是三个句号，用来表示省略或犹豫。不要用。

### 2.4.7 En dash（–）
此符号比连字符稍长。用 en dash 来表示区间，而不要用波浪线 **~** 。比如，不要说：

>Operating Temperature	-20℃ ~ 50℃ (-4°F~122°F)

而应该说：

>Operating Temperature	-20℃–50℃ (-4°F–122°F)

打 en dash 的方式如下：

* 如果是 Mac 键盘，同时按下 **Alt** 键和 **减号（-）** 键。
* 如果是 Windows 键盘, 同时按下 **开始** 键和 **句号（.）** 键，点击上方的 **omega** 符号，下拉可找到 en dash。

### 2.4.8 Em dash （—）
此符号是 en dash 的两倍长. 用 em dash 来表示对话，和在文本中加说明。

打 em dash 的方式如下：

* 如果是 Mac 键盘，同时按下 **Alt** 键，**Shift** 键，和 **减号（-）** 键。
* 如果是 Windows 键盘, 同时按下 **开始** 键和 **句号（.）** 键，点击上方的 **omega** 符号，下拉可找到 em dash。

### 2.4.9 感叹号（!）
少用。

### 2.4.10 连字符（-）

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

### 2.4.11 乘号 (×)

描述产品尺寸时，可以用乘号连接几个数字。但注意，除非有空间限制，否则不要省略每个数字后面的单位。所以，不要说：

> Dimensions (W × D × H): 405 × 424 × 490 mm

而应该说：

> Dimensions (W × D × H): 405 mm × 424 mm × 490 mm

### 2.4.12 括号 ()

少用。如果删除括号内的内容不影响句子意思的完整性，不要用。

### 2.4.13 句号（.）

没有停顿的长篇大段是很难读的。以下是一个极端的案例：

>Keep adjusting the height of the nozzle using **Up** and **Down** buttons until there is slight resistance when you pull out the calibration card and it should be wrinkled when you push it forward.

加上一些逗号和句号，整个段落会更好理解：

>Keep adjusting the height of the nozzle using **Up** and **Down** buttons, until there is slight resistance when you pull out the calibration card. When you push it forward, the card should be wrinkled.

用句号，而不是逗号来连接两个完整的句子。比如，不要说：

>Cut the bending end of the filament using the diagonal pliers, then insert the filament into the 3D Printing Module.

而应该说：

>Cut the bending end of the filament using the diagonal pliers. Then insert the filament into the 3D Printing Module.

如果一个句子由一个链接结束，别忘了在链接后面打句号。

不要在题目和标题结尾打句号，即使它们读起来是完整的句子。

### 2.4.14 双引号（""）

不要用双引号来提及UI里面的元素，用粗体。如果需要引用一个整段，用 markdown 语法，而不要用双引号或单引号。

### 2.4.15 分号（;）

两个完整句子之间如果意思相近，用分号连接。否则用句号。此外，需注意 **then**，**therefore**，**otherwise**，以及 **namely** 是副词。所以应该用分号而不是逗号把它们和前一个句子隔开。或者，在它们前面加上连词。比如，不要说：

>The firmware is updated on 8th September, therefore if you use the previous version, you may experience delays.

而应该说：

>The firmware is updated on 8th September; therefore if you use the previous version, you may experience delays.

### 2.4.16 斜杠（/）

不要用斜杠来代替 **or**。如果非用不可，也不要多个并排用，因为大部分情况下可以用逗号替代多个斜杠。比如，不要说：

>You can recover any project and get perfect printing / engraving / cutting / carving results at any time.

而应该说：

>You can recover any project and get perfect printing, engraving, cutting, or carving results at any time.

不要用斜杠来间隔日期和时间。用连字符来间隔年月日，用冒号来间隔时分秒。比如，不要说：

>We will host an orientation on 07/12/2020. Don't miss it!

而应该说：

>We will host an orientation on Monday, December 7th, 2020. Don't miss it!

避免使用反方向的斜杠。

## **2.5 间距**

间距不对有可能会造成误解，并且给人不专业的印象。

遵循以下原则：

* 数字和单位之间空一格。但在某些情况下，单位不是其英文的缩写，而是一个符号，比如 **°**（度）、**'**（英尺）或 **"** (英寸)，这种情况下数字和单位之间不需要空格。另一个例外是产品命名，这种情况下数字与单位之间不空格。
* 切换语言时，引入语和主体语言之间空一格。
* 两个段落之间空一行。

比如，不要说：

* As a desktop 3D printer, F250 offers a 320 × 350 × 220mm work area.
* The module stops working automatically whenever its temperature sensor detects a higher than normal (one that exceeds 55 ℃/131 ℉) working temperature.
* Bring them to life now with the right tool: the 10 W High Power Laser Module.
* This inevitably gives rise to what we call知之者胜，不知之者不胜in Chinese.

而应该说：

* As a desktop 3D printer, F250 offers a 320 × 350 × 220 mm work area.
* The module stops working automatically whenever its temperature sensor detects a higher than normal (one that exceeds 55℃/131℉) working temperature.
* Bring them to life now with the right tool: the 10W High Power Laser Module.
* This inevitably gives rise to what we call 知之者胜，不知之者不胜 in Chinese.

有标点时，注意它们与文字前后的间距。 一般而言，在标点后面，文字前面空一格。除了以下情况：

* 斜杠或连字符与文字之间不空格。
* 如果括号结束一个句子，左括号前空一格，右括号和句号之间不空格。
* **&** 符号前后各空一格。
* 乘号前后各空一格。

如果你要用拼音，不要在同一个词的拼音内加空格。
