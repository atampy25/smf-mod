# Mod template

To get started, customise manifest.json to your liking, then create a commit along the lines of `feat: initial mod`. If you're looking to integrate this into an existing mod you have, copy everything from that mod over to this template, create a commit such as `chore: transfer existing mod` and then tag that commit with the currently released version of the mod (the initial commit will still automatically be tagged 0.1.0, which is fine).

This template will do everything for you, including versioning, generating changelogs and creating mod ZIPs; just make sure you follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0). If you want to have multiple new features in a release, just work in a branch and then merge it into the main branch once you want to release.

As a rule of thumb, anything that doesn't drastically alter the mod or make sweeping changes that could break other mods should be either an `enhancement` (for improvements to existing parts of the mod), `feat` (for new parts of the mod) or `fix` (for bugfixes). You can specify the part of the mod you're changing like so: `fix(epic feature): do this thing properly`.

If you do drastically alter the mod or make sweeping changes that could break other mods, add an exclamation mark just before the `:`, and write `BREAKING CHANGE: This thing is now this thing, which means this.` in the "description" or "footer" of the commit.

An important note: the version for the mod starts at `0.1.0`, which means the mod is in development. When you finalise the mod for its first release, add an exclamation mark before the `:` and the version will automatically be bumped to `1.0.0`.
