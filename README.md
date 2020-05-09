# Hass.io custom component - Kevo

## What you need

- A Kevo smart lock
- Kevo Plus bluetooth enabled gateway
- Reference : https://www.weiserlock.com/en/kevo/smart-lock

## Needed python module

The ```pykevocontrol``` module is automatically installed when first used of this custom component on Hass.io.

## Custom component setup

Copy these project files into your Home Assistant ```/config``` directory.

```
custom_components/kevo/__init__.py
custom_components/kevo/lock.py
custom_components/kevo/manifest.json
```

congifuration.yaml file entry:
```
# Locks controls
lock:
  - platform: kevo
    email: KEVO_ACCOUNT_EMAIL         # Your Kevo account Email
    password: KEVO_ACCOUNT_PASSWORD   # Your Kevo account Password
```
     
## TODOs

- 

