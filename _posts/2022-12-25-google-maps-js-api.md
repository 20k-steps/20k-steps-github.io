---
layout: page
title:  "Test Google Maps Javascript API"
date:   2022-12-25 11:04:42 +0800
categories: draft
---
This page is a placeholder for testing Google Maps Javascript API.

<script>
const mapConfig = {
  zoom: 13,
  center: {
    lat: 1.304094714364756, 
    lng: 103.8319403194047
  }
};

const markersConfig = {
  'start': {
    position: {
      lat: 1.296878195130882, 
      lng: 103.80497131618391
    },
    label: 'S'
  },
  'end': {
    position: {
      lat: 1.32240370244476, 
      lng: 103.81500492284349
    },
    label: 'E'
  }
};

const pathConfig = [
  markersConfig['start'].position,
  [ 1.2964597301768581, 103.80564482924974 ],
  [ 1.295257380463328, 103.8077411854462 ],
  markersConfig['end'].position,
];
</script>

{% include google-maps-js-api.html %}

