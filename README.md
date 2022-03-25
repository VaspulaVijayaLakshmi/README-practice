# README-practice
Practice writing readme files

> Refer to this page for comprehensive guide for writing README files:
>> https://www.markdownguide.org/basic-syntax/#blockquotes-1



# Heading

# H1
## H2
### H3

***

# Font style

**bold text**

*Itlaian*

***


# Blockquote


> blockquote

Blockquotes can be nested. <br/>
Add a >> in front of the paragraph you want to nest.

eg:
> this is text in block quotes
>> this is nesting



***

<br/>

# Lists
You can organize items into ordered and unordered lists.
1. First item
2. Second item
3. Third item
4. Fourth item

***

# Unordered Lists

To create an unordered list, add dashes (-), asterisks (*),
or plus signs (+) in front of line items. <br/>
Indent one or more items to create a nested list.


- First item
+ Second item
* Third item
 - Indented item
    - Indented item


***


1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item



***

# Blockquotes + lists

* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.







# Horizontal Rules
To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

***

---

_________________



***


# Links

To create a link, enclose the link text in brackets (e.g., [placeholder of link]) and then follow it immediately with the URL in parentheses
(e.g., (https://duckduckgo.com)).

My favorite search engine is [leetcode](https://leetcode.com/problem-list/top-interview-questions/).

***


# Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document,
add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.


***


# Images


To add an image, 
1. add an exclamation mark (!)
2. followed by alt text in brackets
3. the path or URL to the image asset in parentheses.
4.  You can optionally add a title in quotation marks after the path or URL.

![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg )

(or)

![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")






# Linking Images

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)


this is for link     \[]()

this is for image   \!\[]() 

so for link into image \[ \!\[]() ]()
