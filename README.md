# DarkSpice

This is a Spiceworks UI overhaul with CSS for those sensitive to light. Inspired by the dark theme in Zabbix.

This is a beta version, however, majority of UI elements should be covered. if you see any elements that are still their original colour, please let me know in the comments. Some elements were skipped intentionally as making them dark may impact their usability (Graphs, Charts etc.).

Please note: Spiceworks was designed with a light theme in mind and some icons do not look great on a dark background (some white edges etc.).

This method works better than my native spiceworks plugin as it avoids some issues/limitations of the Spiceworks API and/or my coding skills, such as: the Ticket Dashboard is NOT ignored, The login Page is NOT ignored. It also allows you to make sure it applies only to users that want it instead of applying it globally to the entire Spiceworks install.

# Contribution

Please feel free to contribute to the CSS. The orriginal file is for the Dark Ui Theme, create a new file if it is a differently styled theme.

# Instructions

1. Install "Stylish" plugin in Chrome Opera or Firefox
2. Create a new style
3. Copy the CSS into the newly created style
4.(Chrome/Opera) In Chrome or Opera make sure to enter your spiceworks domain in the applies to field of the style settings page.
4.(Firefox) In Firefox make sure you add

NOTE: Do Not use beautify option in stylish as it breaks some table related .CSS (specifically it removes all spaces before ":nth-child" and they are required in some places for the related custom CSS to work. 
