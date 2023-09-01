# HoriSEOn Challenge 

## Description

This code refactor was done to improve accessibility for future developers intending to add to this site. The previous iteration greatly overused `<div>` tags in the primary `index.html` file, as well as excessive redundancy in the `style.css` stylesheet. In this iteration, the `<div>` tags have been entirely replaced, utilizing `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` tags in a sensible, logical manner. The redundant CSS styles have been properly consolidated, by applying each style to their parent instead - specifically, the `content` class and the `benefits` class. 

Additionally, the navigation links at the top of the page now work properly. The now-extraneous classes in the `index.html` file have been repurposed into ID values instead, so that the links at the top may properly link to them. Although there are no such links for the individual items in the Benefits section, those classes have been changed to IDs as well for any future developer's use.

## Installation

N/A

## Usage

The new code functions mostly identically to the old code, aside from the fixed navigation links at the top. The primary difference is in readability, as it is now possible to more easily determine what parts of the code correspond to what aspects of the finished site. The `style.css` file is also much less of a slog to scroll through.

## Credits

All original code sourced from the Rutgers Coding Bootcamp curriculum.

## License

Please refer to the license in the repo.