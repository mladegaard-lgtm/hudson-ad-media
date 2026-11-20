# Hudson ad media

Finished ad images for Hudson's Reddit campaigns. The repo is public because Reddit downloads each ad image from a public link when an ad is built.

- Only finished ad images go here, under `ads/<test-id>/`.
- No screenshot library, source files, app data or notes. Those stay in the private hudson-web repo.
- Files are added by `tools/publish_ad_image.sh` in hudson-web. Never edit or delete a file a live ad uses: Reddit has already copied it, and the link in hudson-web's adset.json must keep working for review.
