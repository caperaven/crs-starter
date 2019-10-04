# CRS Starter

## Introduction

This is a small template project to help with library development.
It includes all the required building blocks already set up ready to use.
There are a couple of conventions to consider.

1. Source code is in the "src folder"
1. Tests have the same name as the src file but also includes ".test" at the end of the name. For example "my-class.test.js"
1. index.js found in the src folder is the bundling entry and exports the library api using the export function

## Standard features included

1. Jest tests configured for ES6
1. Rollup bundling with minification using Tensor
 
## Scripts

The package.json file has two scripts defined for common use.

1. Test
1. Bundle

## Tests

Jest is set up to allow es6 using Babel.  
It also includes code completion.