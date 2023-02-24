# Email Verifier
The best real time email verifier with API 


The best email finder and verifier with real time API provided by https://minelead.io/search/

This repo contains a list of codes in python language that users can see in order to find anyone's profesional email in milliseconds.

This API is real time, it will check if the email exists in Minelead Database as well as searching and verifying inflight all the emails found the it does return them in REST.

more details here : https://minelead.io/docs/


We verify everyday thousands of emails
for thousands of users
CHECK THE VALIDITY OF EMAILS IN THE WEB

STOP BOUNCING !!


## API Reference

#### Verify an email

```http
  GET "https://api.minelead.io/v1/validate/?email=name@example.com&key=yourapikey"
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `key` | `string` | **Required**. Your API key |
| `email` | `string` | **Required**. the email you would like to validate |
