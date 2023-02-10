# Spin-Brainfuck App

This is an example of running brainfuck on fermyon cloud.

## steps

- Install the `@surma/bf2wasm` npm package
  
```shell
$ npm install
```
- Compile 
 
```shekll
$ spin build
```

- Test locally

```
$ spin up &
$ curl -i localhost:3000
HTTP/1.1 200 OK
content-type: text/html
content-length: 20
date: Fri, 10 Feb 2023 00:57:05 GMT
$ killall spin
```

- Deploy!!

```shell
$ spin deploy
```

