# Verified Queer Flag Emojis

**If you're looking for the emoji image files themselves, you can find them in [releases](https://github.com/ShadowJonathan/VerifiedQueer/releases).**

This is a repository of art resources for the Verified Queer Flag Emojis you might have seen on the fediverse;

![](examples/verifiedenby.png)
![](examples/verifiedtrans.png)

I've taken inspiration from the [VeriPride Maker](https://posm.gay/public/veripride/) generator ([source](https://git.lgbt/root/veripride/)), but found it lacking for some specific things tasks (like heavy customization), and the non-right-angle checkmark annoyed me when trying to get fill-ins to work, so I created a defacto template file from which I started basing every other flag-file of.

In these files, the "flowery" outline is taken from the SVG of twitter's website. The checkmark is mine, created by some long twiddling in an SVG editor.

I'm opening these files here to allow anyone to make their own flags as well :)

These resource files are released under [`CC NC-SA`](https://creativecommons.org/licenses/nc-sa/1.0/).

This means;
- That you can remove attribution to me or this repo if you want (please do, I don't want the attention or popularity, I just want to empower people)
- That - if you make more *flag template files* (like `verified.xcf`) deriving from these files - you should release it under the same license.
- That you cannot use this for commercial purposes.`*`
  - First off because fuck corporations encroaching on queerness, but also because the whole point of these images are to allow people to stick a finger to any authority-beholden "verification" of queerness, so to speak. (You can read [my post](https://tech.lgbt/@ShadowJonathan/109473889530943426) on it, if you're curious.)
  - `*` I give an exception to physical cosmetic items, like stickers and badges, go wild: wear it proudly :)

## Repo Layout

Most flags (which are as easy as just adding a flag background to the template, and coloring the checkmark) are not saved
on the repo, as that'll duplicate a **lot** of data.

Instead, there's one "cookie cutter" xcf file, `verified.xcf` which contains 3 layers, with the top layer being the checkmark,
the middle layer being the masked flag layer, and the bottom being a background layer.

There also exists "unique" flag files, such as the polyam ones, which are released under `unique/`.

## Workflow (for standard flags)

If you want to use it to make a flag, just find a flag file on the internet, or make your own.

Paste it in a new tab, don't paste it to the second layer just yet.

Then, scale it *down* to a 500px height, it's now ready to be copy-pasted onto the second layer.

In the verified xcf file, select the second layer (beware of clicking the mask accidentally), and paste the flag.

It should fit perfectly to the top and bottom edges of the verified image, and you can now change the checkmark color
to have sufficient contrast, and export the image.
