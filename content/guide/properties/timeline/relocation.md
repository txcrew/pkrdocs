---
title: "Relocation"
weight: 60
---

The record of a property moving to (or from) a new location and name.

## Fields

| Field         | Summary                     		    |
| ------------- | ------------------------------------- |
| `direction`   | `To` or `From`          			    |
| `location`  	| Name of new (or previous) location    |
| `as`  		| New (or previous) property name 	    |
| `date`   		| As `Year`, `Year + Month` or `Year + Month + day`     |
| `note`  		| Any relevant information to give context    |

## Usage

Relocations are noted when a property moves to a new location with the same base experience (excluding any theme alterations or ehancements).

{{< callout type="info" >}}
When a property is relocated the origin property `operational status` becomes `defucnt`.
{{< /callout >}}

## Example

A relocation on a timeline can be in either direction; in this case it's `to`.

> `Swings` relocated `to` `Orleans Place` as `Whirligig`

The reverse reference `from` is auotmatically generated.

> `Whirligig` relocated `from` `Yukon Territory` as `Swings`

## Sort order

Relocations are always placed as the first or last point on a timeline, depending on the `direction`.


| Field         | Sort in timeline                     		    |
| ------------- | ------------------------------------- |
| `to`   | First         			        |
| `from`  	| Last  |
