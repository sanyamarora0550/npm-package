#THIS PACKAGE ALLOWS YOU TO REMOVE DUPLICATES FROM AN ARRAY OF OBJECT BASED UPON KEY YOU PROVIDE.
---------------------------------------------------------------------------------------------------------------------
How to use :
---------------------------------------------------------------------------------------------------------------------
 const { removeDuplicates } = require('remove-duplicates-from-an-array-of-object');
console.log(removeDuplicates([{
    key: 1,
    value: 1
},
{
    key: 2,
    value: 2
},
{
    key: 2,
    value: 4
}], 'key'));
---------------------------------------------------------------------------------------------------------------------
O/P: [ { k: 1, v: 1 }, { k: 2, v: 2 } ]
