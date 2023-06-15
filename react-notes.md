# React Notes

- **Custom Components**
- ... are a way to create reusable components in React.
- **Proptypes**
    ... are a way to validate the props that are passed to a component. Here is a link to React docs on [PropTypes](https://react.dev/reference/react/Component#static-proptypes)
- **React.fragments**
  ... are a way to group a list of children without adding extra nodes to the DOM. Here is a link to React docs on [Fragments](https://react.dev/reference/react/Fragment)
  JSX expressions must have one parent element.
- **Styling React Comonents**
  ... there are 2 common ways to style react components
  - Inline styling
  - Using the className attribute
- **Forms**
    A synthetic event
    event.nativeEvent
    event.target.value
    refs
    controlled input
    uncontrolled input
    lazy state initialization: https://kentcdodds.com/blog/use-state-lazy-initialization-and-function-updates
    custom hook


- React Hooks
A large list of built-in hooks:
  1. useState
    - useState is a function that returns an array with 2 elements
    - used for updating state
    - useful for re-rendering a component when the state changes
    - common mistakes include not using the previous state when updating state || not using the updater function
    - implementing my own useState hook
    ```javascript
    function useState(initialValue) {
      let _val = initialValue;
      function setState(newVal) {
        _val = newVal;
      }
      return [_val, setState];
    }
    ```

  2. useEffect
   - useEffect is useful for localStorage, timers, subscriptions, etc.
   - A dependency list is useful because it allows you to specify when the effect should be run and stop it from running unnecessarily
  3. useContext
  4. useReducer
  5. useRef
  6. useCallback
  7. useMemo
  8. useImperativeHandle
  9.  useLayoutEffect
  10. useDebugValue
  11. useTransition
  12. useDeferredValue
  13. useMutableSource
  14. useOpaqueIdentifier
  15. useResponder
  16. useTransition
  17. useMutableSource
  18. useOpaqueIdentifier
  19. useDeferredValue
  20. useResponder
  21. useDeferredValue
  22. useResponder
  23. useTransition
  24. useMutableSource
  25. useOpaqueIdentifier
  26. useDeferredValue
  27. useResponder
  28. useTransition
  29. useMutableSource
  30. useOpaqueIdentifier

A good read about implementation of the hooks:
- https://medium.com/@ryardley/react-hooks-not-magic-just-arrays-cd4f1857236e


## Project 01

### Topics to be covered

## Project 02

### Topics to be covered

## Project 03

### Topics to be covered

## Project 04

### Topics to be covered

## Project 05

### Topics to be covered

## Project 06

### Topics to be covered

## Project 07

### Topics to be covered

## Project 08

### Topics to be covered

## Project 09

### Topics to be covered

## Project 10

### Topics to be covered

## Project 11

### Topics to be covered

## Project 12

### Topics to be covered

## Project 13

### Topics to be covered

## Project 14

### Topics to be covered

## Project 15

### Topics to be covered

## Project 16

### Topics to be covered

## Project 17

### Topics to be covered

## Project 18

### Topics to be covered

## Project 19

### Topics to be covered

## Project 20

### Topics to be covered

## Project 21

### Topics to be covered
