# Testing Package

This package is a demonstration for creating and consuming private npm packages.  

## Installation

1. **Install the package:**
   - Run the following command in your project directory:

     ```bash
     npm install @shankar-b/my-test-package@1.0.0
     ```

## Usage

This package provides a `privateGreet` function that generates a personalised greeting.

```javascript
const privateGreet = require('@shankar-b/my-test-package');

const message = privateGreet('Anand');
console.log(message); // Output: "Greetings, Anand! This is a private message."
```

**Example (index.js):**

```javascript
// test.js
const privateGreet = require('@shankar-b/my-test-package');
const message = privateGreet('Anand');
console.log(message); 
```

## Dependencies

- `@shankar-b/my-test-package`: This is the actual private package containing the `privateGreet` function.

## License

This package is licensed under the ISC License.
