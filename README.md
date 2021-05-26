# Golang Containerization

- Clone Proyek dengan:

```bash
$ git clone https://github.com/xhartono/golang.git
```

- Build Image dengan:

```bash
$ docker image
$ docker build -t inixindo/hello .
$ docker image
```

- Jalankan container dari hasil image:

```bash
$ docker ps
$ docker run --rm --name go1 -p 80:80 -d inixindo/hello
$ docker ps
```

- Lihat apakah port 80 sudah aktif ?

```bash
$ ss -tulpn | grep 80

atau 

$ netstat -tulpn | grep 80
```

- Akses web aplikasi hello golang dengan curl:

```bash
$ curl localhost
```

- Atau melalui browser URL:

```
URL: http://localhost
```



