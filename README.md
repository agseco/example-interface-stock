# Example Interface (Stock)

This is an example interface for Directus 7.

You can use this repo as a starting point for creating your own custom interface

## Requirements

The interfaces uses [Parcel](https://parceljs.org/) to build the `.vue` files to (Directus compatible) `.js` files. 

In order to run Parcel, you need [Node.js](https://nodejs.org) (preferably LTS) installed.

## Installation

Clone this repo and run `npm install` to install the npm dependencies.

## Usage

To build the `.vue` files to make them ready for use in Directus, you can run `npm run build`. This will generate everything in the dist folder. To install this interface into Directus, create a new folder in the `/public/extensions/custom/interfaces/` folder called `my-interface` (or any other name) and put the contents of the `dist` folder in that newly created `my-interface` folder. 
