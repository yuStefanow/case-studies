# Authentication & Authorization

EXPLORE - How it works, why to use, key features, when to use

---
## OAuth 2.0
---

* **Client Credentials Flow:** When the client authenticates using its own credentials.

* **Authorization Code Flow:** A typical flow for web apps, where the user grants permission and gets an authorization code.

* **Implicit Flow:** Used in browser-based apps, where the token is returned directly.

* **Refresh Tokens:** Allows long-lived sessions by using a refresh token to get a new access token without re-authenticating.

---
## JWT (JSON Web Tokens)
---

* **Stateless Authentication:** JWTs store claims (like user ID) and are signed to verify integrity.

* **Secure Handling:** JWTs should be securely transmitted (e.g., via HTTPS) and have an expiration time.

---
## API Keys
---

* **Static or Dynamic:** API keys can be assigned at account creation or generated dynamically for specific use cases.

* **Key Rotation:** Periodically changing API keys to enhance security.

---
## Role-Based Access Control (RBAC)
---

* **Permissions:** Assign roles (admin, user, guest) with defined permissions (read, write, delete).
* **Least Privilege:** Users should only have the minimum level of access necessary

---
## Attribute-Based Access Control (ABAC)
---