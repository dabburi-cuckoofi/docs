---
sidebar_position: 1
---

# Using an API key with REST

You can pass the API key into a REST API call as a header with the following format. 
Replace api_key with the key string of your API key and your_domain with your company domain.

For example, to pass an API key for a Rewards Gift Card Brands API request for listing brands:

```bash
curl -X POST \
-H "x-ckf-api-key: API_KEY" \
-H "Content-Type: application/json; charset=utf-8" \
"https://rewards.your_domain.com/api/v1/gift-cards/brands"
```

# Secure an API key

- When you use API keys in your applications, ensure that they are kept secure during both storage and transmission. Publicly exposing your API keys can lead to unexpected charges on your account. To help keep your API keys secure, follow these best practices:

- Add API key restrictions to your key.

- By adding restrictions, you can limit the ways an API key can be used, reducing the impact of a compromised API key.
Delete unneeded API keys to minimize exposure to attacks.
Recreate your API keys periodically.

- Periodically create new API keys, delete the old keys, and update your applications to use the new API keys.
