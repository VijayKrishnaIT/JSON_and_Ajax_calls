# JSON Server

==> http://localhost:3000/products (GET) (5 records)

==> http://localhost:3000/products?\_sort=p_cost&\_order=asc

==> http://localhost:3000/products?\_sort=id&\_order=desc

==> http://localhost:3000/products?\_start=0&\_end=3

Greater than and Less than example

==>http://localhost:3000/products?id_gte=3

==> http://localhost:3000/products?p_cost_lte=30000

==> http://localhost:3000/products?id_ne=3

==> http://localhost:3000/products?p_name_like=p_one

==> http://localhost:3000/products?q=50000

Reference: https://www.npmjs.com/package/json-server

# Synchronous calls

making calls one after another.

# Asynchronous calls

Server executes all the requests at a time.

No relation between client 1 to client 2.

How to make Aysnchonous calls?

## JavaScript

XMLHttpRequest

## jQuery

\$.ajax()

## AngularJS

\$http

## Angular 11

HttpClient

## ReactJS

axios

# jQuery CDN

Add jQuery CDN in the header section

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

## Multiple Ajax calls

2 API \$.ajax({})
