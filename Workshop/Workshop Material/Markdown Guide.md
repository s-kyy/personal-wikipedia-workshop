%%also available via the Help vault!%%
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Formatting:
**bold** __bold__
*italics* _italics_
~~strikethough~~
==highlight==
%%comments (won't appear in preview mode)%%

> quotes

---
Bullet  Lists
- Item 1
	- Item a
	- Item b
- Item 2

---
Ordered Lists
1. One
2. Two
	1. Two.one

---
Checklists
- [ ] First Todo
- [ ] Second Todo
	- [ ] Sub-todo

---
Other useful formatting: 
- CTRL-K : Making links [Website on Corgi's](https://www.carsonvet.com/services/dogs/breeds/pembroke-welsh-corgi)
- Wikilinks (Internal Linking): `[[Note Name]]` (existing or new notes)
- Pasting from clipboard and `![[Embedding Images]]`  ^8b2361
	- Embedding Full Notes: `![[Note Name]]`
	- Embedding Headers: `![[Note Name#Header]]`
	- Embedding Paragraphs: `![[Note Name^Paragraph Code]]`
		- EX: ![[Outline v1#^5b5db4]]
	- [[Outline v1#Plugin]]
- Code Fencing: 
	```python
	print("Hello world")
	```
- YAML formatting - At the top of a note, we can tell Obsidan what synonyms, abbreviations etc we'd like it to track in the unlinked references. For a note named `Artifical Intelligence` you can Indicate the following (without the code fences):
```
---
aliases: [AI]
---
```


