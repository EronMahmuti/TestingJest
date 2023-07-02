## Login Component Tests

This repository contains tests for the Login component using Jest.

## Setup

1. Clone the repository:

   ```[bash]
   git clone <repository-url>

2. Install the dependencies:

[bash]
# pnpm install

## Running the Tests
To run the tests, use the following command:
[bash]
# pnpm test

The test suite will be executed, and you will see the test results in the console.
If you want to fail a test just change component [Login.jsx] and you can find tests functions in [LoginInputs.text.js]

## Test Descriptions
- `username input should be rendered:` Verifies that the username input element is rendered.
- `password input should be rendered:` Verifies that the password input element is rendered.
- `button should be rendered:` Verifies that the button element is rendered.
- `username input should be empty:` Verifies that the username input element is empty.
- `password input should be empty:` Verifies that the password input element is empty.
- `button should be disabled:` Verifies that the button element is disabled.
- `loading should not be rendered:` Verifies that the loading indicator is not rendered.
- `login should be written correctly:` Verifies that the login button text is correct.
- `error message should not be visible:` Verifies that the error message element is not visible.
- `username input should change:` Verifies that the username input value changes correctly.
- `password input should change:` Verifies that the password input value changes correctly.
- `button should not be disabled when inputs exist:` Verifies that the button is not disabled when inputs have values.
- `loading should be rendered when click:` Verifies that the loading indicator is rendered when the button is clicked.
- `loading should not be rendered after fetching:` Verifies that the loading indicator is not rendered after fetching data.
- `user should be rendered after fetching:` Verifies that the user item is rendered after fetching data.


