# PencariBuku-APIGooglebook
# Aplikasi Pencarian Buku dengan Google Book API
1. Aplikasi dibuat menggunakan library JavaScript yaitu React.js
2. Icon di import dari fontawesome
3. API yang digunakan adalah API dari Google Book API
4. Pengolahan API menggunkan Axios dengan cara menggingstalnya di React.js
5. Max result dari API yang didapatkan dari google book API adalah 40
6. Yang ditampilkan dari Google Book API 
	- Gambar (item.volumeInfo.imageLinks.smallThumbnail),
	- Judul Buku (item.volumeInfo.title),
	- Harga (item.saleInfo.listPrice.amount),
	- IDR (item.saleInfo.listPrice.currencyCode)
	- Author/Pengarang (item.volumeInfo.authors),
	- Tanggal Terbit (item.volumeInfo.publishedDate),
	- Penerbit (item.volumeInfo.publisher),
	- Deskripsi Buku (item.volumeInfo.description),
	- Link untuk Preview Buku (item.volumeInfo.previewLink)
