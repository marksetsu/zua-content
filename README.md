# zua-content

The live content of ZUA's main screen (news, albums, tracks): `catalog.json`, served by GitHub Pages at
https://marksetsu.github.io/zua-content/catalog.json. The app reads it when it opens and when it comes back to the
front; it keeps the last copy it read, and falls back to the copy built into the app.

Everything here is public: put things in only when they are to be shown. Drafts live in the app's own (private) repo,
`App/ZUA/Resources/catalog.json`, and are published from there with `tools/publish-content.sh`.
