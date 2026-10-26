# GeoDecoder Digital

Publication branch: **main-digitalized**, GitHub Pages folder **/(root)**.
Digital **v2.6.0** · learning module **v1.5.0**.

Website: https://undead41.github.io/geodecoder-digital/

Frontend mirror of unDead41/geodecoder at tested code commit
6246d06ab492a5b0ab3edb3d5ee7b25bcc84b081. The mirror contains website HTML,
audio and publication metadata. Runtime accounts, classrooms, Duel and
authentication use the existing hosted backends.

Both profile_v2_3.sql and module_progress_v2_4.sql were applied to GeoDecoder
Digital in migration 20261026050330, after explicit owner authorization.
Hosted profile/ownership/module-progress SQL checks passed; synthetic fixtures
were rolled back. GitHub Pages Settings now selects main-digitalized / (root).

Verification:248 application tests,244 module tests, both builds/checks and
representative Chrome/narrow-viewport checks. The deployment record and tested
HTML fingerprint are in release.json. Existing SMTP/redirect requirements still
apply to email delivery; SQL and Pages checks do not verify inbox delivery,
password-provider flows or physical devices.
