
`	`Dalam era digital yang semakin maju seperti sekarang ini, instansi ataupun perguruan tinggi memiliki kebutuhan yang sangat penting dalam membangun infrastruktur jaringan komputer yang efisien dan handal. Seiring dengan perkembangan teknologi dan kebutuhan akses data yang semakin tinggi, rancangan topologi jaringan menjadi aspek kritis dalam mendukung berbagai aktivitas yang dilakukan oleh pengguna di dalam institusi tersebut.

`	`Topologi jaringan merupakan representasi fisik atau logis dari bagaimana perangkat komputer, server, dan perangkat jaringan lainnya terhubung dan berkomunikasi satu sama lain. Dengan memiliki topologi jaringan yang tepat, sebuah institusi atau perguruan tinggi dapat menjamin ketersediaan jaringan yang stabil, pengelolaan sumber daya yang efisien, dan kemampuan untuk mengatasi potensi masalah jaringan dengan cepat dan efektif.

Perguruan Tinggi Fakultas Teknik Universitas Nurul Jadid adalah salah satu institusi pendidikan yang berdedikasi untuk memberikan pendidikan berkualitas dalam bidang teknik dan teknologi. Namun, seperti banyak perguruan tinggi lainnya, Fakultas Teknik Universitas Nurul Jadid juga menghadapi berbagai tantangan dalam membangun dan mengelola infrastruktur jaringan yang sesuai dengan perkembangan teknologi dan kebutuhan pengguna.

Salah satu masalah utama yang dihadapi oleh perguruan tinggi ini adalah keterbatasan infrastruktur jaringan yang ada. Dengan adanya dua gedung di dalam lingkungan kampus, diperlukan penghubung jaringan yang efisien dan andal antara kedua gedung tersebut. Mungkin saat ini, perguruan tinggi ini masih menggunakan infrastruktur jaringan kabel konvensional, seperti kabel tembaga, yang rentan terhadap gangguan dan memiliki batasan kecepatan transfer data.

Selain memperbarui infrastruktur kabel, pihak perguruan tinggi juga perlu memastikan investasi dalam perangkat jaringan dan sistem manajemen yang tepat. Penggunaan perangkat jaringan yang canggih dan modern akan memastikan keefisienan dan kinerja yang optimal dari jaringan. Sistem manajemen jaringan yang baik juga penting untuk memantau dan mengatasi masalah potensial dengan cepat, sehingga downtime dapat diminimalkan dan pengguna dapat terus mengakses layanan internet dengan lancar.


Beberapa masalah yang di temukan adalah sebagai berikut:
1.		Perguruan tinggi Fakultas Tehnik Universitas Nurul Jadid tidak memiliki sebuah topologi jaringan yang pasti di gedung utama;
2.		Tidak adanya kejelasan yang pasti mengenai topologi jaringan yang terdapat di 2 gedung perguruan tinggi Fakultas Tehnik Universitas Nurul Jadid.

Gambar di Atas yang bagian Gedung C yaitu penghubung antar jaringan menggunakan Switch.
A. Switch merupakan perangkat jaringan yang bekerja pada lapisan Data-link (Layer 2) dalam model referensi OSI (Open Systems Interconnection). Fungsinya mirip dengan bridge, yakni menghubungkan beberapa segmen jaringan lokal (LAN) ke dalam satu jaringan yang lebih besar. Dengan menggunakan switch, data dapat dikirimkan secara efisien hanya ke tujuan yang tepat, menghindari pengiriman data ke semua perangkat di jaringan seperti yang terjadi pada hub.

Di Gedung Fakultas Teknik Universitas Nurul Jadid, terdapat enam switch yang digunakan untuk mengatur dan menghubungkan beberapa segmen LAN. Setiap switch berperan dalam mengelola lalu lintas data di segmen jaringan lokal tertentu.
Selain itu, ada juga hub yang digunakan untuk menghubungkan switch-switch tersebut. Hub adalah perangkat jaringan yang bekerja pada lapisan Fisik (Layer 1) dalam model referensi OSI.
HUB merupakan sebuah peranti jaringan komputer yang berfungsi untuk menghubungkan peranti-peranti dan kabel dari node ke nod yang membuat beberapa komputer terhubung menjadi satu, setelah Hub menghubungkan ke ruter untuk menampung sebuah jaringan setelah semua terhubung ke jaringan maka kita harus menggunakan server untuk setting kecepatan maupun batasan akses yang ingin kita hubungkan ke komputer lain. 
Dalam konteks pendistribusian jaringan komputer di perguruan tinggi Fakultas Teknik Universitas Nurul Jadid, HUB menjadi komponen penting dalam membentuk infrastruktur jaringan yang handal. Fungsi utama HUB adalah menghubungkan perangkat-perangkat dan kabel dari setiap node atau komputer ke satu titik pusat, sehingga memungkinkan beberapa komputer terhubung menjadi satu jaringan. Dengan menggunakan HUB, mahasiswa, dosen, dan karyawan dapat saling berkomunikasi dan berbagi sumber daya seperti printer atau file secara lebih mudah dan efisien.
Setelah terhubung melalui HUB, selanjutnya jaringan tersebut akan terhubung ke router. Router bertindak sebagai penghubung antara jaringan lokal di perguruan tinggi dengan jaringan eksternal, seperti internet. Router memainkan peran penting dalam mengatur lalu lintas data, meneruskan paket data ke tujuan yang tepat, dan menjaga keamanan jaringan dengan menggunakan teknik seperti Network Address Translation (NAT) dan firewall.

 	(mengggunakan HUB dengan IP ADRESS 192.168.0.0   DIsambungkan Pada Komputer dengan IP ADRESS )
•	Komputer (1)192.168.0.1, Komputer (2)192.168.0.2, Komputer (3)192.168.0.3, Komputer (4)192.168.0.4
 	Menggunakan swith dengan IP address 192.168.1.1   Disambungkan Pada Komputer dengan IP ADRESS
•	Komputer (1)192.168.1.2, Komputer (2)192.168.1.3, Komputer (3)192.168.1.4 Dll.

**Beberapa Ancaman pada System Keamanan Jaringan**

- DOS (Denial Of Service) merupakan bentuk serangan pada jaringan dengan cara menghabiskan sumber daya, tentunya sangat berbahaya bagi keamanan jaringan.
- Paket Sniffing adalah prinsip dasar pencurian jenis ini, bahwa semua koneksi ethernet yang bersifat broadcast.
- IP Spoofing adalah model serangan yang bertujuan untuk menipu calon korban. Dilalui dengan cara mengubah alamat asal sebuah paket sehingga dapat melewati firewall yang telah diinstal.
- DNS Forgery , Seseorang penyerang membutuhkan informasi seperti nama identitas pertanyaan,  port tujuan pertanyaan, IP address , DNS, resolver, Informasi yang ditanyakan, waktu pertanyaan.
- DNS Cache adalah memanfaatkan cache dari setiap server DNS yang merupakan tempat penyimpanan sementara data-data domain pada browser.


Beberapa Ancaman pada System Keamanan Jaringan

- DOS (Denial Of Service) merupakan bentuk serangan pada jaringan dengan cara menghabiskan sumber daya, tentunya sangat berbahaya bagi keamanan jaringan.
- Paket Sniffing adalah prinsip dasar pencurian jenis ini, bahwa semua koneksi ethernet yang bersifat broadcast.
- IP Spoofing adalah model serangan yang bertujuan untuk menipu calon korban. Dilalui dengan cara mengubah alamat asal sebuah paket sehingga dapat melewati firewall yang telah diinstal.
- DNS Forgery , Seseorang penyerang membutuhkan informasi seperti nama identitas pertanyaan,  port tujuan pertanyaan, IP address , DNS, resolver, Informasi yang ditanyakan, waktu pertanyaan.
- DNS Cache adalah memanfaatkan cache dari setiap server DNS yang merupakan tempat penyimpanan sementara data-data domain pada browser.


Beberapa Ancaman lainnya pada System Keamanan Jaringan

- Worm adalah program yang menyebar sendiri dengan cara mengirimkan dirinya sendiri ke sistem, hampir sama dengan virus.
- Virus adalah program yang dapat menyisipkan dirinya sendiri ke obyek lainnya, seperti : file executable (berekstensi .exe) dan beberapa jenis dokumen yang digunakan (file nya dihacker).
- Trojan merupakan software yang sangat berbahaya dan dapat merusak sebuah sistem atau jaringan.
- Junk Mail adalah ancaman ini adalah dengan mengirim spam akan memperbesar kapasitas inbox email, sehingga pesan lain yang penting tidak dapat masuk karena kapasitas inbox telah penuh kiriman pesan berantai tersebut.
- Vulnerability adalah suatu sistem yang memungkinkan seorang penyerang untuk melanggar integritas sistem tersebut. Kerentanan memungkinkan akibat lemahnya password, software bug, sebuah virus komputer atau malware, skrip kode injeksi, sebuah SQL injection atau kegagalan konfigurasi.
- Hacking adalah suatu tindakan untuk memperoleh akses ke suatu sistem menggunakan kelemahan yang terdapat pada sistem itu sendiri . Sikap hacking dan kemampuan yang ada pada dasarnya harus mempelajari sendiri, seperti hal berikut :
Untuk mengetahui alur spesifikasinya dengan cara berikut.

- Pertama kita setting mikrotiknya dengan menggunakan router 
- Agar bisa melakukan konfigurasi MikroTik harus masuk ke router menggunakan Winbox. 
- Setelah masuk ke router MikroTik dengan Winbox, cari menu *IP*  *Pool* dari menu sebelah kiri di Winbox. Tampilan IP Pool akan muncul, lalu hapus *IP Pool* server DHCP Anda. Jadi, tidak akan ada IP yang akan diberikan secara otomatis oleh server DHCP Anda untuk pengguna.
- Selanjutnya klik menu *IP*  *DHCP Server*, pada tab *DHCP* klik dua kali pada server DHCP yang aktif dan tampilan DHCP server akan muncul. Di tab *Generic*, masih pada tampilan *DHCP server*, periksa pada bidang *Address Pool* dan ubah bidang tersebut menjadi *static-only*.






