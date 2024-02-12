## Gutenberg Block Development Boilerplate

It works like a boilerplate for start developing custom **Gutenberg Block**. This package has been made with
**@wordpress/scripts**. It is almost similar to the **@wordpress/create-block**, but there is a huge differce between them.

## How to Start Your Development

**Simply clone the Repo. in your WordPress plugin directory. Now install the plugin.**

It creates a new plugin with a simply dummy cusotm gutenberg block
and a custom block category. The name of the dummy block is **Bootsrap Block** and you will find it under **BOILERPLATE** cateogry.

Now, it is time to run the following command to install npm, simply run the following command in this boilerplate folder (You may rename the folder as per your need).

```
$ npm install
```

As a result, node_modules will be loaded and you can start developing your own block. To start editing & watching the effect, run the following command.

```
$ npm start
```

For production of your project, you have to build the whole project. So, to build the project, run the following command-

```
$ npm run build
```

## New Block Registration Process

If you want to add a new block to your plugin, you must have to follow these steps:-

-   **Step-1:** Create a new folder inside **blocks** directory. You will find it here: **src/blocks**.
    Suppose, I want to create a **box** block. So, my folder name will be **box** and it will be found in **src/blocks/box**

-   **Step-2:** Keep all necessary blocks infor inside your block folder. In my case, I will keep all blocks files in my **box** folder.
    if you don't know how to write codes for your custom block, you can enjoy this [tutorial series](https://www.youtube.com/watch?v=5WiyRvPNyng&list=PL-OcaXZwrwuIWrLLI3_d1TQdcTbDEffAv)

-   **Step-3:** Import your block's **index.js** file in the main **index.js** file. You will find the file here: **src/index.js**. Already dummy block's file has been imported there. see the example. It will look like this: **import './blocks/box/index';**

-   **Step-4:** Open your plugin main php file, in our boilerplate, its name is **plugin.php** (you can rename it as per your need). now find out the block register function. In our boilerplate, its name is **boilerplate_register_block()**.
    Now, simply add the new block name inside the **blocksList** array.

**NOTE**: \*It is highly recommended using your own prefix. in case of boilerplate, the prefix was **boilerplate** and **BOILERPLATE\***

## Better Practice

It is better to run **npm run build** firstly for new block registration, then simply run **npm start** to update editing.

### Acknowledgements

-   [Gutenberg Developer Handbook](https://developer.wordpress.org/block-editor/)
-   [Block Plugin Checker](https://wordpress.org/plugins/developers/block-plugin-validator/)
-   [WordPress Components](https://wordpress.github.io/gutenberg/)

### Authors
 Raihan Islam - [@Raihan](https://www.github.com/raihancsegit)


### 🚀 About Me

I am a software Engineer .My professional experience includes using programming languages such as JavaScript ,Node Js,Express Js,React Js, Laravel, PHP, WP.
From the last 3 years, I am focused on **Minimal WordPress Theme** development and developing **Custom Gutenberg Blocks** with **Gutenberg Native Components**.
I am available for any freelance project or hiring. You are most welcomed to [Contact Me](https://raihan.website)

## Feedback

If you have any feedback, please reach out to us at raihanislam.cse@gmail.com

