# Day 9 readings

1. Functional programing focuses on unchanging state.

2. a pure function returns the same result given the same argument. it will not cause any parameter passed into it to change.

3. the benefit is that you don't need to mock anything up and you can expect inherent values when putting data in and should have to wounder what it will return.

4. an immutable object is an object that is unchanging. if you wanted to change it you can't.

5. pure functions + immutable data = referential transparency. If a function consistently gives out the same result for the same input it is referentially transparent.

## Node js

1. a module is code separated out into a separate file.

2. require lets you pass the module to other modules that require it.

3. set whatever you want to be made Global as module.exports in the original file.

4. in the file which you are grabbing the Global variable from yuo have to set it to a variable equal to the source files path.