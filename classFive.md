<h1> CSS -Cascading Style Sheets </h1>

CSS -Cascading Style Sheets
  * CSS is a rule-based language for specifying how documents are presented to users — how they are styled, laid out, effects (i.e. animation), etc. 
  * CSS defines rules specifying a group of styles that should be applied to certain elements/groups of elements on the web page. 

Rules 
	* Opens with a selector.  h1 { } (curly braces)
	* Inside braces -one or more declarations with property and value pairs
	* Before colon -Property; after colon -value

Inserting CSS
  * External CSS -change one file <link rel=”stylesheet” href=”mystyle.css”> (must have .css extension and should not contain any HTML tags)
  	* External Styles are defined with <link> element inside of the <head> section
	* Internal CSS -one single HTML page has a unique style.
		* Internal Styles are defined with <style> element inside the <head> section
	* Inline CSS -used to apply unique style to single element
		  * Inline styles are defined with the “style” attribute of the relevant element
  * Using multiples -If some properties are defined for the same selector/element in different style sheets, the value from the last read stylesheet will be used.
  * Myers Web Reset Stylesheet

* Cascading Order -all styles will cascade into a new “virtual” style sheet by the following rules -number one has the highest priority.

  * Inline style (inside an HTML element)
  * External and internal style sheets (in the head section)
  * Browser default

  Color
	  * color: red; 
	  * color: 00ff00;
	  * color: rgb(0,0,255);

	  * color -specifies text color
  	* initial -sets the property to default value
	  * inherit -inherits front the parent element
