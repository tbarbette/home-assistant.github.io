---
layout: page
title: "VLC"
description: "Instructions on how to integrate VLC media player into Home Assistant."
date: 2016-11-02 12:02
sidebar: true
comments: false
sharing: true
footer: true
logo: videolan.png
ha_category: Media Player
featured: false
ha_release: 0.35
ha_iot_class: "Local Polling"
---

The `vlc` platform allows you to control [VLC media player](http://www.videolan.org/vlc/index.html).

To add a VLC media player to your installation, add the following to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
media_player:
  - platform: vlc
```

Configuration variables:

- **name** (*Optional*): The name to use in the frontend.

