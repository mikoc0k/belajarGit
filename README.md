# Belajar materi GIT di [gitbranch](https://learngitbranching.js.org/)

## Commit

`git commit -m "pesan commitnya apa"`

Bayangkan bahwa commit ibarat checkpoint pada sebuah game.

Sebelum commit, kita harus menginisiasi direktori dari file yang ingin di-git-kan.
`git init <nama file>`

lalu melakukan staging dengan cara :

`git add <nama file>`

atau

`git add .`

## Branch

`git branch <nama_branch>`

contoh penggunaan branch :

`git branch bugFix`

setelah bikin branch, jangan lupa di commit

## Checkout

digunakan untuk keluar dari branch dan berpindah ke branch tertentu.

`git checkout main`

artinya adalah keluar dari branch sekarang, lalu pindah ke branch "main".
