# Union and Intersection of Two Linked Lists

This is a simple web app to find the union and intersection of two linked lists. The app is built using HTML, CSS and JavaScript. The app is hosted on [Netlify](https://www.netlify.com/).

## Demo


#### HomePage

#### UI

#### Output

## Algorithm

The algorithm used to find the union and intersection of two linked lists is as follows:

### Union

1. Create a new linked list. Let the new linked list be `unionList`.
2. Insert all the elements of the first linked list in `unionList`.
3. Traverse the second linked list. For every element being traversed, check if it is present in `unionList`. If the element is not present, then insert it at the end of `unionList`.
4. `unionList` contains the union of the two linked lists.

### Intersection

1. Create a new linked list. Let the new linked list be `intersectionList`.
2. Traverse the first linked list. For every element being traversed, check if it is present in the second linked list. If the element is present in the second linked list, then insert it at the end of `intersectionList`.
3. `intersectionList` contains the intersection of the two linked lists.