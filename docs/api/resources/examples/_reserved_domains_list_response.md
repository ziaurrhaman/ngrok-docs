<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-08-06T10:08:27Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.32rirsbcuvkbafpb2.local-ngrok-cname.com",
      "created_at": "2025-08-06T10:08:26Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30uQJlKEAtjxn30ZMmjyohZH2Jv",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30uQJlKEAtjxn30ZMmjyohZH2Jv"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_30uQJWpaKJoiAASETUUVGF3xBZg",
        "uri": "https://api.ngrok.com/tls_certificates/cert_30uQJWpaKJoiAASETUUVGF3xBZg"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.32rirsbcuvkbafpb2.local-ngrok-cname.com",
      "created_at": "2025-08-06T10:08:26Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30uQJcuT5Jg2PajcGIz4V4DPUiE",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30uQJcuT5Jg2PajcGIz4V4DPUiE"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-06T10:07:56Z",
      "description": "Your dev domain",
      "domain": "positive-gopher-allowing.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_30uQFqD4tMUEOqEUN3jPSdNUovY",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_30uQFqD4tMUEOqEUN3jPSdNUovY"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
