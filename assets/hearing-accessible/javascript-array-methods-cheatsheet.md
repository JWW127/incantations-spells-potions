new Array(3).fill(🧀) // creates ['🧀','🧀','🧀']
Array.from('🌮🍒🍩') // creates array from a string ['🌮','🍒','🍩']
Array.of('🌮','🍒','🍩') // creates an array from args ['🌮','🍒','🍩']

['🌮','🍒','🍩'].pop() // returns last element in array 🍩
['🌮','🍒','🍩'].push('🧀') // add new elment to the end array and return length
['🌮','🍒','🍩'].indexOf('🍩') // returns the index of 🍩 which is 2
['🌮','🍒','🍩'].join('$')          // creates string of elements with $ separating '🌮$🍒$🍩'
['🌮','🍒','🍩'].concat(['🌮','🍒','🍩']) // combines arrays ['🌮','🍒','🍩','🌮','🍒','🍩']
['🌮','🍒','🍩'].forEach(item => console.log(item)) // executes a function on each element indivudually. logs🌮 logs🍒 logs🍩
['🌮','🍒','🍩'].map((item) => (true ? item : 'false')) // iterate over each item if true return the item in our new array ['🌮','🍒','🍩']
['🌮','🍒','🍩'].find(item => item === '🍩') // returns element whos value is '🍩' // returns 🍩
['🌮','🧀','🍒','🧀','🍩','🧀'].filter(item => item === '🧀') // returns a new array with matched items ['🧀','🧀','🧀']
['🌮','🍒','🍩'].copyWithin(0,2) // replace value at [0] with the value at [2] ['🍩','🍒','🍩']
['🌮','🍒','🍩'].reverse() // reverse the order of the array ['🍩','🍒','🌮']
['🌮','🍒','🍩'].includes('🍩') // does the array contain '🍩' return true if so
['🌮','🍒','🍩'].splice(1,1,'🧀') // at key 1, delete 1, and insert 🧀, ['🌮','🧀','🍩']
['🌮','🍒','🍩'].slice(0,2) // return values in array from 0-2 but not including 2 ['🌮','🍒',]
['🌮','🍒','🍩'].shift() // remove the first elemenet of an the array, and return the value of that element '🌮'
['🌮','🍒','🍩'].unShift('🧀') // add new element to the beginning of the array and return the length of the array which is 4
['🌮','🍒','🍩'].reduce((accumulator, current) => accumulator + current, '🧀'initial) // iterate over array add current item to accumulator ['🧀','🍩','🍒','🌮']
['🌮','🍒','🍩',['🧀','🧀']].flat() //returns a flattened array/sub-array ['🌮','🍒','🍩','🧀','🧀']
['🌮','🍒','🍩'].some('🌮') //checks to see if any of the array evaluates to true and returns a boolean //true
['🌮','🍒','🍩'].isArray() //checks to see if it is an array //true
