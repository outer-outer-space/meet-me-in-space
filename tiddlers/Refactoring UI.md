**Book:** Refactoring UI
**Authors:** Adam Wathan, Steve Schoger
**Find Online:** [https://refactoringui.com/book/](https://refactoringui.com/book/)
**Date Read:** February 2019

## Why did I choose to read this book?
This was another recommendation that came from Thomas soon after I started working for him. It was directed at my entire software team, and a little over a year later, I definitely think it's made an impact on the design culture on that team. 

---

## Table of Contents
1. **Starting from Scratch**
	1. Start with a feature, not a layout
	2. Detail comes later
	3. Don’t design too much
	4. Choose a personality
	5. Limit your choices
2. **Hierarchy is Everything**
	1. Not all elements are equal
	2. Size isn’t everything
	3. Don’t use grey text on colored backgrounds
	4. Emphasize by de-emphasizing
	5. Labels are a last resort
	6. Separate visual hierarchy from document hierarchy
	7. Balance weight and contrast
	8. Semantics are secondary
3. **Layout and Spacing**
	1. Start with too much white space
	2. Establish a spacing and sizing system
	3. You don’t have to fill the whole screen 
	4. Grids are overrated
	5. Relative sizing doesn’t scale
	6. Avoid ambiguous spacing
4. **Designing Text**
	1. Establish a type scale
	2. Use good fonts
	3. Keep your line length in check
	4. Baseline, not center
	5. Line-height is proportional
	6. Not every link needs a color
	7. Align with readability in mind
	8. Use letter-spacing effectively
5. **Working with Color**
	1. Ditch hex for HSL
	2. You need more colors than you think
	3. Define your shades up front
	4. Don’t let lightness kill your saturation 
	5. Greys don’t have to be grey
	6. Accessible doesn’t have to mean ugly. 
	7. Don’t rely on color alone
6. **Creating Depth**
	1. Emulate a light source
	2. Use shadows to convey elevation 
	3. Shadows can have two parts
	4. Even flat designs can have depth
	5. Overlap elements to create layers 
7. **Working with Images**
	1. Use good photos
	2. Text needs consistent contrast
	3. Everything has an intended size
	4. Beware user-uploaded content 
8. **Finishing Touches**
	1. Supercharge the defaults
	2. Add color with accent borders
	3. Decorate your backgrounds
	4. Don’t overlook empty states
	5. Use fewer borders
	6. Think outside the box
9. **Leveling Up**

---

# My Notes
## 1: Starting from Scratch
#### 1.1 Start with a feature, not a layout
> …an “app” is actually a collection of *features*. Before you’ve designed a few features, you don’t even have the information you need to make a decision about how the navigation should work 

#### 1.2 Detail comes later
> By designing in grayscale, you’re forced to use spacing, contrast, and size to do all of the heavy lifting. 

#### 1.3 Don’t design too much
> Instead of designing everything up front, work in short cycles. Start by designing a simple version of the next feature you want to build… Iterate on the working design until there are no more problems left to solve, then jump back into design mode and start working on the next feature. 

> If part of a feature is a “nice-to-have”, **design it later**. Build the simple version first and you’ll always have something to fall back on. 

#### 1.4 Choose a Personality
> Words are everywhere in a user interface, and choosing the right ones is just as (if not more) important than choosing the right color or typeface. 

#### 1.5 Limit your Choices
> *Design systems in advance:* Instead of hand-picking values from a limitless pool any time you need to make a decision, *start with a smaller set of options*. 

> *Systematize everything:* Look for opportunities to introduce new systems as you make new decisions, and try to avoid having to make the same minor decision twice. 

----

## 2: Hierarchy is Everything
#### 2.1 Not all elements are equal
> *Visual hierarchy*refers to how important the elements in an interface appear in relation to one another, and it’s the most effective tool you have for making something feel “designed”. 

#### 2.2 Size isn’t everything
> Instead of leaving all of the [hierarchical] heavy lifting to font size alone, try using font weight or color to do the same job. 

#### 2.3 Don’t use grey text on colored backgrounds
> Making the text closer to the background color is what actually helps create hierarchy, not making it light grey. 

#### 2.4 Emphasize by de-emphasizing
> Sometimes you’ll run into a situation where the main element of an interface isn’t standing out enough, but there’s nothing you can add to it to give it the emphasis it needs. 
> 
> When you run into situations like this, instead of trying to further emphasize the element you want to draw attention to, figure out how you can *de- emphasize*the elements that are competing with it. 

#### 2.4 Labels are a last resort
> When you’re able to present data without labels, it’s much easier to emphasize important or identifying information, making the interface easier to use while at the same time making it feel more “designed”. 

> *Combine labels and values:* When you’re able to combine labels and values into a single unit, it’s much easier to give each piece of data meaningful styling without sacrificing on clarity. 

#### 2.5 Separate visual hierarchy from document hierarchy
> A lot of the time, section titles act more like *labels* than headings — they are supportive content, they shouldn’t be stealing all the attention. Usually the *content* in that section should be the focus, not the title. That means that a lot of the time, titles should actually be pretty small 

#### 2.6 Balance weight and contrast
> *Using contrast to compensate for weight (and vice versa):*  Reducing the contrast works like a counterbalance, making heavier elements feel lighter even though the weight hasn’t changed (e.g. lightening icon colors to deemphasize)

#### 2.7 Semantics are secondary
> Every action on a page sits somewhere in a pyramid of importance. Most pages only have one true primary action, a couple of less important secondary actions, and a few seldom used tertiary actions. 
> 
> When designing these actions, it’s important to communicate their place in the hierarchy. 

	1. Primary actions should be obvious.
	2. Secondary actions should be clear but not prominent.
	3. Tertiary actions should be discoverable but unobtrusive.

---

## 3: Layout and spacing
####  3.1 Start with too much white space
> One of the easiest ways to clean up a design is to simply give every element a little more room to breathe. 

#### 3.2 Establish a spacing and sizing system
> For a system to be truly useful, it needs to take into consideration the *relative*difference between adjacent values. 

> A simple approach [for your spacing and sizing scale] is to start with a sensible *base*value, then build a scale using factors and multiples of that value. 16px is a great number to start with because it divides nicely, and also happens to be the default font size in every major web browser. 
[img[Refactoring UI Image 1: Sizing and Scaling]]

#### 3.3 You don’t have to fill the whole screen 
> …just because you have the space, doesn’t mean you need to use it. 

> Spreading things out or making things unnecessarily wide just makes an interface harder to interpret, while a little extra space around the edges never hurt anyone. 

#### 3.4 Grids are overrated
> …even though grids can be useful, outsourcing *all*of your layout decisions to a grid can do more harm than good. 

#### 3.5 Relative sizing doesn’t scale
> Let go of the idea that everything needs to scale proportionately — giving yourself the freedom to fine-tune things independently makes it a hell of a lot easier to design for multiple contexts. 

#### 3.6 Avoid ambiguous spacing
> When groups of elements are explicitly separated — usually by a border or background color — it’s obvious which elements belong to which group.  But when there isn’t a visible separator, it’s not always so obvious. 

> Whenever you’re relying on spacing to connect a group of elements, always make sure there’s more space *around*the group than there is within it…

---

## 4: Designing Text
#### 4.1 Establish a type scale
> For interface design, a more practical approach is to simply pick values by hand. 

> *Avoid em units:* When you’re building a type scale, don’t use *em*units to define your sizes. Stick to *px*or *rem*units instead. 


[img[Refactoring UI Image 2: Font Sizing and Scaling]]

#### 4.2 Use good fonts
> If you really don’t trust your own taste, one great option is to rely on the system font stack:  `-apple-system, Segoe UI, Roboto, Noto Sans, Ubuntu, Cantarell, Helvetica Neue;`

> Ignore typefaces with less than five weights

#### 4.3 Keep your line length in check
> For the best reading experience, make your paragraphs wide enough to fit between 45 and 75 characters per line. The easiest way to do this on the web is using *em*units, which are relative to the current font size. A width of 20-35em will get you in the right ballpark. 

#### 4.4 Baseline, not center
> When you align mixed font sizes by their baseline, you’re taking advantage of an alignment reference that your eyes already perceive. 

#### 4.5 Line-height is proportional
> …line-height and paragraph width should be proportional — narrow content can use a shorter line-height like 1.5, but wide content might need a line-height as tall as 2. 

> Line-height and font size are *inversely*proportional — use a taller line-height for small text and a shorter line-height for large text. 

#### 4.6 Not every link needs a color
> …when you’re designing an interface where almost everything is a link, using a treatment designed to make links “pop” in paragraph text can be really overbearing. 

#### 4.7  Align with readability in mind
> …if something is longer than two or three lines, it will almost always look better left-aligned. 

> If you’re designing a table that includes numbers, right-align them. 

#### 4.8 Use letter-spacing effectively
> If you want to use a family with wider letter-spacing for headlines or titles, it can often make sense to decrease the letter-spacing to mimic the condensed look of a purpose-built headline family: 

> …it often makes sense to increase the letter-spacing of all- caps text to improve readability: 

---

## 5: Working with Color
#### 5.1 Ditch hex for HSL
> Hex and RGB are the most common formats for representing color on the web, but they’re not the most useful. HSL fixes this by representing colors using attributes the human-eye intuitively perceives: *hue*, *saturation*, and *lightness*. 

#### 5.2 You need more colors than you think
> You can break a good color palette down into three categories. 

1. *Grays:* In practice, you want 8-10 shades to choose from 
2. *Primary Colors:* sites need one, *maybe*two colors that are used for primary actions, active navigation elements, etc. These are the colors that determine the overall look of a site — the ones that make you think of Facebook as “blue”. You need a variety *(5-10)*of lighter and darker shades to choose from. 
3. *Accent colors:* for communicating different things to the user, e.g. a new feature or to emphasize different semantic stages. You’ll want multiple shades for these colors too, even though they should be used pretty sparingly throughout the UI. 

#### 5.5 Define your shades up front
> …define a fixed set of shades up front that you can choose from as you work. 

> *Choose base color first:* There’s no real scientific way to do this, but for primary and accent colors, a good rule of thumb is to pick a shade that would work well as a button background. 

#### 5.6 Don’t let lightness kill your saturation 
> …if you don’t want the lighter and darker shades of a given color to look washed out, you need to increase the saturation as the lightness gets further away from 50%. 

> Since different hues have a different perceived brightness, another way you can change the brightness of a color is *by rotating its hue*.  To make a color lighter, rotate the hue towards the nearest bright hue — 60°, 180°, or 300°. To make a color darker, rotate the hue towards the nearest dark hue — 0°, 120°, or 240°. 

#### 5.7 Greys don’t have to be grey
> colors that we *think of*as grey are actually saturated quite heavily 

#### 5.8 Accessible doesn’t have to mean ugly. 
> When using white text on a colored background, you’d be surprised how dark the color often needs to be to meet that 4.5:1 contrast ratio… You can solve this problem by *flipping the contrast*. Instead of using light text on a dark colored background, use dark colored text on a light colored background 

#### 5.9 Don’t rely on color alone
> Always use color to support something that your design is already saying; never use it as the only means of communication. 

> …someone who is red-green colorblind can’t easily tell if a metric has gotten better or worse. An easy fix for this is to also communicate that information in some other way, like by adding icons to indicate if the change is positive or negative. 

> …try relying on *contrast*instead of using completely different colors. It’s much easier for someone who’s colorblind to tell the difference between light and dark than it is for them to tell the difference between two distinct colors. 

---

## 6: Creating Depth
#### 6.1 Emulate a light source
> If you want an element to appear raised or inset, first figure out what *profile*you want that element to have, then mimic how a light source would interact with that shape. 

> Borrowing some visual cues from the real world is a great way to add a bit of depth, but there’s no need to try and make things look photo-realistic. 

#### 6.2 Use shadows to convey elevation 
> Shadows can be more than just a flashy effect — used thoughtfully, they let you position elements on a virtual z-axis to create a meaningful sense of depth. 

> The closer something feels to the user, the more it will attract their focus. 

> Just like with color, typography, spacing, and sizing, defining a fixed set of shadows will speed up your workflow and help maintain consistency in your designs. You don’t need a ton of different shadows — five options is usually plenty. 

> Using shadows in a meaningful way like this is a great way to hack the process of choosing what sort of shadow an element should have. Don’t think about the shadow itself, think about where you want the element to sit on the z-axis and assign it a shadow accordingly. 

#### 6.3 Shadows can have two parts
> When you see someone combining two shadows, they’re not just experimenting randomly until things look nice, they’re using each shadow to do a specific job: 1) The first shadow is larger and softer, with a considerable vertical offset and large blur radius. It simulates the shadow cast behind an object by a direct light source. 2) The second shadow is tighter and darker, with less of a vertical offset and a smaller blur radius. It simulates the shadowed area *underneath*an object where even ambient light has a hard time reaching. 

#### 6.4 Even flat designs can have depth
> In general *(especially with shades of the same color)*, lighter objects feel closer to us and darker objects feel further away. 

> Another way to communicate depth in a flat design is to use short, vertically offset shadows with no blur radius at all. 

#### 6.5 Overlap elements to create layers 
> One of the most effective ways to create depth is to overlap different elements to make it feel like a design has multiple *layers*. 

---

## 7: Working with Images
#### 7.1 Use good photos
> Bad photos will ruin a design, even if everything else about it looks great. 

#### 7.2 Text needs consistent contrast
> …*reduce*the dynamics in the image to make the contrast between the text and the background more consistent, e.g. by adding a semi-transparent overlay to the background image, or lowering image contrast

#### 7.3 Everything has an intended size
>  icons that were drawn at 16–24px are never going to look very professional when you blow them up to 3x or 4x their intended size. They lack detail, and always feel disproportionately “chunky” 

#### 7.4 Beware user-uploaded content
> Instead of letting users wreak havoc on your page structure, center their images inside fixed containers, cropping out anything that doesn’t fit. 

---

## 8: Finishing Touches
#### 8.1 Supercharge the defaults
> You don’t always have to add new elements to a design to add flare — there are a lot of ways to liven up a page by “supercharging” what’s already there. 

#### 8.2 Add color with accent borders
> One simple trick that can make a big difference is to add colorful accent borders to parts of your interface that would otherwise feel a bit bland. 

#### 8.3 Decorate your backgrounds
> A great way to break up some of the monotony without drastically altering the design is to add some excitement to a few of your backgrounds. 

> You don’t have to necessarily repeat it across the entire background, either — a pattern designed to repeat along a single edge can look great, too. 

#### 8.4 Don’t overlook empty states
> If you’re designing something that depends on user-generated content, the empty state should be a priority, not an afterthought. Try incorporating an image or illustration to grab the user’s attention, and emphasizing the call-to-action to encourage them to take the next step 

> Empty states are a user’s first interaction with a new product or feature. Use them as an opportunity to be interesting and exciting — don’t settle for plain and boring. 

#### 8.5 Use fewer borders
> Box shadows do a great job of outlining an element like a border would, but can be more subtle and accomplish the same goal without being as distracting. 

> Giving adjacent elements slightly different background colors is usually all you need to create distinction between them. 

#### 8.6 Think outside the box
> …just because we’ve been conditioned to believe that there’s only one way to design a particular component, doesn’t mean it’s true. 

> When you imagine a table, you probably think of columns that each contain one specific piece of data. Tables don’t *have*to work this way, though — if a column doesn’t need to be sortable, there’s no reason you can’t combine it with a related column and introduce some interesting hierarchy.

> Don’t let your existing beliefs hold back your designs — constraints are powerful but sometimes a bit of freedom is just what you need to take an interface to the next level. 

----

## 9: Leveling Up
> Whenever you stumble across a design you really like, ask yourself: *“Did the designer do anything here that I never would have thought to do?”*

> The absolute best way to notice the little details that make a design look really polished is to recreate that design from scratch. By continually studying the work that inspires you with a careful eye, you’ll be picking up design tricks for years to come. 