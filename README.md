# Design Review Checklist in Figma
Below is a checklist template to validate design components across categories like composition, properties, and behaviors.


### 1. Metadata
As a user, I can insert a component that’s precisely named and accurately described. [^1]

Item | Type | Description
:--- |:--- |:---
1.1 | **Name** | Is it named consistently with the code?
1.2 | **Description** | Is it described sufficiently?
1.3 | **Status** | Is the status of the component up-to-date?
1.4 | **Links** | Is linked correctly with the usage guidelines and code documentation?

### 2. Composition — Base, sub, and nested components
As a user, I can successfully swap out subcomponents to include other design system components and/or custom content as slots. [^2]

Item | Type | Description
:--- |:--- |:---
2.1 | **Base component** | Are
2.2 | **Base component content** | Are
2.3 | **Subcomponent properties** | Are
2.4 | **Subcomponent content** | Are
2.5 | **Slot component** | Are
2.6 | **Slot resize** | Are
2.7 | **Slot content reflow** | Are

### 3. Base Component Anatomy
As a user, I want to interact with a well-organized and cleanly built component anatomy. [^3]

Item | Type | Description
:--- |:--- |:---
3.1 | **Layer name** | Are layer names consistent with the specified component anatomy?
3.2 | **Layer format** | Are layer names formatted as actual names in sentence case?
3.3 | **Default visibility** | Are layers shown or hidden appropriately, including layers within hidden layers?

### 4. Color styles
As a user, the component applies colors via color styles and component-specific attributes in a manner consistent with design tokens. [^4]

Item | Type | Description
:--- |:--- |:---
4.1 | **Color styles** | Is every fill, stroke, solid color and gradient applying a color style instead of a hardcoded value?
4.2 | **Color accuracy** | Are background, text, and border colors applied accurately relative to design specifications? This includes accuracy of states, theming, and other color variability.
4.3 | **Style specificity** | Is each color style applying the most semantically specific (Text > Link > On Dark) instead of generic (Global colors > Blue > 50) style?
4.4 | **Hardcoded colors** | Where a hardcoded value is used, has it been discussed and agreed upon?
4.5 | **Buried colors** | Are buried hardcoded colors — applied to shadow effects and other non-styled locations — applied accurately?

### 5. Text styles
As a user, the component applies system typography via text styles and component-specific overrides so that I don’t have to style text. [^5]

Item | Type | Description
:--- |:--- |:---
5.1 | **Text styles** | Is each text layer associated with a defined text style?
5.2 | **Non-text style properties** | Are properties not styles — list style, vertical alignment, and horizontal alignment — accurately applied or omitted?

### 6. Content
As a user, I can flow text, images, icons and other content into the component and the within-component layout will adapt accordingly regardless of the component’s size. [^6]

Item | Type | Description
:--- |:--- |:---
6.1 | **Too much content** | Does layout break when content is too large, such as a wrapping label, collision or image that needs to be cropped?
6.2 | **Too little content** | Does layout accurately present content that’s quite small, such as a label of a few characters or an image too small for a container?
6.3 | **Missing content** | Does it break in the absence of content, such as omitted text or missing image?

### 7. Auto Layout
As a user, I want to[^7]

Item | Type | Description
:--- |:--- |:---
7.1 | **Name** | Are

### 8. Spacing Tokens
As a user, I can trust that the space between elements is precise. [^8]

Item | Type | Description
:--- |:--- |:---
8.1 | **Padding around items** | Is every element — particularly containers of nested elements — padding the container precisely?
8.2 | **Alignment** | Is every element and pair of adjacent elements aligned correctly as elements expand and the component resizes?
8.3 | **Space between items** | Is every element and pair of adjacent elements inset and separated consistent with design specifications?

### 9. Properties
As a user, I can adjust properties and values in a manner consistent with the component code. As a designer, I can insert a component with appropriate defaults. [^9]

Item | Type | Description
:--- |:--- |:---
9.1 | **Property names** | Are properties named and formatted correctly?
9.1 | **Property order** | Are properties ordered sensibly, such as by priority, alphabetical, related sets, or documented order across components?
9.1 | **Option names** | Are property options named and formatted correctly?
9.1 | **Option order** | Are options ordered correctly, such as by scale order ( small then medium then large) or alphabetical?
9.1 | **Default option** | When I insert an instance, is the default correct? Is the default option positioned correctly within the option order?

### 10. Behaviors
As a user, I can leverage prototyping states, animations and other behaviors as scoped for the component. [^10]


[^1]: My reference.
[^2]: My reference.  
[^3]: My reference.
[^4]: My reference.
[^5]: My reference.
[^6]: My reference.
[^7]: My reference.
[^8]: My reference.
[^9]: My reference.
[^10]: My reference.
