# Providers
## Disconnect from Provider
### HTTP Request

`GET https://api.ecoautomation.com/provider/disconnect`
= 'providers/disconnect';

## Provider Callback for OAuth
### HTTP Request

`GET https://api.ecoautomation.com/provider/(:any)/callback`
= 'providers/callback/$1';

## Connected Devices
### HTTP Request

`GET https://api.ecoautomation.com/provider/(:any)/devices`
= 'providers/devices/$1';

## Available Devices
### HTTP Request

`GET https://api.ecoautomation.com/provider/(:any)/available`
= 'providers/available/$1';

## Add Provider Device
### HTTP Request

`GET https://api.ecoautomation.com/provider/(:any)/device/add`
= 'providers/deviceAdd/$1';

## Remove Provider Device
### HTTP Request

`GET https://api.ecoautomation.com/provider/(:any)/device/remove`
= 'providers/deviceRemove/$1';

## Undo??
### HTTP Request

`GET https://api.ecoautomation.com/provider/(:any)/device/undo`
= 'providers/deviceUndo/$1';


