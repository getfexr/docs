---
sidebar_position: 2
---

# Decentralised Signing  

Format for signing request data (QR, NFC)

```json title="Example incoming signature request"
{
    "type": "sync-v1",
    "request" : {
        "for_did": "Qm....",
        "display_name": "...",
        "reason": "...",
        "from_did": "Qm....",
        "payload" : {
            "data": "...."
        },
        "signature_type": "default",
        "timestamp": "...."
    },
    "theme": {
        "gradient_color_one" : "#...",
        "gradient_color_two" : "#...",
    }
}
```