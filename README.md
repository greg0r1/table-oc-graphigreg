[![forthebadge](https://forthebadge.com/images/badges/cc-0.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)

# table-rc-oc-2022

A simple table for your React app.

### Compatibility

Your project needs to use React 18.0.0 or later. If you use an older version of React, please refer to the table below to find a suitable table-rc-oc-2022 version.

| React version | Newest compatible table-rc-oc-2022 version |
| ------------- | ------------------------------------------ |
| ≥18.0.0       | latest                                     |
| ≥18.0.0       | 1.0.0                                      |

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### Installation

Add table-rc-oc-2022 to your project by executing `npm i table-rc-oc-2022` or `yarn add table-rc-oc-2022`.

### Usage

Here's an example of basic usage:

```js
import React, { useState } from 'react'
import Table from 'table-rc-oc-2022'


function MyApp() {
    const labels = ['First Name','Last Name','Start Date','Department','Date of Birth','Street','City','State','Zip Code']
    const employees = [
        {
            firstName: 'John',
            lastName: 'Doe',
            startDate: '01/01/2022',
            department: 'Aude',
            dateOfBirth: '01/01/1980',
            street: '1 rue Larue',
            city: 'Nice',
            state: 'France',
            zipCode: '06000',
        },
        {
            firstName: 'Jane',
            lastName: 'Doe',
            startDate: '01/01/2022',
            department: 'Loire',
            dateOfBirth: '01/01/1981',
            street: '1 rue Marue',
            city: 'Paris',
            state: 'France',
            zipCode: '75000',
        }
    ]

  return (
    <div>
      <Table data={dataList} labels={labels} numberOfItemsByPage={10} />
    </div>
  )
}
```

### Custom styling

Styles loaded by the default entry file are `table-rc-oc-2022/dist/styles.css`. You can copy them to your project to build your own upon them.

## User guide

### table-rc-oc-2022

Displays an input field complete with custom inputs, native input, and a calendar.

#### Props

| Prop name  | Description                           | Example values | Default value                                   |
| ---------- | ------------------------------------- | -------------- | ----------------------------------------------- |
| data       | Display rows data.                    | n/a            | Array of strings: `["class1", "class2 class3"]` |
| labels     | Display rows data.                    | n/a            | Array of strings: `["class1", "class2 class3"]` |
| pagination | Displays the number of rows per page. | 10             | Number: 10                                      |

## Author

<table>
  <tr>
    <td>
      <img src="https://github.com/greg0r1.png?s=100" width="100">
    </td>
    <td>
      Greg0r1
    </td>
  </tr>
</table>
