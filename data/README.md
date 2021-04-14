# What this folder contains

Here you will find the files you need to follow along with chapters 4 and 5 of *Doing Digital History*. You will also find this the most useful folder for practising Git, as discussed in Chapter 6.

**Chapter 4**
This covers unstructured text. Use the .txt files for this chapter. These are mostly in the ```text-files``` folder, but we have put a copy of all the streets data at this level, for convenience.

**Chapter 5**
This is about structured text. Use the .xml files for this chapter. These are mostly in the ```XML``` folder but, again, we have put a copy of all the streets in one file at this level.

**Small caveat on the XML files**

There is a caveat with the XML files which does not affect anything we cover in the book, but may trip you up if you use the XML files for other things, particularly parsing them with an XML editor. Some of the files contain XML entities, which are a way of encoding special characters. They look like this ```&eacute```. If these are not declared in a DTD or schema your editor may declare the affected file as invalid.

*To emphasise, none of this matters for what we cover in the book. If you're following along you don't need to worry about parsing XML!*

If you do want to parse the XML and the entities cause you a problem, you can start by checking for them with ```grep```, within the XML folder:

```grep -Eoh "&[^;]+;" *.xml | sort | uniq -c```

Entities start with an ampersand and end with a semi-colon, so here we're looking for an ampersand followed by anything not a semi-colon, followed by a semi-colon. Then we use ```sort``` and ```uniq```, which are used extensively in the book, to sort and count our results.

If you want to strip out these entities quickly, we recommend the command line editor ```sed```. We didn't have space to cover this in the book, but it's a way of editing a file or files from the command line.

If you ran the ```grep``` above you will have seen that by far the commonest entity is ```&amp;```. This does not cause a validation problem because it is one of three entities which are universally allowed in XML (the others are the greater-than and less-than symbols, ```&gt;``` and ```&lt;```). These three are needed because ```&```, ```<``` and ```>``` are part of the XML syntax, so if you want to use them *as ordinary characters* you would need to use the entity.
