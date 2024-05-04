Freeshell "More Tuna Please" v1.0.0

—————————— Terms ——————————
This freeshell is free to use for your own ghost projects, with the following terms.

You must:
	• Mention in your ghost's readme that you are using my freeshell. I can be credited as "Zichqec", with the following link: https://ukagaka.zichqec.com/
	• Keep this readme file as-is.
	
You may:
	• Modify the shell, including recoloring, drawing new expressions, combining expressions, etc.
	• Modify the settings files in any way you need.
	• Use this shell to create a thumbnail image for your ghost, or a preview image for use on the ghost's release page, etc.
	
You must not:
	• Use this freeshell to create commercial works.
	• Distribute any version of this freeshell on its own.
	• Use this shell for works outside the realm of ukagaka.
	• Modify the shell to be discriminatory or political, or use it in a work that contains these elements.
	• Modify the shell to add nudity or sexual elements.

It is not required to notify me that you have used this shell, but I'd love to see what you've made!


—————————— Customization ——————————
layers.psd has been included to help with customization. Feel free to make use of it for recoloring, adding patterns, etc.

You may of course use this shell as-is, but I think it would be wonderful if folks recolored him into different colors of cat!


—————————— Surface numbering scheme ——————————
This shell follows the recommended surfaces listed on Ukadoc. 0-9 should roughly match up with the standard 0-9 that you'll find there.

In addition, there are alternate eyes and arms that can be controlled by adding additional digits. The ones column is the expression, the tens column is the eyes, and the hundreds column is the arm. For example, surface142 is the surprised expression (2), with eyes looking right (4), and the arm in a thinking position (1).

000 - Arms down
100 - Thinking arm
200 - Gesturing arm

	00 - Eyes closed (sometimes up, sometimes down)
	20 - Eyes looking forward
	30 - Eyes looking left
	40 - Eyes looking right
	
		0-9 - The recommended expressions listed on Ukadoc

Note that there is one exception to this scheme. The surfaces for 26, 36, and 46 would be identical to 20, 30, and 40, so instead these have been given a slightly different expression. If you'd like this special expression with closed eyes, please use the special surface 56. Sorry for the weird exception, I figured that more expressions was better than omitting the duplicates.

There are also a group of "special expressions". These are the expressions in the 50s range, which are unique and created from the various pieces of the shell. If you want to add additional expressions, it is recommended to start within this 50s range.


All surfaces have the following "never" animations that can be called with \i[] tags:

\i[10] - Stop the talking animation (for narration, etc.)
\i[11] - Blush
\i[12] - Sweat drops

Note that the blush and sweat drops are automatically applied to some expressions, making it redundant to use these tags with those surfaces.

And finally, base_alt.png is included in the files, and may be substituted for base.png if you like. This changes the hoodie text from "Meow" to "にゃーん" (Nyaan). If you do not need this file, you can delete it.


—————————— Collisions ——————————
The following collisions are included by default:

Head - Top of head and both ears. By default, the ears have their own collisions. However, if you'd prefer that they all be joined together into one collision, you can remove the ear collisions and just use this one.
Ears - Both ears.
Face
Nose
Hair - The hair to the side of the head, not the top.
Left_hand - The hand on the left side of the shell, which never moves.
Right_hand - The hand on the right side of the shell, which moves for some surfaces. This is sometimes covered up by the tail.
Belly - The stomach area. Sometimes partially obscured by the right side arm.