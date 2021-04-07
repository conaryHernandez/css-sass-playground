# css-sass-playground

## Natours

- Float layouts
- 7 - 1 Architecture
- Perspective Property
- Clip-path Property
- Background-clip Property
- backface-visibility Property
- Checkbox trick
- Mobile First vs Desktop First
- Media query order
- @supports query
- Only screen condition
- Density Switching
- Art Direction (Changing image)

## Trillo

### Flexbox

#### Container

##### flex-direction: row | row-reverse | column

Indicates content direction

##### flex-wrap: nowrap | wrap | wrap-reverse

Simply defines if the Flex items should wrap into a new line if there is not enough space in the Flex container or not.

##### justify-content: flex-start | flex-end | center | space-between | space-around | space-envenly

Defines how the Flex items will be aligned along the main axis.

##### align-items: flex-start | flex-end | center | baseline

Similar to justify-content with a difference that this one defines how the Flex items will be aligned along the cross axis, not the main axis.

##### align-content: flex-start | flex-end | center | space-between | space-around

Only applies when there is more than one row of Flex items. In that case, align-content controls how the rows are aligned along the cross axis.

#### Item

##### align-self: auto | stretch | flex-start | flex-end | center | baseline

Similar to align-items but for one individual Flex item.

##### order: 0 | integer

Defines the order in which one specific Flex item should appear inside the container.

##### flex-grow: 0 | integer

We define how much an item can grow.

##### flex-shrink: 1 | integer

We define how much it can shrink

##### flex-basis: auto | length

We can define its base width.
