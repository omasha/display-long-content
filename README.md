# A very long page

A prototype for a page that is designed to present a lot of content in a user-friendly way.

## Requirements

Content should be organized into logical blocks that are visible at a glance so that a user gets oriented in it on load. A user can navigate between the blocks and drill down into any particular block as needed. The full page text should be available at a glance if desired. The mobile version should have additional navigation options for the ease of use.

## Implementation

To achieve that, the sections have headers, short descriptions and dropdowns for the rest of the content however long

- There is a menu that gets dynamically generated from the section headers
- The links in the menu navigate to the corresponding sections and expand them on click
- There's an option in the menu to expand/collapse all sections
- A copy of the dynamic menu appears at the bottom of the mobile layout as well so that a user doesn't need to scroll all the way up to access the section links. It's hidden on load and becomes available on click.
