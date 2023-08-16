## Design Specifications:
- Only one element should be in focus at a time
- All interactive elements should have a focused state (not just inputs, but also buttons, links, etc)
- It should be obvious which element is in focus
- Focus should be distinguishable from other states such as hover, visited, or active
- Focused radio inputs should be easily distinguishable from selected ones
- Try to avoid changing the layout of the page with focus. Be mindful how the focus change interacts with other elements(e.g. when adding a 2px border the element will be wider than it was before focus, so check that there is enough space)
- To meet accessibility success criteria outlined in WCAGm ensure that:
    - When the keyboard focus indicator is visible, an area of the focus indicator meets all the following:
    - is at least as large as the area of a 2 CSS pixel thick perimeter of the unfocused component or sub-component, and
    - has a contrast ratio of at least 3:1 between the same pixels in the focused and unfocused states.
- Make sure that there are at least two ways to show focus change, (e.g. a border and a colour change. Color alone is probably not sufficient to show focus.)
- Consider different variations of background a focused element may appear on (e.g. on dark mode, or high-contrast modes)
- Ensure it works for both keyboard focus and mouse focus
- Invisible elements should generally not be focusable (an exception would be a skip link, for example)
- Compare your output with the following video:

## Wireframe/video/screenshot
<iframe width="560" height="315" src="../designer_solution/design_solution.mov" frameborder="0" allowfullscreen></iframe>
