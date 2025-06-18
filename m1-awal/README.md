# 👋 Program Pertama dengan Golang

Ini adalah program Go paling sederhana yang biasanya digunakan sebagai langkah awal dalam belajar bahasa pemrograman Golang.

## 📄 Kode Program

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello World")
	fmt.Println("Hai, I'm Agus Furqon")

## 🧠 Penjelasan Kode
Mari kita bahas bagian-bagian kode di atas:

package main
Baris ini menandakan bahwa file ini merupakan bagian dari paket main.
Ini penting karena hanya paket main yang dapat dikompilasi dan dijalankan secara langsung di Go.

import "fmt"
Kita mengimpor package fmt (format) dari pustaka standar Go.
Paket ini digunakan untuk menampilkan teks ke terminal (output).

func main() { ... }
Fungsi main adalah titik awal eksekusi program Go.
Ketika kamu menjalankan program, baris kode dalam fungsi ini yang akan dieksekusi pertama kali.

fmt.Println(...)
Fungsi Println dari paket fmt mencetak teks ke terminal, diikuti dengan baris baru (\n).
Dalam contoh ini, dua baris teks akan dicetak:

Hello World
Hai, I'm Agus Furqon
