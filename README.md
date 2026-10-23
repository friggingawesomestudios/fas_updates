# fas_updates

Version info for Frigging Awesome Studios Maya tools. AnimPolish and Sticky Mod read these files for Help > Check For Updates.

- `animPolish.json`
- `stickyMod.json`

Each release gets an entry at the top of `releases`, with its version, new features, and bug fixes. Big releases also get a one-note overview first:

```json
{
	"url": "https://friggingawesome.gumroad.com/l/animpolish-premium",
	"releases": [
		{"version": "2.0.1", "features": ["Added that"], "fixes": ["Fixed this"]},
		{"version": "2.0.0", "overview": ["What the update is about"], "features": ["First release"]}
	]
}
```

The update popup shows `overview` under Overview, `features` under New Features, and `fixes` under Bug Fixes. Any of them can be left out.

Get AnimPolish at https://friggingawesome.gumroad.com/l/animpolish-premium and Sticky Mod at https://gum.co/sticky-mod.
