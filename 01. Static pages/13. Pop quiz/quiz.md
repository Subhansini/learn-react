1. Where does React put all of the elements I create in JSX when I 
   call `root.render()`?

all of the eelements I render get put inside the div with the id of root(or whatever we mention)

2. What would show up in my console if I were to run this line of code:
```
console.log(<h1>Hello world!</h1>)
```
An object, unlike creating a HTML element in vanilla DOM JS, what gets created from the JSX we have 
in our React code is a plain JS object that react uses to fill in the view


3. What's wrong with this code:
```
root.render(
    <h1>Hi there</h1>
    <p>This is my website!</p>
)
```
We can only render 1 parnt element at a time & that parent element can have as many children required
eg. there should be <div>/<section>/<main> after "(" & inside that we can put as many req elements

4. What does it mean for something to be "declarative" instead of "imperative"?

Insted of giving detailed instructions about doin a tak we rely on something(framework/library) to do
the heavy uplifting for us.
eg. insted of giving the whole recipe or making the sandwich(imperative) we rely on the cook that that
he will do his work and deliver the correct product(declaritive)
React is declaritive & vanilla js is imperative

6. What does it mean for something to be "composable"?
Breaking larger section into smaller and effiect ones OR We have smaller pieces that can be put together
to make something greater than the individual peieces
