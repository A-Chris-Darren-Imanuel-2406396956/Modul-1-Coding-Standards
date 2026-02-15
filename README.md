# Refleksi 1
Dalam mengerjakan tutorial dan exercise yang diberikan, saya kembali diingatkan untuk menerapkan prinsip _clean coding_ dalam pelaksanaan _programming_. Sewaktu implementasi List, Create, Delete, kemudian Edit, saya memberikan **Meaningful Names** dalam penamaan variabel dan _method_ yang sesuai dengan semantik dan _self explanatory_. Selanjutnya, saya juga memanfaatkan library Lombok untuk menjaga model tetap bersih dan tidak dipenuhi method getter setter saja. Saya pun menerapkan UUID untuk Id product, memastikan Id Product tidak mudah ditebak oleh _unauthorized user_.

Meski dalam pengerjaan ini tidak ditemukan banyak masalah atau kesulitan, saya yakin pengerjaan ini dapat di-_improve_ menjadi lebih baik, seperti menambahkan autentikasi & otorisasi, validasi input, dan _handle edge case_ lainnya.

# Refleksi 2
Tidak ada angka pasti dalam membuat unit test. Tujuan kita membuat unit test adalah memastikan setiap jalur logika teruji berjalan baik dan sesuai dengan kebutuhan. 100% code coverage juga tidak menjamin kebenaran logika untuk semua kemungkinan input yang ada. Sebagai developer, kita harus memahami perspektif sebagai user dan juga sebagai programmer.

Dalam membuat class baru tersebut akan menimbulkan duplikasi kode yang apabila practice ini terus dilanjutkan akan membawa masalah baru yaitu kesulitan dalam pemeliharaan dan maintenance kode. Approach yang bisa kita ambil sebagai solusi adalah refactor dengan membuat base class yang berisi semua setup sehingga reusable dan maintainable.