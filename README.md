# Digby: Dig to the Core (beta)

A robot digs to the center of the Earth. Tap to dig, evolve, collect relics and reach the core at 6,371 km.

**Play:** https://saerensadv.github.io/digby/

- Single-file HTML game (`index.html`), no build step, no game assets.
- Progress is saved in the browser (localStorage); save codes move it between devices.
- ConsentEase is installed with its official manual snippet at the top of `<head>`.
- Basic consent mode: the page does not request GTM until ConsentEase updates `analytics_storage` to `granted`. Digby game events are withheld while consent is denied or unset; revoking analytics stops new event pushes. The GTM and GA4 tags also require `analytics_storage`.
- A ready-to-import GTM Web Container JSON and GA4 custom-definition checklist accompany the launch task. The import targets `GTM-56HVV4B7` and `G-FD4GCRQT6K`; import using **Merge** into a new workspace, review the diff, then preview before publishing. Do not use Overwrite on an existing container.
- Add `#debug` to the game URL to inspect `digby_*` events locally after analytics consent.

Beta by Saerens Advertising. Companion series: @dig.bydigs on Instagram.
