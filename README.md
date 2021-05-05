# express-boilerplate

An expressjs boilerplate that uses pug as view engine, stylus as css engine and bootstrap as css framework.

It uses pug version "^3.0.2" and stylus version "0.54.8"

It creates an alias for bootstrap in app.js
```
app.use("/bootstrap", express.static(path.join(__dirname, '/node_modules/bootstrap/dist')));
```
With this alias, Boostrap stylesheets and javascript can be loaded using:
```
    link(rel='stylesheet', href='/bootstrap/css/bootstrap.min.css')
    script(src='/bootstrap/js/bootstrap.bundle.min.js')
```

Boostrap-icons are load using 
```
    link(rel="stylesheet", href="/bootstrap-icons/font/bootstrap-icons.css")
```
