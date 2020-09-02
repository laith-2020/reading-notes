
# Welcome To Read 1  401 Course 

 * The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

 * The reduce() method reduces the array to a single value.

 The reduce() method executes a provided function for each value of the array (from left-to-right).
 
 The return value of the function is stored in an accumulator (result/total).

 * SuperAgent
 SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!

```request
   .post('/api/pet')
   .send({ name: 'Manny', species: 'cat' })
   .set('X-API-Key', 'foobar')
   .set('Accept', 'application/json')
   .then(res => {
      alert('yay got ' + JSON.stringify(res.body));
   });
   ```

* Async/await
There’s a special syntax to work with promises in a more comfortable fashion, called “async/await”. It’s surprisingly easy to understand and use.

So, async ensures that the function returns a promise, and wraps non-promises in it. Simple enough, right? But not only that. There’s another keyword, await, that works only inside async functions, and it’s pretty cool.

The keyword await makes JavaScript wait until that promise settles and returns its result.


![](https://miro.medium.com/max/3200/1*xdo0UBpyszvD7-7EH4TkIA.png)

What is Node.js?
Node.js is an open source server environment
Node.js is free
Node.js runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.)
Node.js uses JavaScript on the server


Node.js is a JavaScript runtime environment. Sounds great, but what does that mean? How does that work?

The Node.js run-time environment includes everything you need to execute a program written in JavaScript.


![](https://miro.medium.com/max/548/1*o474X_2eTiF2Dnn39h6Rjg.jpeg)
<hr>
npm is the world’s largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well.


Use npm to . . .
Adapt packages of code for your apps, or incorporate packages as they are.
Download standalone tools you can use right away.
Run packages without downloading using npx.
Share code with any npm user, anywhere.
Restrict code to specific developers.
Create Orgs (organizations) to coordinate package maintenance, coding, and developers.
Form virtual teams by using Orgs.
Manage multiple versions of code and code dependencies.
Update applications easily when underlying code is updated.
Discover multiple ways to solve the same puzzle.
Find other developers who are working on similar problems and projects.