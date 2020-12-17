# Ads & Geolocation datasets

## CSV dataset

### Fields

- `source` Application used to collect the post. One of `fb_app`, `fb_mobile`, `twitter_mobile`, `instagram_app`, `instagram_mobile`.
- `granted_permissions` Was the app granted location permissions ? One of `True` or `False`.
- `user_id` Identifer for the account collecting the data, 10 last characters of the sha256sum of the email of the account used to collect data
- `timestamp` ISO formatted string of the collection date
- `latitude` Geolocation of the mobile phone during the location.
- `longitude` Geolocation of the mobile phone during the location.
- `ip` Public IP of the phone during the collection
- `spoofed_gps` Was the GPS position being spoofed during data acquisition ? Either `True` or `False`.
- `spoofed_ip` Was the device IP being spoofed during data acquisition to match GPS position ? Either `True` or `False`.
- `spoofed_ap` Were nearby Access Points being spoofed during data acquisition to match GPS position ? Either `True` or `False`.

