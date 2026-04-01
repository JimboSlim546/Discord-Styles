# Discord Styles
A handful of textbox styles for theming messages

![Example of the 'Hero of Law' style](/docs/Sample.png)

## Installation
Have Vencord installed, enable the **ThemeAttributes** plugin, then add this to your QuickCSS:

`@import url('https://raw.githubusercontent.com/JimboSlim546/Discord-Styles/refs/heads/main/main.css');`

To add a style for a user, use this template in your QuickCSS or a separate theme file:

```
li[data-author-id="USER_ID"] {
  --style: M3;
}
```

Replace `USER_ID` with a user's ID, which you can obtain by enabling Discord's Developer mode in the Advanced Settings, then right-clicking a user.


## Styles
Refer to the wiki for a list of styles and their specific attributes. (When I eventually make it...)