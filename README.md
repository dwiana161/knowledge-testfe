# ninja-jobs

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Built with

The project was developed using :
* Vue js
* Vue-Router

This app show different page by using vue-router
* router-link 
### `mendefinisikan path URL dari views yang dituju`
* router-view
### `menampilkan view halaman yang dituju`
* Passing Data menggunakan URL Dynamic Segment
Pada views job terdapat list job, ketika salah satu di klik, maka halaman akan berpindah ke halaman job yang dipilih dan akan menampilkan id dari halaman yang dipilih tersebut.
* untuk menuju halaman selanjutnya pada <route-links> menggunakan named routes yang ditambahkan parameter untuk menuju ke views detail job yang sesuai.
* pada jobsdetail id didapatkan dengan menggunakan props
* maka hasilnya
