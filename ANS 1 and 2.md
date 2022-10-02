# steeleye-assigment

# Q1- Explain what the simple List component does.

List is used to store multiple items of the same and different datatype under a variable. It is basically an array. We can perform various operations on it such as .map() to loop over the list/array to list down all the elements.
The wrappedListComponent returns a memoized components list. By memoized it states that it doesn't re-render unnecessarily
that is if the component's props don't change it doesn't re-render. The memo is used to make website speed more efficient and perform better. As long as the title and release date properties are the same between renderings, React reuses the memoized content.

# Q2-What problems / warnings are there with code?

1. Uncaught TypeError: prop_types_WEBPACK_IMPOR TED_MODULE_2_default(...).s hapeof is not a function

2. factoryWithTypeCheckers.js:183 Uncaught Invariant Violation: Calling PropTypes validators directly is not supported by the prop-types package. Use PropTypes.checkPropTypes() to call them.

3. Uncaught TypeError: Cannot read properties of null (reading 'map')

4. The above error occurred in the component: at WrappedListComponent

5. Warning: Each child in a list should have a unique "key" prop.

6. react-dom.development.js:86 Warning: Failed prop type: Invalid prop isSelected of type function supplied to WrappedSingleListItem, expected `boolean

7. Uncaught TypeError: setSelectedIndex is not a function.

8. react_devtools_backend.js:4026 Warning: Failed prop type: Invalid prop isSelected of type number supplied to WrappedSingleListItem,
expected boolean.

