README

Untuk merilis versi module cukup create tag di git:
1. git tag v1.0.0
2. git push origin v1.0.0

Untuk upgrade module cukup push tag baru:
1. git tag v1.1.0
2. git push origin v1.1.0

Untuk upgrade major maka perlu ganti nama module agar backward competable (tidak merusak module versi sebelumnya):
1. ganti nama module di file go.mod menjadi (contoh) github.com/yoga-nugroho129/go-say-hello-module/v2
2. push tag baru menjadi v2.0.0