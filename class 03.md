# Read class 03
## we have to read about terms and built in function to understand it and how to use it.

1. What does .map() return?
> returns a completely new array with the same amount of data and modified elements.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
> we can use map or forEach to loop through an array for example:
 
 {this.state.users.map((user) => (
          <User
            name={`${user.name.first} ${user.name.last}`}
            avatar={user.picture.thumbnail}
            email={user.email}
            key={user.id.value}
          />
        ))}
  
3. Each list item needs a unique _key.

4. What is the purpose of a key?
> to determine whether list items have been updated, revised, or removed or We can assert that keys are employed to provide an identity to the list items.


5. What is the spread operator?
> refers to expanding an iterable object into a list of arguments using a three-dot ellipsis..

6. List 4 things that the spread operator can do?
 - Combining objects
 - Concatenating or combining arrays
 - Copying an array
 - Adding an item to a list.
 
7. Give an example of using the spread operator to combine two arrays?
 - const array1 = [1,2,3,4,5]
 - const array2 = [6,7,8,9,10]
 - const combinearray = [...array1,...array2]

8. Give an example of using the spread operator to add a new item to an array.
const str1 = ['a','b','c']
const str2 = ['d', 'e', ...str1]

9. Give an example of using the spread operator to combine two objects into one?
const first = {firstname: "hamzah"}
const last = {lastname: "Alddamas"}
const combine = {...first, ...last, age: "22"}

