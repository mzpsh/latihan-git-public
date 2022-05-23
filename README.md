# Tips
## Periksa lagi di branch mana
```
git branch
```
## Periksa file mana yang belum di simpan
```
git status
```

# Tutorial

## 1. Download repo ke device kamu dan pindah folder
```
git clone https://github.com/mzpsh/latihan-git-public.git
cd latihan-git-public
```
## 2. Bikin branch baru untuk penambahan fitur
```
git checkout -b "fitur-baru"
```
## 3. Pindah ke branch yang baru
```
git checkout fitur-baru
```
## 4. Edit file atau tambah file
## 5. Simpan dan commit hasil perubahan
```
git add *
git commit -m "penambahan fitur baru, dan lainnya"
```
## 6. Beralih ke branch main
```
git checkout main
```
## 7. Update branch main sebelum melakukan merge(penggabungan)
```
git pull
```
## 8. Gabungkan branch baru dengan main
```
git merge fitur-baru
```
## 9. Simpan, commit, dan upload hasil perubahan
```
git add *
git commit -m "penambahan fitur baru, dan lainnya"
git push origin main
```
## 10. Hapus branch yang tidak terpakai
```
git branch -d "fitur-baru"
```


Testing
teesss
