Request:-
curl -v https://httpbin.org/get
> GET /get HTTP/1.1
> Host: httpbin.org
> User-Agent: curl/8.9.1
> Accept: */*

Response:-
< HTTP/1.1 200 OK
< Content-Type: application/json
< Content-Length: 345
< Server: gunicorn/19.9.0
< Date: Mon, 02 Jun 2025 12:00:00 GMT

{
  "args": {},
  "headers": {
    "Accept": "*/*",
    "Host": "httpbin.org",
    "User-Agent": "curl/8.9.1"
  },
  "origin": "203.0.113.195",
  "url": "https://httpbin.org/get"
}
