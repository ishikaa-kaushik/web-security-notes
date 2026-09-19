# HTTP vs HTTPS (Quick Summary)

- **HTTP (Hypertext Transfer Protocol)** is how a browser (client) and a website (server) communicate using a **request → response** model.
- An **HTTP request** asks for a resource (page/API) using methods like **GET** or **POST**.
- An **HTTP response** returns data with a **status code** (e.g., 200, 301/302, 401, 403, 404, 500) plus headers and a body.

- **HTTPS** is **HTTP over TLS** (encrypted).
- HTTPS provides:
  1) **Confidentiality** (others can’t read your data),
  2) **Integrity** (data can’t be silently changed),
  3) **Authentication** (the server proves its identity using a certificate).

- **HTTP is not safe** for logins or sensitive data because traffic is plain text.
- **HTTPS is the standard** for secure browsing; it protects passwords, cookies, and page/API content in transit.
- Even with HTTPS, some metadata (like the domain and IP) may still be visible, but the **content** is encrypted.
