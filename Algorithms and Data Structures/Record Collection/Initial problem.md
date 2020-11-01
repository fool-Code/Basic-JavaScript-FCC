My problem with this code was to follow the structure, and understand what's happening. 
So first I tried and failed miserable... I couldn't figured what's was asking.
I will try explain how I figure out to solve.
Below are the instructions:

You are given a JSON object representing a part of your musical album collection. Each album has a unique id number as its key and several other properties. 
Not all albums have complete information.

You start with an updateRecords function that takes an object like collection, an id, a prop (like artist or tracks), and a value. 
Complete the function using the rules below to modify the object passed to the function.

    Your function must always return the entire object.
    If prop isn't tracks and value isn't an empty string, update or set that album's prop to value.
    If prop is tracks but the album doesn't have a tracks property, create an empty array and add value to it.
    If prop is tracks and value isn't an empty string, add value to the end of the album's existing tracks array.
    If value is an empty string, delete the given prop property from the album.

Note: A copy of the collection object is used for the tests.

First of all I recommend you read how JSON works seeing this https://www.json.org/json-en.html follow the diagram after read the instructions.
Then read the instructions and see what tests will take to pass through this challange, this can help too.
If this wouldn't help you, I recommend you do the previous basic JavaScript from freecodecamp.
Don't need to think hard, it's an easy instructions and easy code to do.

Feel free to send any help.
