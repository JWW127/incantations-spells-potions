# breakpoints

sm: 640px
md: 768px
lg: 1024px
xl: 1280px
2xl: 1536px

# sizes

1 = .25rem
2 = .50rem
3 = .75rem
4 = 1.0rem
8 = 2.0rem
full = 100%

# displays

hidden
block
inline-block
flex
grid

# overflow

overflow-hidden, scroll, auto, visible
overflow-x-hidden, scroll, auto, visible
overflow-y-hidden, scroll, auto, visible

# position

fixed
absolute
relative
sticky

# placement

top-#
right-#
bottom-#
left-#

# visibility

visible
invisible

# z-index

z-#

# padding

p-#
px-#
py-#
pt-#
pr-#
pb-#
pl-#

# margin

m-#
mx-#
my-#
mt-#
mr-#
mb-#
ml-#

# background-color

bg-transparent
bg-black
bg-white
bg-gray-50,100,200,300-900
bg-red-50,100,200,300-900
bg-yellow-50,100,200,300-900
bg-green-50,100,200,300-900
bg-blue-50,100,200,300-900
bg-indigo-50,100,200,300-900
bg-purple-50,100,200,300-900
bg-pink-50,100,200,300-900

# background-gradient

/_[bg-gradient-to-location][start-color][middle-color][end-color]_/
bg-gradient-to-r from-color-# via-color-# to-color-#

# box-shadow

shadow-sm
shadow-md
shadow-lg
shadow-xl
shadow-2xl

# opacity

opacity-#

# background blend

bg-blend-normal
bg-blend-lighten
bg-blend-darken

# Flexbox

flex-[attribute]
flex-row, flex-row-reverse
flex-column, flex-column-revers
flex-wrap, flex-wrap-reverse
flex-grow-#
flex-shrink-#
order-first
order-last
order-#

# box-aligment

## justify content

justify-start
justify-end
justify-center
justify-between
justify-around
justify-evenly

## justify items

justify-items-stretch

## justify self

justify-self-start
justify-self-end
justify-self-center

## align content

content-start
content-center
content-end

## align items

items-start
items-center
items-end

## align self

self-start
self-center
self-end

# sizing

## width

w-#
w-#/# "1/2 = 50%"
w-full "100%"
w-max "max-content"
w-screen "100vw"
w-[27vw] "arbitrary custom value"
min-w-# "minimum width"
max-w-# "max width"
max-w-xs "20rem-320px"
max-w-sm "24rem-384px"
max-w-md "28rem-448px"
max-w-lg "32rem-512px"
max-w-xl "36rem-576px"
max-w-2xl "42rem-672px"
max-w-3xl "48rem-768px"
max-w-4xl "56rem-896px"
max-w-5xl "64rem-1024px"

## height

h-#
h-#/# "1/2 = 50%"
h-full "100%"
h-max "max-content"
h-screen "100vw"
h-[27vh] "arbitrary custom value"
min-h-# "minimum height"
max-h-# "max height"
max-h-screen "100vh"

# borders

## width

border-#
border-t-#
border-r-#
border-b-#
border-l-#

## color

border-yourColor-colorWeight

## style

border-solid
border-dashed
border-dotted
border-double

## radius

rounded-sm "2px"
rounded-md "4px"
rounded-lg "8px"
rounded-xl "12px"
rounded-2xl "16px"
rounded-3xl "24px"
rounded-full "circle"

## ring

ring-#
ring-youColor-colorWeight

# typography

## color

text-yourColor-colorWeight

## size

text-xs
text-sm
text-lg
text-2xl
text-9xl

## family

font-fontFamily

## weight

font-thin
font-extralight
font-light
font-normal
font-medium
font-semibold
font-bold
font-extrabold
font-black

## list style

list-none
list-disc
list-decimal

## placeholder

placeholder-yourColor-colorWeight
placeholder-opacity-#

## text-align

text-left
text-center
text-right
text-justify

## text-decoration

underline
line-through
no-underline
