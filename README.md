# 🚀 GSTIN Lookup API
A fast and scalable GSTIN verification and business lookup platform built using FastAPI, designed to provide real-time GST details through a simple web interface and developer-friendly API.

**GSTIN Lookup** is a high-performance API service designed to verify Indian Goods and Services Tax Identification Numbers (GSTIN) and retrieve associated business information efficiently.

[**Live Service**](https://gst-lookup.onrender.com) • [**API Documentation**](https://gst-lookup.onrender.com/docs) • [**Report Issue**](https://github.com/Mr-Bhardwa7/gstin_lookup/issues)

---

## 💎 Key Features

- 🔍 **GSTIN Verification**: Validate GST numbers and fetch associated business details.
- ⚡ **High Performance API**: Built with FastAPI for fast and reliable responses.
- 🧠 **Smart Caching**: Optimized PostgreSQL caching for improved response times.
- 🌐 **Integrated Web Interface**: Simple UI for quick GST lookups.
- 🚦 **Rate Limiting**: Protects the API from excessive usage and abuse.

## 🚦 Quotas & Plans

| Plan | Per Minute | Per Day | Best For |
| :--- | :--- | :--- | :--- |
| **Free** | 10 | 50 | Developers & Small Tests |
| **Pro** | 60 | 500 | Growing Businesses |
| **Enterprise** | 60 | 1000 | High-volume Platforms |

## 🛠️ How to Use

Make a simple GET request to verify a GSTIN:

```
GET /api/v1/gst/lookup/27AAAAA0000A1Z5
x-gst-api-key: YOUR_API_KEY
```

## 🤝 Support & Feedback 
This repository serves as the public landing page and issue tracker for the GST Lookup service. 
- **Found a bug?** Open an [Issue](https://github.com/Mr-Bhardwa7/gstin_lookup_public/issues). 
- **Need help?** Check the [Documentation](https://gst-lookup.onrender.com/api-documentation). 
- **Feedback?** We value your suggestions to improve the service! 

--- *© 2026 GST Lookup. All rights reserved. This project is proprietary.*
