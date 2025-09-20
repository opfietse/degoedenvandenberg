# De Goed en van den Berg
Bootstrap site.

## Compile sass to ccss
```
#sass scss/dgvdb.scss css/dgvdb-sass.css
dart compile-sass.dart scss/dgvdb.scss css/dgvdb-sass.css
```

## Transfer to kubernetes
```
rsync --recursive --links --times * kube05:/home/rvk/nfs/dgvdb
```
