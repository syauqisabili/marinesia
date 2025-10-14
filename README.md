![Marinesia](https://db.marinesia.com/storage/v1/object/public/assets//marinesia-logo-dark-smooth.png)

[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Offering+a+simple+way+to+access;Ships;Ports;Live+Streams)](https://git.io/typing-svg)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/syauqisabili/marinesia/commits/master/) [![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://marinesia.com) [![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/syauqisabili/marinesia/issues)
# Marinesia - Marine API

**Marinesia** is a free-to-use, lightweight and modern API designed for maritime applications. It provides APIs that support real-time vessel tracking, historical movements, ship profile management, global port registry, and location-aware CCTV live streams.

- Portal: [https://marinesia.com](https://marinesia.com)
- Documentation: [https://docs.marinesia.com](https://docs.marinesia.com)


## Features

- Vessel location (AIS)
- Vessel profile with image
- Global port directory
- Live CCTV streaming from onboard locations


## Getting started

#### Get Latest Vessel Location by MMSI

```http
  GET https://api.marinesia.com/api/v1/vessel/${MMSI}/profile?key=${YOUR_API_KEY}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `MMSI` | `string` | **Required**. MMSI (Maritime Mobile Service Identity) |
| `YOUR_API_KEY` | `string` | **Required**. Your API key |


## Give a Star 🌟
You can give this repository a star to show more people and they can use this repository


## Support and Feedback

- Support: https://buymeacoffee.com/syauqisabili
- Feedback: contact@marinesia.com
