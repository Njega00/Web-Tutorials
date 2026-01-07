#This is a html file . 
# In Html the <!DOCTYPE html> declaration defines this document to be HTML5
# The doctype is not case sensitve and it is recommended to always write it in uppercase.
# The <html> element is the root element of an HTML page
# The <head> element contains meta information about the document
# The <head> element contains the metadata / information for the document
# The <title> element specifies a title for the document
# The <body> element contains the visible page content
    # Using headings 
    # Single line comments are written using the hashtag symbol (#)
    # Below is an example of a multiline comments used in the rest of this tutorial.
    <!--
    Deﬁning a heading:
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
    
<h1> deﬁnes the most important heading.
<h6> deﬁnes the least important heading.

    Example document (extra intendation to illustrate hierarchy):
<h1>Main title</h1>
<p>Introduction</p>
<h2>Reasons</h2>
<h3>Reason 1</h3>
<p>Paragraph</p>
<h3>Reason 2</h3>
<p>Paragraph</p>
<h2>In conclusion</h2>
<p>Paragraph</p>

The HTML <p> element deﬁnes a paragraph: 
    <p>This is a paragraph</p>
    <p>This is another paragraph</>
        Usng spaces within the paragraph in between texts does not add spaces , instead use <br> to add lines

        Text Formatting
        This involves formatting text such as highlighting, bolding ,underlining,subscript and sticken text
        <mark> is used to highlight text in a document "due to its relevance in another context"</mark>

        To bold use <strong>Bold text here </strong> or <b>Bold text here also</b>
        strong indicates that is is fundamentally /semantically important than the others

        Italic text uses <em> or <i> tags
            <em>This indicates that the text has extra emphasis</em>

            Underlined text uses <u>The above would be unerlined</u>

            To mark some expression as an abbreviation, use <abbr> tag:
<p>I like to write <abbr title="Hypertext Markup Language">HTML</abbr>!</p>

To mark text as inserted, use the <ins> tag:
<ins>New Text</ins>
To mark text as deleted, use the <del> tag:
<del>Deleted Text</del>
To strike through text, use the <s> tag:
<s>Struck-through text here</s>

Anchors and hperlinks
href -- it specifies the destination address , it can be an absolute or relative url or the name of the anchor
//An absolute url points to the complete url of a website , a relative url points to another dir , doc inside the same document

hreflang -- specifies the language used
rel -- specifies the relationship between the current document and the linked document.
target -- specifies where to open the new tab / window
We also have the attributes like title and download.*target is not recommended as it violates the control of the user over a website 

Linking to another site 
This is the basic use of the <a> anchor element tag
    <a href="https://example.com" rel "external">Link to example.com </a> We can use the external link type to denote that the link leads to an external website.

    Linking to an anchor 
    Anchors are mainly used to jump to specific tags on an htmlpage 

    Anchors are mostly used with classes and ids . below is an an example

<h2>First topic</h2>
<p>Content about the first topic</p>
<h2>Second topic</h2>
<p>Content about the second topic</p>

<h2 id="Topic1">First topic</h2>
<p>Content about the first topic</p>
<h2 id="Topic2">Second topic</h2>
<p>Content about the second topic</p>


<h1>Table of Contents</h1>
<a href='#Topic1'>Click to jump to the First Topic</a>
<a href='#Topic2'>Click to jump to the Second Topic</a>
Remember, you can always <a href="page1.html#Topic1">look back in the First Topic</a> for
supporting information.

Link to a page on the same site . We use a relative url for this .. example <a href= "/page">Text her</a>


we use the target attribute to specify where the url is going to open eg target = "_blank" which opens on a new tab/window per user preference 

SECURITY VULNERABILITY WARNING!
Using target="_blank" gives the opening site partial access to the window.opener object via JavaScript,
which allows that page to then access and change the window.opener.location of your page and
potentially redirect users to malware or phishing sites.
Whenever using this for pages you do not control, add rel="noopener" to your link to prevent the
window.opener object from being sent with the request.
Currently, Firefox does not support noopener, so you will need to use rel="noopener noreferrer" for
maximum eﬀect.

the links can also be used with phone numbers, running javascript, and in mails

Lists

Ordered lists
<ol>
<li>Item</li>
<li>Another Item</li>
<li>Yet Another Item</li>
</ol>
by default they use the numbered list
Using the attributes we can modify the listing

The attributes in the <li> overide the <ol> atttributes if they have similar functionality but different values

    Unordered lists
    <ul>
        <li>Item</li>
         <li> Aother Item</li>
          <li>Yet Another Item</li>
    </ul>
        The defaultwill produce a bulleted list

        Nested Lists
<ul>
<li>item 1</li>
<li>item 2
<ul>
<li>sub-item 2.1</li>
<li>sub-item 2.2</li>
</ul>
</li>
<li>item 3</li>
</ul>

Tables
They allow authors to display tabular data in a two dimentional table with rows and columns

An example is as shown below

<table>
<tr>
<th>Heading 1/Column 1</th>
<th>Heading 2/Column 2</th>
</tr>
<tr>
<td>Row 1 Data Column 1</td>
<td>Row 1 Data Column 2</td>
</tr>
<tr>
<td>Row 2 Data Column 1</td>
<td>Row 2 Data Column 2</td>
</tr>
</



    -->