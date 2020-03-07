# Homework-1 Notes: Jeffrey Adamo 3/7/2020 

Acceptance Criteria:

GIVEN a webpage meets accessibility standards

## 1) WHEN I view the source code, THEN I find semantic HTML elements

	• There were lot of <div> elements. These need to be optimized.
	• Changed <div class=header"> to a <header> element.
		○ Simplified CSS to reflect <header>, <h1> tags. Removed first <div> element and styled CSS within the <ul> element. 
	• Redefined <div> element for meeting image as <figure> element. Linked image in html rather than CSS. Used id="hero" instead of class because only used once
	• Redefined <div> element for 3 left boxes to <main> element
	• Redefined <div> element for "benefits" as <aside> element
		○ Replaced <div> class="benefits"> to <aside class="benefits">
			§ CSS changed as well
	• Redefined <div> element for "footer" as <footer> element
	
## 2) WHEN I view the structure of the HTML elements, THEN I find that the elements follow a logical structure independent of styling and positioning

	• Incorporated styling of elements (heading, main, aside, footer) instead of classes in CSS

## 3) WHEN I view the image elements, THEN I find accessible alt attributes

	• Added alt="name of image" in each image tag

## 4) WHEN I view the heading attributes, THEN they fall in sequential order

	• Moved all class attributes to the beginning of the tag
		○ As in: <img class="float-left" src=… alt=…> ordering
	• Since the <h3> tag is only used in the aside, I consolidated CSS of ".benefit-lead h3", "benefit-brand h3", "benefit-cost h3" to a h3 CSS.

## 5) WHEN I view the title element, THEN I find a concise, descriptive title

	• Renamed as "Horiseon"
