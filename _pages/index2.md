---
layout: splash
title: WeatherLink Developer Portal
permalink: /index2
header:
  overlay_color: "#000000"
  overlay_filter: "0.0"
  overlay_image: /assets/vendor/weatherlink/images/landing.jpg
# actions:
#   - label: "Download"
#     url: "https://github.com/mmistakes/minimal-mistakes/"
excerpt: "Access your weather station data"
feature_row_v2_api:
  - title: "WeatherLink v2 API"
    excerpt: "Documentation and samples demonstrating the use of the WeatherLink v2 API.<br><br>The WeatherLink v2 API can be used to access weather station metadata and weather observation data for WeatherLink connected weather stations you have access to."
    image_path: /assets/vendor/weatherlink/images/v2_api.jpg
    url: "/v2-api"
    btn_label: "View Documentation"
    btn_class: "btn--primary"
feature_row_airlink_local_api:
  - title: "AirLink Local API"
    excerpt: "Documentation for the AirLink Local API.<br><br>The AirLink Local API can be used to get current conditions directly from an AirLink device using a JSON over HTTP API."
    image_path: /assets/vendor/weatherlink/images/airlink_local_api.jpg
    url: "/airlink-local-api"
    btn_label: "View Documentation"
    btn_class: "btn--primary"
feature_row_weatherlink_live_local_api:
  - title: "WeatherLink Live Local API"
    excerpt: "Documentation and samples demonstrating the use of the WeatherLink Live Local API.<br><br>The WeatherLink Live Local API can be used to get current conditions directly from a WeatherLink Live device using a JSON over HTTP API as well as receive real-time data broadcasts over UDP."
    image_path: /assets/vendor/weatherlink/images/weatherlink_live_local_api.jpg
    url: "/weatherlink-live-local-api"
    btn_label: "View Documentation"
    btn_class: "btn--primary"
feature_row_realtime_data_feed:
  - title: "Real-time Data Feed"
    excerpt: "Documentation and samples demonstrating the use of the WeatherLink Real-time Data Feed.<br><br>The WeatherLink Real-time Data Feed is a real-time data stream of the weather observation data records for WeatherLink connected weather stations you have access to."
    image_path: /assets/vendor/weatherlink/images/realtime_data_feed_lightblue.jpg
    url: "/real-time-data-feed"
    btn_label: "View Documentation"
    btn_class: "btn--primary"
---

{% include feature_row id="feature_row_v2_api" type="left" %}
{% include feature_row id="feature_row_airlink_local_api" type="left" %}
{% include feature_row id="feature_row_weatherlink_live_local_api" type="left" %}
{% include feature_row id="feature_row_realtime_data_feed" type="left" %}
