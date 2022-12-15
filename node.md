# Flexbox

## flex

## All the below properties are of parent property.

## flex-row (by-default), flex-row-reverse, flex-col, flex-col-reverse

## flex-wrap, flex-wrap-reverse, nowrap(by-default)
## Width of the block is totally depends on content inside the block.

## Justify content
## justify-start(by-default), justify-end, justify-center, justify-between, justify-around, justify-evenly.

## Align items
## items-center, items-stretch, items-start, items-end, items-baseline
## important to note that align items only works when flex has nowrap property


## Align content
## content-center, content-start, content-end, content-between, content-around, content-evenly.
## Content between the items when flex-wrap comes into play.





## All the below properties are of child properties.

Css properties
align-self: auto ->  self-auto
align-self: flex-start  -> self-start
align-self: flex-end -> self-end
align-self: center  -> self-start
align-self: stretch  ->  self-stretch


flex-grow: 0  ->  flex-grow-0
flex-grow: 1  ->   flex-grow


flex-shrink: 0  ->  flex-shrink-0
flex-shrink: 1  ->   flex-shrink


flex: 1 1 0%    flex-1
flex: 1 1 auto   flex-auto
flex: 0 1 auto    flex-initial
flex: auto    flex-none

                    customize {
flex-basic: 33%     '1/3' : `1 1 33%`   flex-1/3
flex-basic: 65%     `2/3` : `1 1 65%`   flex-2/3
flex-basic: 25%      `1/4` : `1 1 25%`   flex-1/4


order: 1    order-1
order: 2    order-2
order: 12   order-12
order: -9999  order-first
order: 9999   order-last
order: 0     order-none











