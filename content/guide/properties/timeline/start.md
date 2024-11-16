---
title: "Start date"
linkTitle: "Start"
weight: 30
---

<i class="bigIcon">{{< icon "startDate" >}}</i>

The date [operation status]({{< ref "status" >}}) became `active`.


## Fields

| Field         | Summary                     		    |
| ------------- | ------------------------------------- |
| `date`   | As `Year`, `Year + Month` or `Year + Month + day`     |
| `note`  	| Any relevant information to give context    |
| `replaced`   | Property that previously occupied the space {{< badge content="Multi-value" type="info" >}}     |
| `relocation`   |  Moved from a different location with same core experience    |

## Usage

### Date

Communicates the calendar date the `operational status` of a proeprty is changed to `active`.

A timeline can have multiple `Start dates` if a property is replaced, and later the original property is brought back to replace the new one.

### Replaced

Property previously occupying the space. In some instances, there may be no prior tenants. The reverse reference ([Replaced by]({{< ref "end#replaced-by" >}})) is automatically generated.

### Relocation

Noted when a property moved from a previous location with the same base experience (excluding any theme alterations or ehancements). The reverse reference ([Relocated to]({{< ref "end#relocation" >}})) is automatically generated.

## Example

### Single start date

The `start date` for `Spaceship Earth` at `EPCOT` is `1982 Oct 1`

### Multiple start dates

The `start date` for `Happily Ever After` at `Magic Kingdom` is:
* `2017 May 12`
* `2023 Apr 3`

Each start date is a unique point on the timeline.