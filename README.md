# free.react

> Fast conversion for uncontrolled components

```jsx
<Free 
    render={
        (item) => ( <input {...item('user')} /> )
    }
/>

<Free 
    render={
        (item) => ( <Select {...item('type')} /> )
    }
/>

<Free 
    render={
        (item) => ( <Count {...item('type', {transprops: 'count', change: 'onMount' })} /> )
    }
/>
```
