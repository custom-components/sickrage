# service.sickrage
  
[![Version](https://img.shields.io/badge/version-0.0.1-green.svg?style=for-the-badge)](#) [![mantained](https://img.shields.io/maintenance/yes/2018.svg?style=for-the-badge)](#) [![maintainer](https://img.shields.io/badge/maintainer-swetoast-blue.svg?style=for-the-badge)](#) [![forum](https://img.shields.io/badge/forum-visit-orange.svg?style=for-the-badge)](https://community.home-assistant.io/t/raspberry-pi-power-sensor-updated-2018-07-03/58155)   
Taps into the sickrage api and lets you perform basic commands

To get started put `/custom_components/sickrage/__init__.py` and `/custom_components/sickrage/services.yaml` into your configuration directory   
  
**Example configuration.yaml:**

```yaml
sickrage:
  host: 'http://example.com:8081/api'
  api_key: 'your_api_key'
```

**Configuration variables:**  
  
key | description  
:--- | :---  
**Sickrage** | any version  
  
  
[Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)  
***
Due to how `custom_componentes` are loaded, it is normal to see a `ModuleNotFoundError` error on first boot after adding this, to resolve it, restart Home-Assistant.
