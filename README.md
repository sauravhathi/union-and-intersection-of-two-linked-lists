# Union and Intersection of Two Linked Lists

This is a simple web app to find the union and intersection of two linked lists. The app is built using HTML, CSS and JavaScript. The app is hosted on [Netlify](https://www.netlify.com/).

## Demo

#### https://sauravhathi.github.io/union-and-intersection-of-two-linked-lists

#### HomePage

![image](https://user-images.githubusercontent.com/61316762/200388483-cc85b564-bb04-4bdb-bbdd-7d46d4e549e8.png)

#### UI

![image](https://user-images.githubusercontent.com/61316762/200388593-36e82a26-13b4-496b-a234-059a3f7211bd.png)

#### Output

![image](https://user-images.githubusercontent.com/61316762/200389499-7e87a3d3-3301-4c59-9989-d13774248d9c.png)

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
