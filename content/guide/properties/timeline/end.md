---
title: "End date"
linkTitle: "End"
weight: 40
---

<i class="bigIcon">{{< icon "endDate" >}}</i>

The date [operation status]({{< ref "status" >}}) became `defunct`.


## Fields

| Field         | Summary                     		    |
| ------------- | ------------------------------------- |
| `date`   | As `Year`, `Year + Month` or `Year + Month + day`     |
| `note`  	| Any relevant information to give context    |
| `replaced by`   | Property that succeeded the original property {{< badge content="Multi-value" type="info" >}}     |
| `relocation`   |  Moved to a different location with same core experience    |

## Usage

### Date

Start dates are used to communicate when a property `operational status` is changed to `defunct`.

A timeline can have multiple `End dates` if a property is [replaced]({{< ref "replaced" >}}) by a new one, then the original property is brought back and later it gets replaced again by something completely different.

### Replaced by

Property that occupied the space after the current property. In some instances, there may not be a successor. The reverse reference ([Replaced]({{< ref "start#replaced" >}})) is automatically generated.

### Relocation

Noted when a property moves to a new location with the same base experience (excluding any theme alterations or ehancements). The reverse reference ([Relocated from]({{< ref "start#relocation" >}})) is automatically generated.

## Example

### Single end date

The `end date` for `The Living Seas` at `EPCOT` is `2005 Aug 21`


### Multiple end dates

The `end date` for `Captain EO` at `EPCOT` is:
* `1996`
* `2015`

Each start date is a unique point on the timeline.