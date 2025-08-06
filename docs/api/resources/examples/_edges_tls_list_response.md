<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-06T10:08:54Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_30uQN8W5PX99ShwUex5MA26Pqe2",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30uQN8W5PX99ShwUex5MA26Pqe2"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_30uQLapowYwmRtVQnBNyLHbDFje",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_30uQLapowYwmRtVQnBNyLHbDFje"
        },
        "enabled": true
      },
      "created_at": "2025-08-06T10:08:42Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_30uQLaden3eCghmjzz7gHEezfDf",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30uQLaden3eCghmjzz7gHEezfDf"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
