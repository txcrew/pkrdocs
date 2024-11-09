---
title: "Replaced"
weight: 40
---

<i class="bigIcon">{{< icon "replaced" >}}</i>

Record of the property that occupied the space prior to the current property.

## Fields

| Field         | Summary                     		    |
| ------------- | ------------------------------------- |
| `property`   | Reference property {{< badge content="Multi-value" type="info" >}}     |
| `date`   | As `Year`, `Year + Month` or `Year + Month + day`     |
| `note`  	| Any relevant information to give context    | 

## Example

### One to one

When one property replaces another property.

* `Mission: Space` replaced `Horizons` at `EPCOT`
* `Goliath` replaced `Iron Wolf` at `Six Flags Great America` 

### One to many

When one property replaces multiple properties.

* `Déjà Vu` replaced `Sky Whirl`, `Hay Baylor` and `Demon Nachos` at `Six Flags Great America`

### Reverse reference

The reverse reference (replaced by) is automatically generated on the referenced property's timeline.

* `Horizons` was replaced by `Mission: Space` at `EPCOT`
* `Sky Whirl` was replaced by `Déjà Vu` at `Six Flags Great America`
