# Markdown Tutorial

----

## Lesson One (*Italic and Bold*)


1. To make a phrash *italic* in Markdown, you can surround words with and underscore(`_`).

	> Writing in Markdown is *not* that hard!

2. Similary, to make phrases **bold** in Markdown, you can surround words with two asterisks (`**`). This will `**really**` get your point across. 

	> I **will** complete these lessons!

3. You also can use `_both italics and bold_`in the same line. You can also span them `**across multiple words**`.

	> *"Of course*, she whipered. Then, she shuoted: "All I need is **a little moxie**!"

4. in general, it doesn't matter which order you place the asterisks or underscoresl; you can make some words *bold* _**and**_ *italic*

	>if you're thinking to yourself. _**This is unbelievable**_, you'd probably be right.  

----
## Lesson Two (#Headers)

1. There are six type of headers, in decreasing size:

	># The first biggest header
	>## The second biggest header
	>### The third biggest header
	>#### The fourth biggest header
	>##### The fifith biggest header
	>###### The smallest header 

2. In general, headers one and six should be used sparingly, and also header can be made *italic*.


	># *The first biggest header is italicized* 

----

## Lesson Three (Links)

1. The first link style is called an *inline link*. To create an inline link, warp the link text in barckets `[ ]`, and then the link in parenthesis (`( )`). 

	> [Search for it] (www.google.com) (google)



2. Link text could be emphasised, by using bold syntax


	>[**Search for it**](www.google.com) (google)    

3. Link also can be used within headings. 

	>##### Lesson Three ([Links](http://www.markdowntutorial.com/lesson/3/)) 

4. Reference links 

	>Here's [a link to something else] [another place]
	>Here's [yet another link][another-link]
	>and now back to [the first link][another link]
	>[another place]: www.github.com
	>[another-link]: www.google.com
	
----

## Lesson Four (Images) 

The different with adding links is that an image is prefaced with an exclamation point (`!`), followed by the same two brackets, and a pari of parentheses containing the image URL. Within the image brackets, you can place some "alt text", which is a phrase that describes the image for the visually imparied. 


	>![Alt text](url)  

For example:

> **if you want to get this github logo, you should type:**

	> ![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-256.png)
	
![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-256.png)

----

## Lesson Five (Blockquotes) 

If you need to call special attention to a quote from another source, or desgin a pull quote for a magazine article, then Markdown *blackquote* is useful. 

	> to create a block quote, all you have to do is preface a line with the " great than" caret (`>`). 

for example: 


> GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.



> Note that some features of GitHub Flavored Markdown are only available in the descriptions and comments of Issues and Pull Requests. These include @mentions as well as references to SHA-1 hashes, Issues, and Pull Requests. Task Lists are also available in Gist comments and in Gist Markdown files.
 
----

## Lesson Six (Lists)



1. There are two types of lists in the known universe: unordered and ordered. To create an unorder list, type (`*`), for example: 
	
		* Milk 
		* Eggs
		* Salmon
		* Butter
	>  **(TIPS: `*` comes with space, otherwise won't work**)

	Then the unordered Markdown list will be: 
	* Milk
	* Eggs
	* Salmon
	* Butter
	
2. An ordered list is prefaced with numbers, instead of asterisks, for example"
	
	1. Crack therr eggs over a bowl
	2. Pour a gallon of milk into the bowl
	3. Rub the salmon vigorously with butter
	4. Drop the salmon into the egg-mil bowl 

	To write that in Markdown, you'd do this:
	> 1. Crack therr eggs over a bowl
	>2. Pour a gallon of milk into the bowl
	>3. Rub the salmon vigorously with butter
	>4. Drop the salmon into the egg-mil bowl 
	
3. If you need more depth lists, or nest one list within another. All you have to do is to remember to indent each asterisk on space more than the preceding item. 

	For example: 

	> * Tintin
 	>  * A reporter
    >  * Has poofy orange hair
    >  * Friends with the world's most awesome dog
	> * Haddock
 	>  * A sea captain
 	>  * Has a fantastic beard
 	>  * Loves whiskey
  	>    * Possibly also scotch?  

All you have to type is 
	
	* Tintin
	 * A reporter
	 * Has poofy orange hair
	 * Friends with the world's most awesome dog
	* Haddock
	 * A sea captain
	 * Has a fantastic beard
	 * Loves whiskey
	   * Possibly also scotch?  (Be careful * is needed to intend two) 

----
## Lesson Seven (Paragraphs)

Suppose you want to write text that looks like this:

> Do I contradict myself?
> Very well then I contradict myself.
> (I am large, I contain multitudes)

Unforunately, if you type like this, this Markdown would rendent simply as stralight line. 

Too be continued.. more **"extended** of Markdown will be update


----

### REFERENCE:

[GitHub Markdown Tutorial](http://www.markdowntutorial.com/lesson/1/)

[Getting Started with GitHub Pages](https://guides.github.com/features/pages/)

----
#### CopyRight @ Wentao Liang  