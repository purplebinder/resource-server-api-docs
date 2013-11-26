# Resources

## Tags on Opportunities

### Attributes

[See Tag attributes here.](/docs/resources/organizations/tags.md)

### Endpoints

#### `GET /v1/organizations/:organization_id/opportunities/:opportunity_id/tags`

Returns a list of the tags on an opportunity.

#### `POST /v1/organizations/:organization_id/opportunities/:opportunity_id/tags`

Adds a tag to an opportunity. Anyone can add a tag.

#### `DELETE /v1/organizations/:organization_id/opportunities/:opportunity_id/tags/:id`

Deletes a tag from an opportunity. The `:id` in this case is the `name` attribute, but the parameter name is `id`

### Permissions

* Anyone can add a tag.
* Only the owner of the associated organization and admins can delete a tag.