## What is a Chakra UI?

Chakra UI is a simple, modular and accessible component library that gives you the building blocks you need to build your React applications.


## Is Chakra UI better than material UI?

Material UI is much better when it comes to performance and reliability. Chakra UI is not bad in terms of performance, but it can lag a bit on data-heavy, large-enterprise websites.

## How to use Chakra UI?

```
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
```
#### After installing Chakra UI, you need to set up the ChakraProvider at the root of your application. This can be either in your index.jsx, index.tsx or App.jsx depending on the framework you use.



```
import * as React from 'react'

// 1. import `ChakraProvider` component
import { ChakraProvider } from '@chakra-ui/react'

function App() {
  // 2. Wrap ChakraProvider at the root of your app
  return (
    <ChakraProvider>
      <TheRestOfYourApplication />
    </ChakraProvider>
  )
}

```