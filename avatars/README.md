# VantaView avatars

30 original avatars for the profile picker, in five groups:

| Group | File prefix | Avatars |
| --- | --- | --- |
| Animals | `avatar_animal_` | Fox, Cat, Panda, Owl, Frog, Dino |
| Robots & aliens | `avatar_bot_` | Bot, Cyclops, Alien, UFO, Retro, Astrobot |
| Cartoon faces | `avatar_face_` | Mika, Pip, Ade, Rusty, Sol, Nova |
| Fantasy & sci-fi | `avatar_fantasy_` | Knight, Ninja, Wizard, Astro, Pirate, Viking |
| Anime | `avatar_anime_` | Kira, Ren, Yuki, Mei, Kai, Aya |

Each is a 120×120 SVG with its own background colour baked in, so they are drawn as-is and never tinted. A sixth option, Custom, lets the user supply their own image by URL.

All 30 are original artwork drawn for VantaView. None depicts a character from a film, series, game or other existing work.

## Using them in the app

Android cannot render SVG, so convert each to a vector drawable before use: **File → New → Vector Asset → Local file** in Android Studio, keeping the same file name. They then resolve as `R.drawable.avatar_animal_fox` and so on, and stay sharp from a 40px list row up to a full-screen TV picker.
