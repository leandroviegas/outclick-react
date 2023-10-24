## Install

```
npm install --save outclick-react
```

or
```
yarn add outclick-react
```

## Description

Library to handle outside clicks that also supports multiple components in the children.

## Usage

```tsx
import OutClick from 'outclick-react';
 
function App() {
  return (
    <OutClick
      onOutClick={() => {
        alert('You clicked outside this component!!!');
      }}>
      {/* Component or multiple components */}
    </OutClick>
  );
}
```