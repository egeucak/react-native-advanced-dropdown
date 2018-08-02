# React Native Advanced Dropdown
A react native component for creating highly customizable, paginated and searchable dropdown menus.

Advanced dropdown menu is born with need of a searchable and paginated dropdown menu.

[![npm version](https://badge.fury.io/js/react-native-advanced-dropdown.svg)](https://badge.fury.io/js/react-native-advanced-dropdown)

## Installation

```bash
npm install --save react-native-advanced-dropdown
```

## Try it out

For trying, you can check the example app at [https://github.com/egeucak/Advanced-Dropdown-Menu-Example](https://github.com/egeucak/Advanced-Dropdown-Menu-Example).

## Documentation [WIP]

###Props

| Prop          | Required | Default | Type       | Explanation                                                                                                                      |
|---------------|----------|---------|------------|----------------------------------------------------------------------------------------------------------------------------------|
| data          | Yes      | na      | [Object]   | Array of objects, each object must have a "label" key. Objects can also have an optional func field, which will be run on click. |
| title         | Yes      | na      | String     | The title to be shown on the label of dropdown button                                                                            |
| pagination    | No       | true    | bool       | Pagination can be disabled.                                                                                                      |
| perPage       | No       | 999     | integer    | Amount of items to be shown on one page.                                                                                         |
| searchEnabled | No       | true    | bool       | Search function searchs with respect to labels of data objects                                                                   |
| dropdownStyle | No       | {}      | CSS object | CSS to be injected in dropdown menu                                                                                              |
| buttonStyle   | No       | {}      | CSS object | CSS to be injected in button that opens dropdown menu 