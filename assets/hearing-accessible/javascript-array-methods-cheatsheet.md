new Array(3).fill(ð§) // creates ['ð§','ð§','ð§']
Array.from('ð®ðð©') // creates array from a string ['ð®','ð','ð©']
Array.of('ð®','ð','ð©') // creates an array from args ['ð®','ð','ð©']

['ð®','ð','ð©'].pop() // returns last element in array ð©
['ð®','ð','ð©'].push('ð§') // add new elment to the end array and return length
['ð®','ð','ð©'].indexOf('ð©') // returns the index of ð© which is 2
['ð®','ð','ð©'].join('$')          // creates string of elements with $ separating 'ð®$ð$ð©'
['ð®','ð','ð©'].concat(['ð®','ð','ð©']) // combines arrays ['ð®','ð','ð©','ð®','ð','ð©']
['ð®','ð','ð©'].forEach(item => console.log(item)) // executes a function on each element indivudually. logsð® logsð logsð©
['ð®','ð','ð©'].map((item) => (true ? item : 'false')) // iterate over each item if true return the item in our new array ['ð®','ð','ð©']
['ð®','ð','ð©'].find(item => item === 'ð©') // returns element whos value is 'ð©' // returns ð©
['ð®','ð§','ð','ð§','ð©','ð§'].filter(item => item === 'ð§') // returns a new array with matched items ['ð§','ð§','ð§']
['ð®','ð','ð©'].copyWithin(0,2) // replace value at [0] with the value at [2] ['ð©','ð','ð©']
['ð®','ð','ð©'].reverse() // reverse the order of the array ['ð©','ð','ð®']
['ð®','ð','ð©'].includes('ð©') // does the array contain 'ð©' return true if so
['ð®','ð','ð©'].splice(1,1,'ð§') // at key 1, delete 1, and insert ð§, ['ð®','ð§','ð©']
['ð®','ð','ð©'].slice(0,2) // return values in array from 0-2 but not including 2 ['ð®','ð',]
['ð®','ð','ð©'].shift() // remove the first elemenet of an the array, and return the value of that element 'ð®'
['ð®','ð','ð©'].unShift('ð§') // add new element to the beginning of the array and return the length of the array which is 4
['ð®','ð','ð©'].reduce((accumulator, current) => accumulator + current, 'ð§'initial) // iterate over array add current item to accumulator ['ð§','ð©','ð','ð®']
['ð®','ð','ð©',['ð§','ð§']].flat() //returns a flattened array/sub-array ['ð®','ð','ð©','ð§','ð§']
['ð®','ð','ð©'].some('ð®') //checks to see if any of the array evaluates to true and returns a boolean //true
['ð®','ð','ð©'].isArray() //checks to see if it is an array //true
