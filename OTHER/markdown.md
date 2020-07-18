---
title: "MARKDOWN"
tags: ""
---

# Markdown notes

#### Automatic escaping from special character

-   If you  want to write about ‘AT&T’, you need to write ‘AT&T’.

        	&copy

        	4 < 5  

### Block elements

#### Paragraphe and line break

A paragraph is simply one or more consecutive lines of text, separated by one or more blank lines

When you do want to insert a <br /> break tag using Markdown, you end a line with two or more spaces, then type return.

#### Headers

SetText-style

    This is an H1	
    =============

    This is an H2
    -------------

Atx-style

    # This is an H1

    ## This is an H2

    ###### This is an H6

#### Blockquotes

    > this is a block quote
    > >  Blockquotes nested

> example

#### Lists

Unordered list

    * Red
    * Green

    + Red
    + Green

    - Red
    - Green

Ordered list

    1.  Bird
    1.  McHale
    1.  Parish

you can backslash-escape the period to block it:

    1986\. What a great season.

#### Code blocks

    This is a normal paragraph:

    	This is a code block.
        

#### Horizontal rules

    * * *
    ***
    *****
    - - -

#### Span elements

##### Links

    This is [an example](http://example.com "Link title")  
    [this link](http://link)

If you’re referring to a local resource on the same server, you can use relative paths:

    See my [About](/about/) page for details.   

Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:

    This is [an example][id] reference-style link.

Then, anywhere in the document, you define your link label like this, on a line by itself:

    [id]: http://example.com/  "Optional Title Here"

The following three link definitions are equivalent:

    [foo]: http://example.com/  "Optional Title Here"
    [foo]: http://example.com/  'Optional Title Here'
    [foo]: http://example.com/  (Optional Title Here)

> ##### Notes:
>
> Just use an empty set of square brackets
>
>     [Google][]
>
> And then define the link:
>
>      [Google]: http://google.com/
>
> > Link definitions can be placed anywhere in your Markdown document.
>
> Here’s an example of reference links in action:
>
>     I get 10 times more traffic from [Google] [1] than from
>     [Yahoo] [2] or [MSN] [3].
>
>      [1]: http://google.com/        "Google"
>      [2]: http://search.yahoo.com/  "Yahoo Search"  
>      [3]: http://search.msn.com/    "MSN Search"

#### Emphasis

    *single astherix*  
    **double astherix**   
    _single underscore_  
    __double underscore__    

_single astherix_  
**double astherix**  
_single underscore_  
**double underscore**    

    \*this text is surrounded by literal asterix\*

\*this text is surrounded by literal asterix\*

#### Code

    Use the `printf()` function

Use the `printf()` function

    ``There is a literal backtick (`) here.``

``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

#### Image

    ![Alt text](/path/to/img.jpg)
    ![Alt text](/path/to/img.jpg "Optional title")

That is:

-   An exclamation mark: !;
-   followed by a set of square brackets, containing the alt attribute text for the image;
-   followed by a set of parentheses, containing the URL or path to the image, and an optional title attribute enclosed in double or single quotes.

Reference-style image syntax looks like this:

    ![Alt text][id]
    [id]: url/to/image  "Optional title attribute"

#### Automatic Links

    <http://example.com/>

Automatic links for email addresses work similarly,

    <address@example.com>

#### Backslash escapes

    \*literal asterisks\*

Markdown provides backslash escapes for the following characters:

    \   backslash
    `   backtick
    *   asterisk
    _   underscore
    {}  curly braces
    []  square brackets
    ()  parentheses
    #   hash mark
    +   plus sign
    -   minus sign (hyphen)
    .   dot
    !   exclamation mark
