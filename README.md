# flex-box

Flexbox intro

FLEXBOX-CONATAINER{
display: flex; = initialize flexbox

flex-wrap: wrap; = moves items to stack on each other when the screen size reduces

justify-content: flex-start;
flex-end = adds space to the end of the items
space-around = add space all around the items
space-start = add space to the begining
space-end = add space to the end
center = places items in the center of the container
space-betweeen = adds even space between the items
(default)stretch = stretches items to fill the vertical container

align-items: flex-start; = keeps items at the actual sizes from the top of the container
center

align-content: center; = align all items in the container to the middle

flex-direction: column; = puts all items in columns
justify-content: center; = put the items in the center of the column and not the container
align-items: center; = keeps items at the center of the container

}

FLEXBOX ITEMS {
min-height: 100px;

flex-shrink: 0; = tells that item not to shrink like the others when the container decreases

flex-grow: 1; = tells that item to grow and fill the remaining space when the container increases

flex-basis: 0; = tells flexbox to share the spaces evenly between items

align-self: fles-end; = puts item at the end(bottom) of the container
align-self: center; = puts item in the center of the container
order: 1; = changes the order of where items are positioned on the container

}

/_ C U P_/
fb-cont{
display: flex;
justify-content: center;
align-item: center;
}

fb-it{
flex-grow: 2;
flex-shrink: 0;
flex-basis: 0;
}
