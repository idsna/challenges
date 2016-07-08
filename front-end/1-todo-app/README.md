# Front-End Challenge #1 - Todo App

The following challenge is to create a simple "todo" web application.

You may use any framework you like, including (but not limited to) [BackboneJS](http://backbonejs.org/), [AngularJS](https://angularjs.org/), or plain ol' [jQuery](https://jquery.com/).

You may use a transpiled language provided you perform the necessary steps to convert it to JavaScript that can be run in a browser.

## Specifications

Using your skills as a front-end developer, you will craft a single-page web application for a simple Todo App.

This application will have one (1) main screen. On this screen, you will have the following elements:
- Title
- An unordered list or table containing `todo` items (described below)
- An input box for creating new `todo` items, along with a button that saves the `todo` item to the list
- Each `todo` item in the list should have an associated check box beside it that toggles the item's `completed` state.
    - If the checkbox is checked, the `todo` item text should be displayed as ~~strikethrough~~
- Each `todo` item in the list should have an associated "delete" or `x` button beside it that removes it from the list.
- When creating a `todo` item:
    - the `id` value must be set automatically to a value `1` greater than the last created item's `id`.
        - if this is the first item in the list, its `id` should be set to `1`
    - the `text` field must be filled out
    - the `completed` field should be set to `false`
    - the `createdAt` field should be set to the current date and time at creation
        - don't worry about time zones for this exercise
        - date/time format is not important as long as it can be parsed unambiguously

`todo` object items are structured like this:
```
{
    id: 1,
    text: 'Complete Challenge #1',
    completed: false,
    createdAt: '2016-01-01 00:00:00'
}
```

## Additional Requirements

- You should follow standard coding and naming conventions (an `.editorconfig` file is provided for reference)
- You should not "overthink" or go "all-out" on the specifications. Prefer simpler approaches vs. over-engineered ones.
- If you use `npm`, `bower`, or any other similar tool, make sure you add a `.gitignore` file with the appropriate exclusions so that their myriad of dependencies are not included in the repo.

## Bonus Points

Here are a few optional specifications you can do to get "bonus points". These are **not** required, but can be done to show off additional skills you might have:

- add automated tests to demonstrate that the specifications are met
- persist `todo` items between page reloads (front-end **only**, no server-side saving)
- add a 'delete all' button that purges all `todo` items
- add sorting/filtering capabilities to the list/table
- make it pretty (no Comic Sans please)

## Submission Instructions

Please refer to the [main readme](../../README.md#submission-instructions) for details.
