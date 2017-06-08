# Memex REST API


## What is Memex?

Memex is lightweight personal knowladge base with automatic content management. It means that it helps organise every piece of knowledge (notes, urls, sketches, comments, etc.). These pieces (spaces) are interconnected using memory links which helps to navigate and associate it into more compact knowledge. It is just like web but more lightweight and only personal.

### Space
Core concept of Memex is space which is bundle/collection/folder of small pieces of knowledge. It can be piece of text (text space) note or large collection of links to other collections (collection space).

There is a few standard space types in two core categories:

1. Collection-oriented - defined/represented by its caption
	* Collection - abstract set of links to other spaces
2. Atomic (shortly atoms) - defined/represented by caption and linked media
	* WebPage - decorated URL to any webpage
	* Text - small textual piece of information/note or anything that can be written
	* Image - visual piece of knowledge

Space has wollowing structure:

### Link

Another core principle of memex is link which is nothing more than connection between two spaces. So if there exists association between two things/ideas/spaces in users brain there should be also oriented link in memex.


### Media

Piece of data that can be users avatar or image/textual representation of space.


## Smart Fetaures

Today memex supports two smart features that will help user to automatically manage his content.

#### Auto-Categorization (Autodump)

First one is called autodump and will automatically link new space with most fitting already existing space. Eg. If user drops webpage url and there already exists similar collection of spaces then Memex will try to automatically create link from this collection to newly created space. See Examples section.

#### Auto-Captioning

Are you creating collection of spaces but dont know how to name it?Another smart feature that is offered by Memex is automatic captioning/summarization of space. Just provide set of space MUIDs and we will tell you what is the best name for it.


## Documentation

See swagger generated [documentation](http://memex.co/apps/dev/doc/rest).

## Other Platform APIs

* [JS SDK](https://github.com/memexapp/memex-js-sdk)  
* [Swift SDK](https://github.com/memexapp/memex-swift-sdk)  
* [Go SDK](https://github.com/memexapp/memex-go-sdk)  

## Contact Us

If you need any other help please contact us at [hello@memex.co](mailto:hello@memex.co)  
