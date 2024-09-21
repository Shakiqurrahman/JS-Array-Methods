# JavaScript Array Methods

## 1. `push()`
- **Purpose**: Adds one or more elements to the end of an array.
- **Returns**: New length of the array.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.push(4); // [1, 2, 3, 4]
    ```

## 2. `pop()`
- **Purpose**: Removes the last element from an array.
- **Returns**: The removed element.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.pop(); // [1, 2], returns 3
    ```

## 3. `shift()`
- **Purpose**: Removes the first element from an array.
- **Returns**: The removed element.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.shift(); // [2, 3], returns 1
    ```

## 4. `unshift()`
- **Purpose**: Adds one or more elements to the beginning of an array.
- **Returns**: New length of the array.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.unshift(0); // [0, 1, 2, 3]
    ```

## 5. `concat()`
- **Purpose**: Merges two or more arrays without modifying the original arrays.
- **Returns**: A new array.
- **Example**:
    ```js
    let arr1 = [1, 2];
    let arr2 = [3, 4];
    let result = arr1.concat(arr2); // [1, 2, 3, 4]
    ```

## 6. `slice()`
- **Purpose**: Returns a shallow copy of a portion of an array without modifying the original array.
- **Returns**: A new array.
- **Example**:
    ```js
    let arr = [1, 2, 3, 4];
    let sliced = arr.slice(1, 3); // [2, 3]
    ```

## 7. `splice()`
- **Purpose**: Changes the contents of an array by removing, replacing, or adding elements.
- **Returns**: An array of removed elements.
- **Example**:
    ```js
    let arr = [1, 2, 3, 4];
    arr.splice(1, 2, "a", "b"); // [1, "a", "b", 4]
    ```

## 8. `forEach()`
- **Purpose**: Executes a function once for each array element.
- **Returns**: `undefined`.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.forEach(num => console.log(num)); // Logs 1, 2, 3
    ```

## 9. `map()`
- **Purpose**: Creates a new array with the results of calling a provided function on every element in the array.
- **Returns**: A new array.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    let mapped = arr.map(num => num * 2); // [2, 4, 6]
    ```

## 10. `filter()`
- **Purpose**: Creates a new array with elements that pass a test provided by a function.
- **Returns**: A new array.
- **Example**:
    ```js
    let arr = [1, 2, 3, 4];
    let filtered = arr.filter(num => num > 2); // [3, 4]
    ```

## 11. `reduce()`
- **Purpose**: Executes a reducer function on each element of the array, resulting in a single output value.
- **Returns**: The accumulated result.
- **Example**:
    ```js
    let arr = [1, 2, 3, 4];
    let sum = arr.reduce((acc, num) => acc + num, 0); // 10
    ```

## 12. `find()`
- **Purpose**: Returns the first element in the array that satisfies the provided testing function.
- **Returns**: The found element or `undefined`.
- **Example**:
    ```js
    let arr = [1, 2, 3, 4];
    let found = arr.find(num => num > 2); // 3
    ```

## 13. `findIndex()`
- **Purpose**: Returns the index of the first element in the array that satisfies the testing function.
- **Returns**: The index of the found element or `-1` if not found.
- **Example**:
    ```js
    let arr = [1, 2, 3, 4];
    let index = arr.findIndex(num => num > 2); // 2
    ```

## 14. `some()`
- **Purpose**: Tests whether at least one element in the array passes the test implemented by the provided function.
- **Returns**: `true` if at least one element passes the test, otherwise `false`.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    let hasEven = arr.some(num => num % 2 === 0); // true
    ```

## 15. `every()`
- **Purpose**: Tests whether all elements in the array pass the test implemented by the provided function.
- **Returns**: `true` if all elements pass the test, otherwise `false`.
- **Example**:
    ```js
    let arr = [2, 4, 6];
    let allEven = arr.every(num => num % 2 === 0); // true
    ```

## 16. `includes()`
- **Purpose**: Determines whether an array contains a certain value.
- **Returns**: `true` or `false`.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.includes(2); // true
    ```

## 17. `sort()`
- **Purpose**: Sorts the elements of an array in place and returns the sorted array.
- **Example**:
    ```js
    let arr = [3, 1, 2];
    arr.sort(); // [1, 2, 3]
    ```

## 18. `reverse()`
- **Purpose**: Reverses the array in place.
- **Returns**: The reversed array.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    arr.reverse(); // [3, 2, 1]
    ```

## 19. `join()`
- **Purpose**: Joins all elements of an array into a string.
- **Returns**: A string.
- **Example**:
    ```js
    let arr = [1, 2, 3];
    let joined = arr.join("-"); // "1-2-3"
    ```

## 20. `flat()`
- **Purpose**: Flattens a nested array to the specified depth.
- **Returns**: A new array.
- **Example**:
    ```js
    let arr = [1, [2, [3, 4]]];
    let flat = arr.flat(2); // [1, 2, 3, 4]
    ```
### Thank You!
