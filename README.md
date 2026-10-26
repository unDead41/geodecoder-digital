# GeoDecoder Digital v2.3.0

Main: https://undead41.github.io/geodecoder-digital/

Home → Teroka modul pembelajaran → Makmal interaktif membuka modul v1.2.0 dengan Bina Bentangan, Makmal Isi Padu, Terbitkan Rumus dan Bongkah Gabungan. Modul dipinkan tepat daripada digitalize-module commit 931a0150397bfb3fd79ef3c8da6684167d1c6aad.

Play as a Guest tanpa akaun, kelas guru/pelajar dengan PIN dan skor masa nyata. Muzik rest-site untuk menu dan map untuk modul/permainan, dengan toggle di header; playback bermula selepas interaksi pertama.

Pendaftaran email dan reset menggunakan Supabase Auth. Penghantaran email umum masih memerlukan pemilik melengkapkan custom SMTP dan Site URL/redirect; inbox delivery belum disahkan. Kata laluan 10–128 aksara menerima huruf besar/kecil, nombor dan simbol.

Repo ini membawa frontend serta dua audio dibekalkan pengguna. Sumber pembangunan kekal pada repository private unDead41/geodecoder, branch digitalize. release.json merekodkan pin, sumber dan hash. GitHub Pages menerbitkan main-digital/root. Validation: 100/100 module tests dan 81/81 application tests, build dan static checks lulus.
