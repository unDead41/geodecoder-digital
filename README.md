# GeoDecoder Digital

Prepared publication branch: **main-digitalized**.
Digital **v2.6.0** · learning module **v1.5.0**.

Frontend mirror of unDead41/geodecoder at source commit 6246d06ab492a5b0ab3edb3d5ee7b25bcc84b081.
Only website HTML/audio and publication metadata are included here. Runtime
accounts, classrooms, Duel and authentication remain on their existing hosted
backends. No server keys or database fixtures are included.

The existing public site URL is https://undead41.github.io/geodecoder-digital/ .
This branch is ready as the requested GitHub Pages source; repository Settings
must select **main-digitalized / (root)**. Creating/pushing this branch does not
change those settings. Source selection has not been changed by this update.

For the integrated profile and cloud practice records, apply the source repo's
profile_v2_3.sql and module_progress_v2_4.sql migrations before rolling out the
frontend. Existing SMTP/redirect requirements still apply to email delivery.

Verification: 248 application tests,244 module tests, both builds/checks and
representative Chrome/narrow-viewport smoke. Native development-branch renames
and Pages setting changes require authenticated GitHub UI/CLI; neither is
claimed by preparing this frontend branch.
