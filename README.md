# Awesome WordPress Playground [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[WordPress Playground](https://wordpress.org/playground/) is [WordPress](https://wordpress.org/) in one click. It's a platform that lets you run WordPress instantly on any device without a host. It’s your place to build, experiment, test, and grow.

This list collects awesome uses of playground and awesome tools to build with it.

## Contents

- [Official Links](#official-links)
- [Applications](#applications)
- [Building Blueprints](#building-blueprints)
- [Tools](#tools)
- [Tutorials & Guides](#tutorials--guides)
- [Contribute](#contribute)


## Official Links

- [WordPress Playground](https://playground.wordpress.net/) - Try WordPress Playground here.
- [WordPress.org/Playground](https://wordpress.org/playground/) - WordPress Playground explained on WordPress.org.
- [WordPress Playground on GitHub](https://github.com/WordPress/wordpress-playground) - The source code for the playground.
- [Playground Tools on GitHub](https://github.com/WordPress/playground-tools) - Tools and applications built using WordPress Playground.

## Applications

This is where WordPress Playground powers applications that were not possible or much harder without it.

- [Gutenberg Pull Request Previewer](https://playground.wordpress.net/wordpress.html) - Run a [Gutenberg](https://github.com/WordPress/gutenberg/) Pull Request in a playground to test it.
- [Playground inside Playground](https://playground.wordpress.net/#{%22landingPage%22:%22/wp-admin/post.php?post=1&action=edit%22,%22steps%22:[{%22step%22:%22login%22},{%22step%22:%22installPlugin%22,%22pluginZipFile%22:{%22resource%22:%22wordpress.org/plugins%22,%22slug%22:%22interactive-code-block%22}},{%22step%22:%22writeFile%22,%22path%22:%22/wordpress/post.txt%22,%22data%22:%22%3C!--%20wp:wordpress-playground/playground%20{\%22codeEditor\%22:true,\%22files\%22:[{\%22name\%22:\%22index.php\%22,\%22contents\%22:\%22%3C?php\\\\n/**\\\\n%20*%20Plugin%20Name:%20A%20WordPress%20plugin\\\\n%20*/\\\\nadd_action('init',%20function()%20{\\\\n%20%20update_option('blogname',%20'This%20is%20a%20Playground%20demo!');\\\\n});\%22}]}%20/--%3E%22},{%22step%22:%22runPHP%22,%22code%22:%22%3C?php%20require%20'/wordpress/wp-load.php';%20kses_remove_filters();%20wp_update_post(['ID'=%3E1,'post_title'%20=%3E%20'Playground%20Plugin%20Editor',%20'post_content'=%3Efile_get_contents('/wordpress/post.txt')]);%22}]}) - Uses the interactive code block to do a live preview of the code.
- [Playground Synchronization](https://playground.wordpress.net/demos/time-traveling.html) - Record changes made in one playground and play them back in a second playground.
- [Time Traveling](https://playground.wordpress.net/demos/time-traveling.html) - Record changes made in one playground and play them back in a second playground.
- [Translate Live](https://translate.wordpress.org/projects/wp-plugins/friends/dev/de/default/playground/) - Inline Translation for WordPress plugins and themes, here is an example of the WordPress Plugin [Friends](https://wordpress.org/plugins/friends/) and the language German.
- [WordPress Block Development Examples](https://wordpress.github.io/block-development-examples) – Learn about Block Development through code examples and live demos.
- [WordPress Core Pull Request Previewer](https://playground.wordpress.net/wordpress.html) - Run a [WordPress Core](https://github.com/WordPress/wordpress-develop/) Pull Request in a playground to test it.
- [WP-CLI in the browser](https://playground.wordpress.net/demos/wp-cli.html) - Puts a wp-cli commandline above a playground to manipulate it.

## Building Blueprints

- [Blueprint Builder](https://playground.wordpress.net/builder/builder.html) - A codepen-like environment for building blueprints with autocomplete.
- [Blueprints Gallery](https://github.com/WordPress/blueprints/blob/trunk/GALLERY.md) - A directory of blueprints that demonstrate different ways to use them.
- [Step Library](https://akirk.github.io/playground-step-library/) - Easily build blueprints by joining more complex steps together.

## Tools

- [Edit Visually Browser Extension](https://github.com/WordPress/playground-tools/tree/trunk/packages/edit-visually-browser-extension) - Edit GitHub issue descriptions and other text formats using WordPress blocks in Playground.
- [Museum of Block Art](https://block-museum.com/) - In this museum, the blocks are demo'ed using WordPress Playground.
- [Playground Block for Gutenberg](https://wordpress.org/plugins/interactive-code-block/) - A block that embeds a playground in your post.
- [WordPress Playground for VS Code](https://marketplace.visualstudio.com/items?itemName=WordPressPlayground.wordpress-playground) - Run a WordPress development server without any dependencies.
- [wp-now](https://www.npmjs.com/package/@wp-now/wp-now) - A CLI tool to streamline the process of setting up a local WordPress environment.

## Tutorials & Guides

- [WordPress Playground Documentation](https://wordpress.github.io/wordpress-playground/) - An introduction to WordPress Playground.
- [WordPress Playground README](https://github.com/WordPress/wordpress-playground?#wordpress-playground-and-php-wasm-webassembly) - An explanation of WordPress Playground and how to get started.
- [Blueprints 101](https://github.com/WordPress/blueprints/blob/blueprints-crash-course/docs/index.md) - A Blueprints crash course.
- [Query API](https://wordpress.github.io/wordpress-playground/developers/apis/query-api) - How to configure playground.wordpress.net via query parameters.
- [Blueprint API](https://wordpress.github.io/wordpress-playground/blueprints/data-format) - How to create and use blueprints.
- [Playground on WordPress.tv](https://wordpress.tv/tag/wordpress-playground/) - Talks from WordCamps on WordPress Playground.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
