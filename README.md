# ansur
Program on PHP language version.5 <br>


Program pelengkap untuk e-learning kemenag v.2.0.0 yang dapat menampilkan statistik aktifitas guru dan siswa..!<br>

PETUNJUK:<br>
1.Versi PHP yang digunakan versi.5
Pengaturan versi PHP 5 pada hosting dengan versi PHP.7 ada pada folder Connections.<br>
Tutorial pengaturan versi PHP ada di  (http://ketikspasi.blogspot.com/ ) <br>
2. Silahkan ubah nama database, username, dan password --> Pada file database.php dalam folder connections.<br><br><br>
Buat sebuah tabel ADMIN didalam databse e-learning yang bertujuan untuk membuat akun login.<br><br>
Berikut script tambah tabel "admin":<br><br>


-- Struktur dari tabel `admin`
--

CREATE TABLE `admin` (
  `no_admin` int(11) DEFAULT NULL,
  `username` varchar(20) NOT NULL,
  `password` varchar(20) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

--
-- Dumping data untuk tabel `admin`
--

INSERT INTO `admin` (`no_admin`, `username`, `password`) VALUES
(1, 'admin', '12345');
COMMIT;
