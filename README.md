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
![1](https://user-images.githubusercontent.com/55675935/134435422-927ad90f-2ca4-4bc3-8553-114eb42b11bc.png)
* Passing Data menggunakan URL Dynamic Segment
Pada views job terdapat list job, ketika salah satu di klik, maka halaman akan berpindah ke halaman job yang dipilih dan akan menampilkan id dari halaman yang dipilih tersebut.
![4](https://user-images.githubusercontent.com/55675935/134435497-ad50766c-5122-40dc-afb2-aa8522f4fb41.png)
* untuk menuju halaman selanjutnya pada <route-links> menggunakan named routes yang ditambahkan parameter untuk menuju ke views detail job yang sesuai.
![2](https://user-images.githubusercontent.com/55675935/134435491-6c333a53-c770-4978-a62d-10899fcb8ad6.png)
* pada jobsdetail id didapatkan dengan menggunakan props
![3](https://user-images.githubusercontent.com/55675935/134435496-db3359bc-e2a7-4311-bac8-d255c6dc81ca.png)
* maka hasilnya
