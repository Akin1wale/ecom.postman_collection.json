# ecom.postman_collection.json
This portfolio project demonstrates API testing for authentication and product catalog workflows using Postman. The APIs tested are ReqRes (for login simulation and user retrieval) and DummyJSON (for product search and retrieval).

# QA API Portfolio (Postman) – ReqRes + DummyJSON

This repo contains a Postman **collection** and **environment** for a QA portfolio project.

## Files
- `QA_Portfolio_ReqRes_DummyJSON.postman_collection.json` – 5 requests:
  - ReqRes: Login success, Login fail, Users page 2
  - DummyJSON: Products search, Product by ID
- `QA_Portfolio_Env.postman_environment.json` – environment variables (base URLs, email, password, and saved values like productId).

## How to Use
1. Download both JSON files (or import via the GitHub Raw links).
2. In Postman, click **Import** → add the **collection** and **environment**.
3. Select the environment in the top-right of Postman.
4. Run the requests in order; see tests pass (green checks).

## Tech
Postman (tests using `pm` API), ReqRes (fake auth/users), DummyJSON (products).
