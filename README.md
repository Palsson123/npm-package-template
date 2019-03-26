# npm-package-template
## Usage

### In a React functional component:

```tsx
import React from 'react'
import { useExample } from 'npm-package-template'

function Example() {
  const isExample = useExample()
  return (
    <>
      {isExample ? 'This is an example' : 'This is not an example'}
    </>
  )
}
```