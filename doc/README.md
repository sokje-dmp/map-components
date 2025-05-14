# Introduction

MapComponents (Lagvælgeren) is an (NPM) package containing web frontend components intended to be generally useful for applications that include a map. MapComponents is made and distributed by DMP (Danmarks Miljøportal) and integrates with DMP's central dataset catalogue, allowing easy access to all their public datasets.

MapComponents offers the following UI components:

* LayerControl, this controls which layers are shown on the map (danish name Lagvælger or LV)
* DataStore, the datastore is an overview of all the datasets that can be added to the map (danish name Databutik or DB)
* Attribution, this tells the user what the source of the layer is
* LayerToggle, this enables you to turn the layers on or off.

See frontend [components usage](./usage/components.md) to get started.

For more advanced scenarios it's also possible to directly use an [API](./usage/api.md) to access
the dataset catalog without using the components.

# Access to MapComponents
MapComponents is currently only available through an internal Azure DevOps Artifact feed as it is mostly intended for internal DMP solutions. 
If you would like access as an external party, please contact our support at - support@miljoeportal.dk or use our online contact formula at - https://support.miljoeportal.dk/hc/da/requests/new

# Caveats

- Coordinate system EPSG:25832 is assumed and other projections aren't supported at this time

