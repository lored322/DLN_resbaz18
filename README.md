# DLN_resbaz18
Digital lab notebook test in resbaz July 2018 Dunedin

## DLN_resbaz18

### DLN_resbaz18

###### DLN_resbaz18

DLN_resbaz18
============

DLN_resbaz18
------------

Markdown Syntax
========

## Text decoration

**bold** *italics* ~strikethrough~

OR 

__bold__ _italics_

OR if you're feeling fancy

**_bolded italics_**

No underline... deal with it peeps

-----------------------------------

## Bullet points etc

### Bullet points

Making a list of stuff:
* stuff1
* stuff2
* stuff3

OR

Making another list of stuff:
- stuff4
- stuff5
- stuff6

Looks exactly the same

### Numbered lists:
1. the first thing
1. second
1. third

### Special List (Github only) - Checklist

To-do and done:
- [ ] one
- [ ] two
- [x] three

### Nesting lists

Lists within lists:
* one thing
  * sub thing
* two thing
  * sub thing two
  * sub thing two two
* three thing

## Tables

Making tables with Markdown

| Name | Age | Department | Job |
|---|---|---|---|
|Riku|25|Biochemistry|ARF|
|Ruth|34|Biochemistry|ARF|
|Mik|old|Biochemistry|StatsGuy|

Default centre aligns column names, left aligns everything else

Centre aligning Job column

| Name | Age | Department | Job |
|---|---|---|:---:|
|Riku|25|Biochemistry|ARF|
|Ruth|34|Biochemistry|ARF|
|Mik|old|Biochemistry|StatsGuy|

Use a single colon on left or right to left or right align things

-------

## Markdown Paragraphs, Text and quotes

### Paragraphs

This has singe white spaces between the words.
However,  this  sentence  has  double  or triple   spaces     for lols                     .

But markdown condenses into single space (because its sensible, unlike word).

This is a paragraph. It has lots of words. And lots of sentences. This is a paragraph. It has lots of words. And lots of sentences. This is a paragraph. It has lots of words. And lots of sentences. This is a paragraph. It has lots of words. And lots of sentences. This is a paragraph. It has lots of words. 

And lots of sentences. This is a paragraph. It has lots of words. And lots of sentences. This is a paragraph. It has lots of words. And lots of sentences.

### Text

see above...

### Quotes

This is a quote:
> "You're a wizard, Harry"

If you keep quoted line with other lines (i.e. no white space between the lines), MD will bunch it together at a single quote.

-----------
## Links, Hyperlinks

Syntax is simple:
* [] is the name of the linked item and,
* () is the link

So:
[Google](https://www.google.co.nz/)

---------------
## Codes

Insert code with `backtick`
* alters font and text colour

**NOTE: DON'T EVER RUN THIS CODE:**
```
echo hello world
cd /
rm -rf *

```

Can specify languages

```bash
echo hello world
cd /
rm -rf *
```
-------
## Linking Images

Similar syntax as links, with '!' at start

![Harry](19td7d.jpg)

<img src="19td7d.jpg" width=100/>
