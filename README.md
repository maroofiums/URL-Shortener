# URL Shortener (Streamlit + FastAPI + TinyURL)

A simple URL shortener app built using **Streamlit** for the frontend and **FastAPI** for the backend.  
It uses the **TinyURL API** to shorten URLs and does **not require any database**.

---

## Features

- Shorten any URL using TinyURL API
- Streamlit frontend for easy interaction
- FastAPI backend for handling API requests
- No database required
- Configurable backend URL using `.env` file

---

## Tech Stack

- **Frontend:** Streamlit
- **Backend:** FastAPI
- **URL Shortening:** TinyURL API
- **Environment Variables:** `python-dotenv`

---

## Usage

1. Enter any URL in the input box.
2. Click **Shorten URL**.
3. The app will show the original URL and the shortened URL (TinyURL).
4. Click the link to open the shortened URL.

---

## Notes

* No database is used; all shortening is handled via TinyURL.
* You can change the backend URL by updating the `.env` file.

---

## Dependencies

* `fastapi`
* `uvicorn`
* `requests`
* `streamlit`
* `python-dotenv`
* `pydantic`


