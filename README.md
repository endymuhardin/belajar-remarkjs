# Presentasi dengan RemarkJS #

[RemarkJS](https://github.com/gnab/remark) adalah library untuk membuat slide presentasi dengan sintaks Markdown.

Selain RemarkJS, kita juga bisa menggunakan:

* [Pandoc](http://pandoc.org/demo/example9/producing-slide-shows-with-pandoc.html)
* [RevealJS](http://lab.hakim.se/reveal-js/)
* [Slidify](http://ramnathv.github.io/slidify/)
* [ioslides](http://rmarkdown.rstudio.com/ioslides_presentation_format.html)
* [Markdown Presenter](https://github.com/jsakamoto/MarkdownPresenter)
* [dan lain sebagainya](http://www.impressivewebs.com/html-slidedeck-toolkits/)

---

# Software Requirement #

RemarkJS bisa dijalankan dengan 2 mode :

* local : langsung buka filenya dengan browser
* server : jalankan webserver dulu, kemudian browse ke alamat webservernya (misalnya `http://localhost:8000`)

Untuk mode local, cukup membutuhkan browser saja.
Untuk mode server, ada beberapa pilihan :

* Python 3 : `python3 -m http.server`
* Ruby : `ruby -run -ehttpd . -p8000`
* NodeJS : `http-server -p 8000`. Sebelumnya install dulu modul `http-server` : `sudo npm install -g http-server`

---

# Cara Pakai #

1. Buat presentasi dalam format Markdown
2. Integrasi dengan RemarkJS

    * Embed dalam HTML, contoh ada di file `slide-local.html` dan `slide-portable.html`
    * Cukup disebutkan dalam HTML. Contohnya ada di file `slide.external.html`

3. Tampilkan presentasi

    * Bila markdown diembed dalam HTML, file HTML bisa langsung dibrowse.
    * Bila markdown di file terpisah (external), harus jalankan dulu webserver. Kemudian browse ke webservernya

---

# Referensi #

* [Sintaks markdown untuk membuat presentasi](https://github.com/gnab/remark/wiki/Markdown)
* [Format teks dan gambar](https://github.com/gnab/remark/wiki/Formatting)
