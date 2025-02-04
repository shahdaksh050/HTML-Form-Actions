# HTML GET and POST Actions

This README explains how to use the `GET` and `POST` methods in HTML forms. These methods are commonly used to send data from an HTML form to a server for processing.

## Table of Contents

1. [GET Method].
2. [POST Method]
4. [Example Form Using GET].
5. [Example Form Using POST].

---

### GET Method

The `GET` method is used to send data to the server as part of the URL. This method appends the form data to the URL, making it visible in the browser's address bar. It is typically used for retrieving data.

- **Data Visibility**: Data is visible in the URL (in the address bar).
- **Data Size Limit**: Limited by the URL length (typically around 2048 characters).
- **Use Case**: Ideal for search queries, filtering, and when the action is non-sensitive and does not involve modifying server data.

### POST Method

The `POST` method is used to send data to the server as part of the HTTP request body, rather than in the URL. This method does not append the data to the URL, making it more secure for sending sensitive information. It is typically used for submitting data.

- **Data Visibility**: Data is not visible in the URL.
- **Data Size Limit**: No practical limit (depending on server configuration).
- **Use Case**: Ideal for submitting sensitive data (e.g., passwords, payment details), form submissions that modify server data (e.g., creating a new user or updating information), or when the data is too large to be sent 
                via GET.
