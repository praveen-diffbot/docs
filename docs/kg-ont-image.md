---
id: kg-ont-image
title: Image
---

The Image entity type encompasses images found throughout the web and known to the Knowledge Graph. 

Note that fields are not guaranteed to exist in every entity record.

>New to the Diffbot Knowledge Graph? [Start here](dql-quickstart).

## Image Fields
* [anchorUrl](#anchorurl) 
* [breadcrumb](#breadcrumb) 
* [displayHeight](#displayheight) 
* [displayWidth](#displaywidth) 
* [language](#language) 
* [links](#links) 
* [naturalHeight](#naturalheight) 
* [naturalWidth](#naturalwidth) 
* [tags](#tags) 
* [title](#title) 
* [url](#url) 
* [xpath](#xpath) 

## Image Field Details
Note that certain longer field examples may be truncated for readability in these docs. 

### anchorUrl
  Points to an anchor within a page (like &#x60;href&#x3D;&quot;#top&quot;&#x60;)
* **Type:** String
* **Example:**
```
{
	"anchorUrl": ""
}
```
### breadcrumb
  Graphical control element frequently used as a navigational aid; Returns a top-level array of URLs and link text from page breadcrumbs
* **Type:** GlobalIndexBreadcrumb
* **Example:**
```
{
	"breadcrumb": [
		{
			"link": "",
			"name": ""
		}
	]
}
```
### displayHeight
  Height of image as presented in the browser (and as sized via browser&#x2F;CSS, if resized)
* **Type:** Integer
* **Example:**
```
{
	"displayHeight": 0
}
```
### displayWidth
  Width of image as presented in the browser (and as sized via browser&#x2F;CSS, if resized)
* **Type:** Integer
* **Example:**
```
{
	"displayWidth": 0
}
```
### language
  
* **Type:** String
* **Example:**
```
{
	"language": ""
}
```
### links
  
* **Type:** String
* **Example:**
```
{
	"links": ""
}
```
### naturalHeight
  Raw image height, in pixels
* **Type:** Integer
* **Example:**
```
{
	"naturalHeight": 459
}
```
### naturalWidth
  Raw image width in pixels
* **Type:** Integer
* **Example:**
```
{
	"naturalWidth": 306
}
```
### tags
  Array of tags&#x2F;entities, generated from analysis of the extracted text and cross-referenced with DBpedia and other data sources. Language-specific tags will be returned if the source text is in English, Chinese, French, German, Spanish or Russian.
* **Type:** GlobalIndexTag
* **Example:**
```
{
	"tags": [
		{
			"score": "",
			"sentiment": 0,
			"types": "",
			"count": 0,
			"label": "",
			"uri": ""
		}
	]
}
```
### title
  Title of the Image
* **Type:** String
* **Example:**
```
{
	"title": "Sparky the dog saved the woman after she fell down the sewer"
}
```
### url
  URL of the image
* **Type:** String
* **Example:**
```
{
	"url": "https://i.dailymail.co.uk/1s/2019/04/03/11/11805062-6881369-image-a-83_1554287487623.jpg"
}
```
### xpath
  XPath expression identifying the image node
* **Type:** String
* **Example:**
```
{
	"xpath": ""
}
```