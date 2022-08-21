# How To Review UI Kit Component

> Below is a checklist that organize specific criteria to validate across categories like composition, properties, behaviors and content.

1. Metadata
2. Composition — Base, slots, and nested components
3. Anatomy
4. Color styles
5. Text styles
6. Content
7. Spacing
8. Layout
9. Properties
10. Composition—Base, sub, and nested components
11. Behaviors


### 1. Metadata
As a designer, I can insert a component that’s precisely named and accurately described.[^1]

Item | Type | Description
--- | --- | ---
1.1 | **Name** | Is it named consistently with the code?
1.2 | **Description** | Is it described sufficiently, such as with a component introduction from Aether documentation?
1.3 | **Status** | Is status up-to-date, such as stability (Soon-to-be-removed, Experimental, Beta or …)?
1.4 | **Page Title Links** | Is linked correctly with the Usage Guidelines and Code Documentation?


### 2. Anatomy
As a designer, I want to interact with a well-organized and cleanly built component anatomy to find and adjust elements as needed.[^2]

Item | Type | Description
--- | --- | ---
[ ] 2.1 | `Layer name` | Are layer names consistent with the specified component anatomy?
[ ] 2.2 | `Layer name` | Are layer names formatted as actual names in sentence case, not “Frame ###”?
[ ] 2.3 | `Layer name` | Are naming conventions applied, such as using space between (]-[) for layers?
[ ] 2.4 | `Layer name` | Are nested components named descriptively?
[ ] 2.5 | `Layer name` | Are layers shown or hidden appropriately, including layers within hidden layers?

### 3. Color styles
As a designer, the component applies colors via color styles and component-specific attributes in a manner consistent with design tokens.

Item | Type | Description
--- | --- | ---
[ ] 3.1 | `Layer name` | Are 
[ ] 3.2 | `Layer name` | Are 
[ ] 3.3 | `Layer name` | Are 
[ ] 3.4 | `Layer name` | Are 
[ ] 3.5 | `Layer name` | Are 

### 4. Text styles
As a designer, the component applies system typography via text styles and component-specific overrides so that I don’t have to style text.

Item | Type | Description
--- | --- | ---
[ ] 4.1 | `Layer name` | Are 
[ ] 4.2 | `Layer name` | Are 


---

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]


Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

--- 

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.


---

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

---

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
</dl>