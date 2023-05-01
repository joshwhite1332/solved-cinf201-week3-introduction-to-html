Download Link: https://assignmentchef.com/product/solved-cinf201-week3-introduction-to-html
<br>
<h1>Overview</h1>

This week we will learn about HTML and how it is used to establish a structure for our website. After reviewing information about HTML elements and tags, students will build a basic web page and submit it for review. By the end of this week, students will be able to identify various tags and use them on a web page.

<strong>What is HTML? </strong>

There are three major components of front-end web development:

<ol>

 <li>Structure</li>

 <li>Style</li>

 <li>Interactivity</li>

</ol>

HTML stands for HyperText Markup Language and represents the structure of a web page. It is based on the concept of tags that “markup” the document. Those tags allow the browser to interpret .html files and present them correctly to users on the page. Each tag begins and ends with an angled bracket.




<h2>&lt;p class=“para”&gt;This is a paragraph.&lt;/p&gt;</h2>




The bold text directly above is an HTML element. Elements are made up of tags, attributes, values, and content. The &lt;p&gt; and &lt;/p&gt; parts are the starting and ending tags. “class” is the attribute and “para” is the value you are providing for the attribute. Everything between the starting and ending tags is the content.

Those 4 parts are what makes up the content for pages on the internet. Since every web page is just text and images, you can view the source of the code at any time. To do so, right-click a web page and select “View Source” or “Inspect Element.”

View Source will usually bring up a separate web page with all the HTML being used. Inspect Element will pull up your browser’s web developer tools and the object you clicked on the page will be highlighted. I would recommend doing this activity in Google Chrome as it has some very powerful tools for working with websites.

In HTML, some tags require ending tags and others do not. &lt;p&gt;, &lt;div&gt;, &lt;span&gt;, &lt;strong&gt;, &lt;em&gt;, and many others require a closing tag which looks like the following: &lt;/tag&gt;

“Tag” is replaced by the name of the tag. &lt;br&gt;, &lt;hr&gt;, and &lt;img&gt; are examples of tags that don’t require a closing tag and can be written without any slashes.

Tags in HTML are often nested within each other. An example is &lt;ul&gt; and &lt;li&gt;. &lt;ul&gt; is unordered list and &lt;li&gt; is list item and they appear together as shown below.

&lt;ul&gt;

&lt;li&gt;Item 1&lt;/li&gt;

&lt;li&gt;Item 2&lt;/li&gt;

&lt;/ul&gt;




Tags can be nested over and over, but you want your HTML to be tidy and should code in a way that allows you to keep your code uncluttered. If you open a tag inside of another tag, you must close it unless it doesn’t require a closing tag.

Using semantic markup to organize content and ensuring that your tags are closed correctly are important for making your website more accessible. Many users access the web in a variety of ways and inaccessible websites prevent them from receiving the same quality of services or information.

The table below contains some very common HTML tags along with an explanation of their purpose. Most of these tags are ones you may have seen before, but it doesn’t include some of the newer semantic tags in HTML 5.

<table width="612">

 <tbody>

  <tr>

   <td width="126"><strong>Tag Name </strong></td>

   <td width="486"><strong>Purpose </strong></td>

  </tr>

  <tr>

   <td width="126">&lt;!Doctype html&gt;</td>

   <td width="486">Not really an HTML tag but more like information for the browser about what type of document it should expect. This one is for the latest version of HTML, which is HTML 5, and is the only acceptable one for this course. It always comes first in an HTML document and doesn’t have an end tag.</td>

  </tr>

  <tr>

   <td width="126">&lt;html&gt;</td>

   <td width="486">This is the root of an HTML document and should wrap all other HTML elements. You should always use the lang attribute with this tag to define your web page’s language. This is helpful for search engines/browsers.</td>

  </tr>

  <tr>

   <td width="126">&lt;head&gt;</td>

   <td width="486">This is the head of an HTML document and typically contains information about the document inside of metatags. Things in this tag do not appear on the web page.</td>

  </tr>

  <tr>

   <td width="126">&lt;title&gt;</td>

   <td width="486">This is the title of an HTML document and the content inside of the tags usually appears in the tab of the browser window. It goes inside of the &lt;head&gt; tag and is required for all HTML documents.</td>

  </tr>

  <tr>

   <td width="126">&lt;body&gt;</td>

   <td width="486">This defines the body of an HTML document. Elements inside of this tag will appear on the page.</td>

  </tr>

  <tr>

   <td width="126">&lt;h1&gt; – &lt;h6&gt;</td>

   <td width="486">Defines headings in a document. h1 is the most important while h6 is the least important. In general, only one h1 should be used per page.</td>

  </tr>

  <tr>

   <td width="126">&lt;p&gt;</td>

   <td width="486">Defines a paragraph.</td>

  </tr>

  <tr>

   <td width="126">&lt;ul&gt;</td>

   <td width="486">Unordered list. This will display a list with bullet points as the default style.</td>

  </tr>

  <tr>

   <td width="126">&lt;ol&gt;</td>

   <td width="486">Ordered list. This will display a list with numbers as the default style.</td>

  </tr>

  <tr>

   <td width="126">&lt;li&gt;</td>

   <td width="486">List item. This tag goes inside of &lt;ul&gt; and &lt;ol&gt; tags to display a single item.</td>

  </tr>

  <tr>

   <td width="126">&lt;em&gt;</td>

   <td width="486">Defines emphasized text that is displayed in <em>italic</em>.</td>

  </tr>

  <tr>

   <td width="126">&lt;strong&gt;</td>

   <td width="486">Defines text with strong importance and is usually displayed in <strong>bold</strong>.</td>

  </tr>

  <tr>

   <td width="126">&lt;table&gt;</td>

   <td width="486">Defines a table in a document. This must contain tr and th/td tags at the very least.</td>

  </tr>

  <tr>

   <td width="126">&lt;thead&gt;</td>

   <td width="486">Used to group header content in a table. It is normally used for the first row of a table.</td>

  </tr>

  <tr>

   <td width="126">&lt;tbody&gt;</td>

   <td width="486">Used to group the body content in an HTML table. If there is no footer for the table, this is used for the rest of the rows in a table.</td>

  </tr>

  <tr>

   <td width="126">&lt;tr&gt;</td>

   <td width="486">Defines a row in a table. It must contain th or td tags inside of it for columns</td>

  </tr>

  <tr>

   <td width="126">&lt;th&gt; or &lt;td&gt;</td>

   <td width="486">Defines a column in a table. &lt;th&gt; should be used for the first row in a table (which should be in a &lt;thead&gt; tag) while &lt;td&gt; should be used in rows after that (those rows should be in a &lt;tbody&gt; tag).</td>

  </tr>

  <tr>

   <td width="126">&lt;br&gt;</td>

   <td width="486">Defines a line break and is used to break text content apart. This tag does not have an end tag.</td>

  </tr>

  <tr>

   <td width="126">&lt;hr&gt;</td>

   <td width="486">Horizontal rule. This will display a horizontal line across the screen. This tag does not have an end tag.</td>

  </tr>

  <tr>

   <td width="126">&lt;img&gt;</td>

   <td width="486">Displays an image. This tag requires two attributes which are src and alt. Src is used to define the source of the image whether it’s a local image or something on the internet. The alt attribute is important for accessibility and is used to describe the image for visually impaired users or screen readers. This tag does not have an end tag.</td>

  </tr>

  <tr>

   <td width="126">&lt;div&gt;</td>

   <td width="486">Defines a division or section in a web page. It is a container, and all kinds of tags can be placed inside of it. It is typically used with CSS to change the layout of a page.</td>

  </tr>

  <tr>

   <td width="126">&lt;span&gt;</td>

   <td width="486">Like a div, this is also a container. However, this is an inline container which is typically used to mark up a piece of text in a document. An empty div will take up the whole width of a screen while a span tag only takes up the width of the content inside of it.</td>

  </tr>

  <tr>

   <td width="126">&lt;form&gt;</td>

   <td width="486">Defines a form for user input. It can contain a number of tags including &lt;label&gt;, &lt;input&gt;, &lt;textarea&gt;, and &lt;button&gt;.</td>

  </tr>

  <tr>

   <td width="126">&lt;label&gt;</td>

   <td width="486">Defines a label for another HTML element. These are required for forms because it helps with accessibility for all types of users.</td>

  </tr>

  <tr>

   <td width="126">&lt;input&gt;</td>

   <td width="486">Defines an input area for users. The input can come in many types of way depending on the “type” attribute paired with the input tag. This tag does not have an end tag but requires a type attribute to define the input expected.</td>

  </tr>

  <tr>

   <td width="126">&lt;button&gt;</td>

   <td width="486">Defines a button in a web page. This is typically used with a form to submit user input. The type attribute is necessary to let browsers know what type of button it is.</td>

  </tr>

 </tbody>

</table>




<strong>How do we use HTML on a page? </strong>

To use HTML, we need a text editor and some code. In the lecture notes for this week, I’ve provided a file called html-template.html. Feel free to use this file for assignments, project work, etc. I will be using this file to do a live demonstration for all of you. Please follow along as I type things out on the screen. I would recommend making a copy of the html-template file and renaming/keeping it in a place you can access it.

Besides html-template.html, I’ve provided a html-1-example file which contains most of the code I’ll be writing for the demonstration. Since I tend to improvise, this file contains more generalized information with explanations. If you fall behind during my demonstration, refer to the code in this example file as it will be roughly the same.




<h2>Resources/Online Documents</h2>

<u>Tutorials</u>

<u>https://www.htmldog.com/guides/html/</u>

<u>https://html.com/</u> (Read up until “Our Other HTML Tutorials” and that should suffice) <u>https://www.codecademy.com/learn/learn-html</u> (Interactive, full-blown tutorial – you <strong>DO NOT</strong> have to complete this, but if you want to learn on the side, it helps)




<u>Reference Guides</u>

<ul>

 <li><u>https://html.spec.whatwg.org/multipage/</u> (very technical guide to the whole specification)</li>

 <li><u>https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5</u></li>

 <li><u>http://html5doctor.com/element-index/</u></li>

</ul>




<h1>First HTML Exercise (CW)</h1>

Your task is to build a webpage based on requirements given to you. To start this assignment, get the “html-exercise.html” file from this week’s lecture notes zip folder and open it up in a text editor. This file is also attached to the assignment submission area as well. Add code to the HTML file as described below. All code should be submitted as one HTML file to Blackboard for credit. Almost all the content you’ll add to the file will go between the &lt;body&gt; &lt;/body&gt; tags.




<ol>

 <li>Fill in the title tag with a title for your webpage</li>

 <li>Add an h1 tag with “HTML Exercise” between it</li>

 <li>Add a p tag beneath that with a sentence or two about a place you would like to go to for vacation. When you mention the name of the place, wrap it in a strong tag so that it appears bold on the page.</li>

 <li>Create an <strong>unordered list</strong> with 5 foods you like. Use em tags to make two of your favorite items on that list appear italicized on the page.</li>

 <li>Create an <strong>ordered list</strong> with your three favorite websites. Use the a tag and href attribute to hyperlink those websites so I can visit them.</li>

 <li>Add another list (unordered or ordered) inside of this list with 2 pages from that website. I’ve provided an example using the NYTimes as the website I chose. You do not have to link the pages in the a tag. You can use “#” for the value of the href attribute and just provide the link text between the tags.</li>

</ol>




<h2>Example for #4</h2>

<ul>

 <li>com</li>

 <li>com</li>

 <li>com

  <ul>

   <li>https://www.nytimes.com/section/science</li>

   <li>https://www.nytimes.com/section/opinion?pagetype=Homepage&amp;action=click&amp; module=Opinion</li>

  </ul></li>

</ul>




<ol start="6">

 <li>Add an image (make sure to fill out the alt tag)

  <ol>

   <li>The image can be from a local source or online. However, if you use a local image, you must submit the image with your file so I can see it.</li>

  </ol></li>

 <li>Add an hr tag beneath the image so that a line appears next</li>

 <li>Recreate the table below in HTML (don’t worry about providing real links or styles)

  <ol>

   <li>Make sure to use tbody, thead, tr, th, and th tags</li>

  </ol></li>

</ol>




<table width="623">

 <tbody>

  <tr>

   <td width="152"><strong>Name </strong></td>

   <td width="152"><strong>Species Type </strong></td>

   <td width="153"><strong>Favorite Food </strong></td>

   <td width="166"><strong>Email </strong></td>

  </tr>

  <tr>

   <td width="152">Chris</td>

   <td width="152">Human</td>

   <td width="153">Bacon</td>

   <td width="166"><u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="4a293c2f262f300a2b26282b2433642f2e3f">[email protected]</a></u></td>

  </tr>

  <tr>

   <td width="152">Scooby Doo</td>

   <td width="152">Dog</td>

   <td width="153">Scooby Snacks</td>

   <td width="166"><u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="285b4c4747684b47474445494144064b4745">[email protected]</a></u></td>

  </tr>

  <tr>

   <td width="152">Garfield</td>

   <td width="152">Cat</td>

   <td width="153">Lasagna</td>

   <td width="166"><u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="53343221353a363f3713303c3c3f3e323a3f7d303c3e">[email protected]</a></u></td>

  </tr>

 </tbody>

</table>


