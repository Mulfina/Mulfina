
-- Membuat database
CREATE DATABASE IF NOT EXISTS perpustakaan;
USE perpustakaan;

-- Tabel Buku
CREATE TABLE buku (
    id_buku INT AUTO_INCREMENT PRIMARY KEY,
    judul VARCHAR(100),
    pengarang VARCHAR(100),
    penerbit VARCHAR(100),
    tahun_terbit YEAR,
    jumlah INT
);

-- Tabel Anggota
CREATE TABLE anggota (
    id_anggota INT AUTO_INCREMENT PRIMARY KEY,  
    nama VARCHAR(100),6
    alamat VARCHAR(255),
    no_hp VARCHAR(20)
);

-- Tabel Peminjaman
CREATE TABLE peminjaman (
    id_peminjaman INT AUTO_INCREMENT PRIMARY KEY,
    id_anggota INT,
    id_buku INT,
    tanggal_pinjam DATE,
    tanggal_kembali DATE,
    FOREIGN KEY (id_anggota) REFERENCES anggota(id_anggota),
    FOREIGN KEY (id_buku) REFERENCES buku(id_buku)
);

-- Contoh data awal
INSERT INTO buku (judul, pengarang, penerbit, tahun_terbit, jumlah) VALUES
('Laskar Pelangi', 'Andrea Hirata', 'Bentang Pustaka', 2005, 10),
('Bumi Manusia', 'Pramoedya Ananta Toer', 'Hasta Mitra', 1980, 7),
('Negeri 5 Menara', 'Ahmad Fuadi', 'Gramedia Pustaka Utama', 2009, 5);

INSERT INTO anggota (nama, alamat, no_hp) VALUES
('Siti Aminah', 'Jl. Merpati No. 10, Mamuju', '081234567890'),
('Rudi Hartono', 'Jl. Cendrawasih No. 5, Majene', '082345678901');

INSERT INTO peminjaman (id_anggota, id_buku, tanggal_pinjam, tanggal_kembali) VALUES
(1, 1, '2025-05-20', '2025-05-27'),
(2, 2, '2025-05-22', '2025-05-29');
