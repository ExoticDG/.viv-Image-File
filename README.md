
# Credits to [face-hh](https://github.com/face-hh) for the [original coding](https://github.com/face-hh/bruh). I just modified it.


## VIV
Uhhh, I wanted to made a file format for an image cuz why not.


### How to
1. Download the repo / `git clone` it.
2. Open a command prompt in the directory / `cd viv`
3. Run `cargo run compile` followed by a `path/to/image.png` to compile PNG to VIV. Example: `cargo run compile C:\Uses\User\Downloads\image.png`

4. Run `cargo run` followed by a `path/to/image.viv` to show the image

#### OR
1. Double-click on `image.viv` using your File Explorer.
2. Click on `More Apps`

![More Apps](https://cdn.discordapp.com/attachments/1074408238939906220/1130765375693406258/image.png)

3. Click on `Choose app from this PC`

![Choose app](https://cdn.discordapp.com/attachments/1074408238939906220/1130765548813308034/image.png)

Tip: tick "Always use this app to open .viv files"

4. Type the `path/to/this/project`.
5. Select `viv.exe` inside this folder.

That's it! You can now open `.viv` files!

### Known issues
⚠ The PNG > VIV won't work unless you have the same file (i.e. image.png) but with the .viv extension (i.e. image.viv). What do you have to do? Create an empty file called `image.viv`.

1. Preview window width & height are not exact.
2. Huge file size on large images.
3. Slow preview window.
4. Some large images might include `#0` hex which will crash the program.
5. No transparency.
6. Only works on Windows
