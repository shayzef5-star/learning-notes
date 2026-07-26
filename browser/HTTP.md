# HTTP

## 🇬🇧 English

## What is HTTP?

HTTP (HyperText Transfer Protocol) is an application-layer protocol used for communication between a client and a server.

When a user opens a website, the browser sends an HTTP request to the server. The server processes the request and returns an HTTP response containing the requested resource or an error message.

---

## HTTP Request

An HTTP request is sent from the client (browser) to the server.

A request usually contains:

- Request method (GET, POST, PUT, DELETE, etc.)
- URL
- Headers
- Optional request body

---

## HTTP Response

The server returns a response containing:

- Status code
- Headers
- Response body

---

## Common Status Codes

### 2xx — Success

- **200 OK** — Request completed successfully.
- **201 Created** — A new resource was successfully created.

### 3xx — Redirection

- **301 Moved Permanently** — Resource has been permanently moved.
- **302 Found** — Temporary redirect.

### 4xx — Client Errors

- **400 Bad Request** — Invalid request.
- **401 Unauthorized** — Authentication required.
- **403 Forbidden** — Access denied.
- **404 Not Found** — Requested resource was not found.

### 5xx — Server Errors

- **500 Internal Server Error** — Internal server error.
- **503 Service Unavailable** — Server is temporarily unavailable.

---

## What can QA check?

A QA engineer can verify:

- correct HTTP status codes;
- API responses;
- missing resources;
- redirects;
- loading failures.

---

## What I learned

- HTTP is the protocol used for communication between browsers and servers.
- Every request receives an HTTP response.
- Status codes help identify whether the request was successful or why it failed.
- Browser DevTools (Network) allows inspection of HTTP requests and responses.

---

# HTTP

## 🇷🇺 Русский

## Что такое HTTP?

HTTP (HyperText Transfer Protocol) — это прикладной протокол передачи данных, который используется для обмена информацией между клиентом (например, браузером) и сервером.

Когда пользователь открывает сайт, браузер отправляет HTTP-запрос на сервер. Сервер обрабатывает этот запрос и возвращает HTTP-ответ с нужными данными или сообщением об ошибке.

---

## HTTP-запрос

HTTP-запрос отправляется от клиента к серверу.

Обычно он содержит:

- метод запроса (GET, POST, PUT, DELETE и др.);
- URL;
- заголовки (Headers);
- тело запроса (при необходимости).

---

## HTTP-ответ

После обработки запроса сервер отправляет ответ, который содержит:

- HTTP-статус;
- заголовки;
- тело ответа.

---

## Основные HTTP-статусы

### 2xx — Успешное выполнение

- **200 OK** — запрос успешно выполнен.
- **201 Created** — ресурс успешно создан.

### 3xx — Перенаправление

- **301 Moved Permanently** — ресурс был окончательно перенесён.
- **302 Found** — временное перенаправление.

### 4xx — Ошибки клиента

- **400 Bad Request** — неверный запрос.
- **401 Unauthorized** — требуется авторизация.
- **403 Forbidden** — доступ запрещён.
- **404 Not Found** — запрашиваемый ресурс не найден.

### 5xx — Ошибки сервера

- **500 Internal Server Error** — внутренняя ошибка сервера.
- **503 Service Unavailable** — сервер временно недоступен.

---

## Что может проверить QA?

Тестировщик может проверить:

- корректность HTTP-статусов;
- ответы API;
- отсутствие ошибок загрузки ресурсов;
- правильность перенаправлений;
- успешность выполнения запросов.

---

## Что я понял

- HTTP — основной протокол обмена данными между браузером и сервером.
- Каждый запрос получает ответ от сервера.
- HTTP-статусы помогают определить результат выполнения запроса.
- Во вкладке Network в DevTools можно анализировать HTTP-запросы и ответы сервера.
