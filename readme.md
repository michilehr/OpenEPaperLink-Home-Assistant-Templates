# OpenEPaperLink Home Assistant Templates
Here you can find my templates for the Electronic Shelf Labels powered by [OpenEPaperLink](https://openepaperlink.org/) and the [Home Assistant integration](https://github.com/OpenEPaperLink/Home_Assistant_Integration/blob/main/docs/drawcustom/supported_types.md#download-image).

![showcase.jpg](./preview/showcase.jpg)

All templates are in the `templates` folder. You can use them as a starting point and modify them to fit your needs.

The templates need to be adjusted by the target device id of the OpenEPaperLink device and the source entities you want to display.

| Type             | Resolution | Preview                                                                 | Requirements                                                                                                                                                                                                                                           |
|------------------|------------|-------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 4 Sensor Grid    | 296x152    | ![4_sensor_grid_296x152.jpg](./preview/4_sensor_grid_296x152.jpg)       |                                                                                                                                                                                                                                                        |
| Trash Calendar   | 250x128    | ![trash_calendar_250x128.jpg](./preview/trash_calendar_250x128.jpg)     | [Home Assistant Local Calendar](https://www.home-assistant.io/integrations/local_calendar/) with either manually filled data or automatically by for example [HACS Waste Calendar Schedule](https://github.com/mampfes/hacs_waste_collection_schedule) |
| Weather Forecast | 296x152    | ![weahter_forecast_296x152.jpg](./preview/weahter_forecast_296x152.jpg) | [Home Assistant Weather](https://www.home-assistant.io/integrations/weather/])                                                                                                                                                                         |
| Weather Forecast | 384x184    | ![weahter_forecast_384x184.jpg](./preview/weahter_forecast_384x184.jpg) | [Home Assistant Weather](https://www.home-assistant.io/integrations/weather/])                                                                                                                                                                         |

Feel free to open a merge request to add new templates or open an issue to ask for new ones with a specific idea.