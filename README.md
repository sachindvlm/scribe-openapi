# Scribe OpenAPI Specification

This repository contains a basic OpenAPI 3.0 specification (`openapi.json`) for testing REST connections in **TIBCO Scribe**.

## 🔍 Purpose

The OpenAPI file defines a mock API with a `/users` endpoint, backed by a Postman mock server. It is used to help Scribe auto-discover available API resources and test REST connector functionality.

## 🌐 Base URL

The base URL for the mock API is:


## 📄 File Description

- `openapi.json` – OpenAPI 3.0 specification that defines one endpoint:
  - **GET** `/users`: Returns a list of sample users

## 🧪 Usage in TIBCO Scribe

1. Upload `openapi.json` to a public GitHub repo (this one).
2. Copy the **raw URL** of the file.
3. Paste it in the **Specification URI** field while configuring the Scribe REST connection.

## 👤 Author

Created for development/testing purposes.

---

