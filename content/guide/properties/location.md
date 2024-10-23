---
title: "Location"
weight: 19
next: /guide/properties/classifications
---

Location refers to the specific coordinates that define a property’s position on a map, as well as its relationship to any encompassing parent property. 

Most all properties have a physical location, save for property types that travel (ex: Cruise ships).

## Coordinates

Numerical values that specify a precise location on a map, visualized with a pin to indicate the property's position.

## Located within

Properties that are located within another property are displayed together in a hierarchical in a location tree.

Example
* `Tomorrowland` is in located within `Magic Kingdom`
* `California Adventure` is located within `Disneyland Resort`
* `Brooklyn` is located within `New York City`

Example of location tree
{{< filetree/container >}}
  {{< filetree/folder name="Walt Disney World Resort" >}}
    {{< filetree/folder name="EPCOT" >}}
    	{{< filetree/folder name="World Discovery" >}}
    		{{< filetree/folder name="Sim Track" >}}
    			{{< filetree/file name="Test Track" >}}
    		{{< /filetree/folder >}}
    	{{< /filetree/folder >}}
     {{< /filetree/folder >}}
  {{< /filetree/folder >}}
{{< /filetree/container >}}

