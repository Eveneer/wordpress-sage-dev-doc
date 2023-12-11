# Installation

This file covers how to install roots/sage to a wordpress project.

### Prerequisites

In order to start wordpress theme development with roots/sage, please ensure you have the following installed:

1. (Node)[https://nodejs.org/en]
2. (Composer)[https://getcomposer.org]
3. (Yarn)[https://www.npmjs.com/package/yarn]

### Sage Installation

1. First create a base wordpress project, it can be downloaded from (the official wordpress site)[https://wordpress.org/download/]
2. Change directory to `project/wp-content/themes`
3. Run `composer create-project roots/sage your-theme-name`
4. Install all dependencies by running `yarn`
5. Update `bud.config.js` file with your local dev URL
6. Run `yarn build` to compile assets (**Note:** without compiling, the site will throw an error)

### Additional Notes

Roots/Sage also requires Roots/Acorn, but does not ship with it. This is to give the developer the freedom to include it in a manner which works best for the project/env.
