<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-06T10:08:47Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_30uQLYtutyWQOviTEAIGi3JRPKX",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30uQLYtutyWQOviTEAIGi3JRPKX"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30uQMELzoQnAJdsTQc5ofQmdYGf",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-06T10:08:47Z",
      "uri": "https://api.ngrok.com/endpoints/ep_30uQMELzoQnAJdsTQc5ofQmdYGf",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-06T10:08:45Z",
      "hostport": "b68edd0391dc.ngrok.paid:443",
      "id": "ep_30uQLx17IVh6cWckY4Le8TIGlyy",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_30uQFRwErfGMlHc8w2J0fc1FRHK",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://b68edd0391dc.ngrok.paid",
      "tunnel": {
        "id": "tn_30uQLx17IVh6cWckY4Le8TIGlyy",
        "uri": "https://api.ngrok.com/tunnels/tn_30uQLx17IVh6cWckY4Le8TIGlyy"
      },
      "tunnel_session": {
        "id": "ts_30uQLzs32iX6O9BahLKAbDSQkeI",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_30uQLzs32iX6O9BahLKAbDSQkeI"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-06T10:08:45Z",
      "upstream_url": "http://localhost:80",
      "url": "https://b68edd0391dc.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-06T10:08:42Z",
      "domain": {
        "id": "rd_30uQLYtutyWQOviTEAIGi3JRPKX",
        "uri": "https://api.ngrok.com/reserved_domains/rd_30uQLYtutyWQOviTEAIGi3JRPKX"
      },
      "edge": {
        "id": "edgtls_30uQLaden3eCghmjzz7gHEezfDf",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_30uQLaden3eCghmjzz7gHEezfDf"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_30uQLXMbVuyCtlpu1U7tVFFm8pd",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-06T10:08:42Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
