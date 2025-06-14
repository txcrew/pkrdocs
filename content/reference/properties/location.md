---
title: "Location"
weight: 19
next: /guide/properties/classifications
---

{{< options section="Location" >}}

Location refers to the specific coordinates that define a property’s position on a map, as well as the nearest property its located within. 

## Coordinates

Numerical values that specify a precise location on a map, visualized with a pin to indicate the property's position.

### Examples
* `Spaceship Earth` at `EPCOT` is at coordinates `28.3755,-81.5494`
* `California Adventure` is at coordinates `33.8062,-117.9199`


> [!NOTE]
> Properties that travel (Ex: Cruise ships) do not have stationary coordinates.

## Located within

Properties that are located within another property are displayed together in a hierarchical in a location tree.

### Usage
Identifying the single _closest_ property that a property is located within.

In the following location tree example, `Test Track` is located within `Sim Track`.

{{< filetree/container >}}
  {{< filetree/folder name="Walt Disney World Resort (Resort)" >}}
    {{< filetree/folder name="EPCOT (Park)" >}}
      {{< filetree/folder name="World Discovery (Area)" >}}
        {{< filetree/folder name="Sim Track (Venue)" >}}
          {{< filetree/file name="Test Track (Attraction)" >}}
        {{< /filetree/folder >}}
      {{< /filetree/folder >}}
     {{< /filetree/folder >}}
  {{< /filetree/folder >}}
{{< /filetree/container >}}

It can be inferred that `Test Track` is in `EPCOT` based on the closest proeprty it's located within.

### Examples
* `Tomorrowland` is in located within `Magic Kingdom`
* `California Adventure` is located within `Disneyland Resort`
* `Brooklyn` is located within `New York City`
