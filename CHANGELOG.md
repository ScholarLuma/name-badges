# v1.1.4
A small change for the future: restructured the file structure a bit to separate Powercord and Vizality better. Since the data-author-id attribute is originally a Powercord one, once Vizlaity re-adds the vz-user-id attribute to messages I can change some things back over. For now, it'll continue using src*=. (which is probably gonna be really unoptimized)
- **BUG:** An issue I found out with doing it this way is since it relys on the user's profile picture url, if the user removes their profile picture, the badge will not show as Discord uses a special asset for default profile pictures.

# v1.1.3
Semi-big changes coming to this repo (finally), originally was gonna do it sometime in the future but thanks to Discord changing attribute selectors for the 50th time.. yeaaa.
- Fixed for badges not displaying on usernames in messages.
- Restructured the file structure a bit.
- Better Vizality support (so if you're on Vizality, badges should appear on more things compared to Powercord).
- Small repo rewrite, looks nicer doesn't it?
- Changelog for v1.1.0 and later. Guess what, you're reading it right now!

# v1.1.1 - v1.1.2
Attempts at basic Vizality support by [Hoofer](https://github.com/HooferDevelops/).

# v1.1.0
In order for better maintainability, I recoded this to be in SCSS instead of CSS. You may be asking "well, what's the difference!?!? do i still have my badge?!??!!" First off, there really isn't much of a difference besides it's easier for me to work with and is less of an eye sore. Secondly, yes you still have your badge. If you have name badges before this update, make sure you reinstall the theme completely to prevent any issues. If you're using the import, you have to install the theme as is because you cannot import an SCSS file. If your badge isn't appearing / appearing properly, make an issue request and ill look into it. 