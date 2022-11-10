# Misc-Ikemen-scripts
This is a repository for my Ikemen scripts that offer (minor) QOL improvements for the average user. As of right now there are only two:

**fanfare.zss**

A script that plays a sound sample at the end of a match and offshoot of my extended-intro-outro project, I chose to fork it here since it conceptually kinda clashes; `intro-outro.zss` is meant to be used as is, whereas this `fanfare.zss` is easier to customize.

**powerbars.zss**

A simple script derived from a nugget of code PotS gave me, it hides the power bars for characters who have their own in-built meter management (think CvS2, SF3, SamSho or Melty Blood characters)

**To install**


1. Drop the contents of the most recent release in your `data\` folder.
2. Go to `save\` and open `config.json`
3. Near the beginning of the file you should see a block like this:

```
	"CommonStates": [
		"data/action.zss",
		"data/dizzy.zss",
		"data/guardbreak.zss",
		"data/score.zss",
		"data/tag.zss",
		"data/training.zss"
	],
```
You just need to add `"data/fanfare.zss"` and/or `"data/powerbars.zss"` so the engine can read the files.

```
	"CommonStates": [
		"data/action.zss",
		"data/dizzy.zss",
		"data/guardbreak.zss",
		"data/score.zss",
		"data/tag.zss",
		"fanfare.zss",
		"powerbars.zss",
		"data/training.zss"
	],
  ```
  The order isn't very relevant, just make sure to include a comma if either file is NOT the last the last line on the block, and to ommit it if it isn't.
  4. Open both files with a text editor (like Notepad++) for further instructions as to how to use them.
