[![forthebadge](https://forthebadge.com/images/badges/cc-0.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)

# table-oc-graphigreg

A simple table for your React app.

### Compatibility

Your project needs to use React 18.0.0 or later. If you use an older version of React, please refer to the table below to find a suitable table-oc-graphigreg version.

| React version | Newest compatible table-oc-graphigreg version |
| ------------- | --------------------------------------------- |
| ≥18.0.0       | latest                                        |
| ≥18.0.0       | 0.2.9                                         |

#
### Installation

Add table-oc-graphigreg to your project by executing `npm i table-oc-graphigreg` or `yarn add table-oc-graphigreg`.

### Usage

Here's an example of basic usage:

```js
import React from 'react'
import { Table } from 'table-oc-graphigreg'
import PropTypes from 'prop-types'

function App() {
  return (
    <div>
      <Table data={data} labels={labels} pagination={10} />
    </div>
  )
}
```

### Custom styling

Styles loaded by the default entry file are `table-oc-graphigreg/dist/styles.css`. You can copy them to your project to build your own upon them.

## User guide

### table-oc-graphigreg

Displays an input field complete with custom inputs, native input, and a calendar.

#### Props

| Prop name  | Description                           | Example values | Default value                                                                                                                                                                                                  |
| ---------- | ------------------------------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| data       | Display rows data.                    | n/a            | Array of objects: `[{firstName: 'John',lastName: 'Doe',startDate: '01/01/2022', department: 'Aude',dateOfBirth: '01/01/1980',street: '1 rue Larue',city: 'Nice',state: 'France',zipCode: '06000',}]`           |
| labels     | Display rows data.                    | n/a            | Array of strings: `['First Name','Last Name','Start Date','Department','Date of Birth','Street','City','State','Zip Code',]`                                                                                   |
| pagination | Displays the number of rows per page. | 10             | Number: 10                                                                                                                                                                                                     |

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
