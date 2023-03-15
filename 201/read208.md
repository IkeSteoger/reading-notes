# 201 Reading 08

## CSS Layout

### Flexbox

Flexbox intakes a bunch of items of different sizes & returns the best layout for those items.

The main axis is set by the `flex-direction` but the cross axis runs the other direction of the `flex-direction` so if the if `flex-direction` is `row` then the cross axis runs along the `column`.

Certain properties such as `row-reverse` and `column-reverse` redorder the visual order but not the logical order, which can create issues with accessibility (which is very important!)

### CSS Layout Using Flexbox

Floats & positioning make it difficult or impossible to do the following in any convienent way:

>-Vertically centering a block of content inside its parent.
>-Making all the children of a container take up an equal amount of the available width/height regardless of how much width/height is available.
> Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.
>Credit: Mozilla.org

while Flexbox makes many layout tasks much easier.

This topic connects with my long term goals of styling CSS texts in an easier method - which will save so much time!

## Things I want to know more about

Is the Flexbox most often used on most webpages? Or just certain pages like the Mozilla.org coding tips & tricks website?
