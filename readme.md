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
      Callback={() => {
        alert('You clicked outside of this component!!!');
      }}>
      Hello World
    </OutClick>
  );
}
```