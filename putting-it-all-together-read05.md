1. **How would you break a mock into a component heirarchy?**
2. FilterableProductTable, SearchBar, ProductTable, ProductCategoryRow, ProductRow.

2. **What is the single responsibility principle and how does it apply to components?**
3. The single responsibility principle is when a component should ideally only do one thing.

3. **What does it mean to build a ‘static’ version of your application?**
4. It means to do a lot of typing but not much thinking to render your data model. Build components that reuse other components and pass data using props.

4. **Once you have a static application, what do you need to add?**
5. Props.

5. **What are the three questions you can ask to determine if something is state?**
6. Is it passed in from a parent via props? Does it remain unchanged over time? Can you compute it based on any other state or props in your component?

6. **How can you identify where state needs to live?**
7. Identify every component that renders something based on that state, Find a common owner component (a single component above all the components that need the state in the hierarchy),
   Either the common owner or another component higher up in the hierarchy should own the state, If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
