# Mod template
To get started, create a `0.1.0` tag for the "initial commit" GitHub created and then customise manifest.json to your liking. Everything will be done for you; just make sure you follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0).

As a rule of thumb, anything that doesn't drastically alter the mod or make sweeping changes that could break other mods should be either an `enhancement` (for improvements to existing parts of the mod), `feat` (for new parts of the mod) or `fix` (for bugfixes). You can specify the part of the mod you're changing like so: `fix(epic feature): do this thing properly`.

If you do drastically alter the mod or make sweeping changes that could break other mods, add an exclamation mark just before the `:`, and write `BREAKING CHANGE: This thing is now this thing, which means this.` in the "description" or "footer" of the commit.

An important note: the version for the mod starts at `0.1.0`, which means the mod is in development. When you finalise the mod for its first release, add an exclamation mark before the `:` and the version will automatically be bumped to `1.0.0`.