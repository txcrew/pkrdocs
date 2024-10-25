---
title: "Timeline"
---

A chronological sequence of events that outlines significant milestones, developments, and changes related to a property. 

Events on a timeline are represented as `points` with various types. Points are sorted by date going from oldest -> latest.

## Point types

In additon to type specific fields, all point types include the following fields:

| Field         | Summary                     		    |
| ------------- | ------------------------------------- |
| `date`   | Accepts `Year`, `Year + Month` or `Year + Month + day`        			        |
| `notes`  	| Any relevant information to give context    |


### Start date
The date [operation status]({{< ref "status" >}}) became `active`.

A timeline can have multiple `Start dates` if a property is replaced, and later the original property is brought back to replace the new one.

### End date

The date [operation status]({{< ref "status" >}}) became `defunct`.

A timeline can have several `End dates`. For example, if a property is replaced by a new one, then the original property is brought back and later it gets replaced again by something completely different.

### Name change

Record of an official property `name` alterations.

Adds the following fields:

| Field            | Summary                     		   |
| ---------------  | ------------------------------------- |
| `previous name`  | Previous name of proprty       	   |
| `new name`  	   | New name of proprty   				   |


### Theme change

Objective change in color palette, theme elements or story.

Example
* The track was repainted from black to yellow
* Story setting changed from the woods to the city
* Hundreds of LED Lights added to exterior facade

### Milestone

Record of a noteworthy event

Example
* A dedication ceremony
* New on-ride photo feature was added
* Restraints were modified to be more comfortable

### Sponsorship

The start, change or end of an organization that sponsors a property

### Relocation

The record of a property moving to (or from) a new location and name. Relocations are always placed as the first or last point on a timeline, depending on the `direction`.

| Field         | Summary                     		    |
| ------------- | ------------------------------------- |
| `direction`   | To or From          			        |
| `location`  	| Name of new (or previous) location    |
| `as`  		| New (or previous) property name 	    |

**Example**

1. `Swings` relocated `to` `Orleans Place` as `Whirligig`
2. `Whirligig` relocated `from` `Yukon Territory` as `Swings`

The reverse reference is automatically generated on the referenced property's timeline.

### Replaced

Record of the property that occupied the space prior to the current property.

| Field         | Summary                     		    |
| ------------- | ------------------------------------- |
| `properties`   | Reference any existing properties    |

Similar to relocation, the reverse reference is automatically generated on the referenced property's timeline.


## Dates

Dates per point are not required but offer helpful context.

If a full `Year + Month + Date` is unknown, a hazy date would also be acceptable as either:

* `Year + Month`
* `Year`

## Notes

Each point on a timeline has a notes field. Notes can be anything related to the `point`.