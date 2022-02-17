1. What are the 3 values defined in the shorthand flex property (e.g. flex: 1 1 auto)?
- flex --> A property, which can be set on a flex item. It is used to define how the element adapts its size inside a flex container. 
- 1 --> The first value is the flex-grow. If all  items have the same flex-grow value, the flex items grow evenly to it's avaibable size. With a higher value, the flex items takes more of the avaible space. A flex size of 2 is double the size of the other flex item, with a flex size of 1
- 1 --> The second value is the flex-shrink. If all items have the same flex-shrink value, the items shrink evenly, when the space of the parent container is smaller than the flex items. The higher flex-shrink value, gets more space than the other flex items with a lower flex-shrink value.
- auto --> The third item is the flex-base. This value sets the base value of the flex item. If it is set to auto, it uses a given width an height value. 
