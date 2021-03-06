# Assurance API Python Plugin
A python script which acts as a bridge between Grafana and the Inmarsat Assurance API. By using this plugin, you agree to the licence agreement in LICENSE.md. 

To enable Grafana to gather data from the Inmarsat REST APIs, a bridge is needed. The Simple JSON data source in Grafana coupled with a Flask webserver, is provided as an example bridge. The Flask webserver exposes endpoints which query the Inmarsat API and return assurance data a specified JSON format. The Simple JSON data source then queries the Flask webserver’s endpoints, and feeds the data into Grafana.

This is an example of a dashboard which can be created using the plugin:

![alt text](dashboard_image.jpg)

*Documentation word document* contains more information and installation instructions.

*Grafana json file* contains an example dashboard, in JSON format.

*flask_bridge.py* is the python code.

*dashboard_image.jpg* is an image of an example dashboard.
