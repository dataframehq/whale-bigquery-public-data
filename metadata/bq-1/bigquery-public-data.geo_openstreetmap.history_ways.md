# `geo_openstreetmap.history_ways`
`bq-1` | `bigquery-public-data`

## Column details
* [INTEGER]   `id`
  - Object unique ID.
* [INTEGER]   `version`
  - Version number for this object.
* [STRING]    `username`
  - Name of user who created this version of the object.
* [INTEGER]   `changeset`
  - Changeset number for this object.
* [BOOLEAN]   `visible`
  - Is this version of the object visible?
* [TIMESTAMP] `osm_timestamp`
  - Last-modified timestamp for this object.
* [GEOGRAPHY] `geometry`
  - GEOGRAPHY-encoded bounding box
* [RECORD]    `nodes`
* [INTEGER]   `nodes.id`
  - Nodes that are part of this way
* [RECORD]    `all_tags`
  - Unstructured key=value attributes for this object.
* [STRING]    `all_tags.key`
  - Attribute key.
* [STRING]    `all_tags.value`
  - Attribute value.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
