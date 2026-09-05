# Rugby Predict — share cards

Generated images for [Rugby Predict](https://play.google.com/store/apps/details?id=com.insider08.rugby),
served over GitHub Pages so Instagram's publishing API can fetch them: it will
not accept an uploaded file, only a public https URL.

Everything in `cards/` is written by MediaBot and is disposable — the images are
posted to social media the same day. Files older than 30 days are pruned on each
run, so treat this repository as a cache, not an archive.

    https://drogo4lame.github.io/rugby-predict-cards/cards/<filename>

`.nojekyll` disables the Jekyll build: there is nothing to render here, and it
makes each deploy faster.
