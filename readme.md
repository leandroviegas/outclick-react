## Install

```
npm install --save outclick-react
```

or
```
yarn add outclick-react
```

## Usage

```tsx
import OutClick from 'outclick-react';
 
function App() {
  return (
    <OutClick
      callback={() => {
        alert('You clicked outside this component!!!');
      }}>
      Hello World
    </OutClick>
  );
}
```