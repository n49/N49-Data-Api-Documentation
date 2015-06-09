#N49-Data-Api-Documentation

##About

**Documentation for Integrating with The N49.ca Data-API**

The API allows trusted partners of N49.ca to publish, update, and delete listings in our network of local business directories. This includes adding photos, phone numbers, videos, updating business hours, address, etc.

### How do I get started?

Start by sending an email to [Ryan Marr](mailto:ryan@n49.com?Subject=Hey%20Let%20me%20at%20that%20sweet%20n49.ca%20API), head of product at n49. He will hook you up with an API key.

## Endpoints
There are two primary endpoints, a developement and production endpoint. The data on the development endpoint is wiped every night and replaced with the latest production data. Anything pushed to the development environment will be lost after 24 hours.

**PRODUCTION**   = data-api.n49.com

**DEVELOPEMENT** = data-api-staging.n49.ca

Please see the individual action articles for specific action endpoints and functionality.

##Actions

[**Search:**](https://github.com/n49ryan/N49-Data-Api-Documentation/wiki/Search)
Search is used to find existing business listings on N49.ca

[**Details:**](https://github.com/n49ryan/N49-Data-Api-Documentation/wiki/Details)
Details is used to provide information about a specific business listing on N49.ca

[**Add:**](https://github.com/n49ryan/N49-Data-Api-Documentation/wiki/ADD)
Add is used to add a new listing or to claim an exisitng business listing on N49.ca

[**Update:**](https://github.com/n49ryan/N49-Data-Api-Documentation/wiki/Update)
Update is used to update the information on an n49.ca business Listing that you have already added or already claimed.

[**Delete:**](https://github.com/n49ryan/N49-Data-Api-Documentation/wiki/Delete)
Delte is used to end your relationship with an n49.ca listing, Delte will not remove the listing from n49.ca but will remove any content that you've provided except for the basic business information.

[**Suppress:**](https://github.com/n49ryan/N49-Data-Api-Documentation/wiki/Suppress)
Suppress is used to merge two duplicate listings the Suppressed listing is pointed to a Canonical listing.

[**Reviews:**](https://github.com/n49ryan/N49-Data-Api-Documentation/wiki/Reviews)
Reviews is used to pull user reviews of businesses from n49.ca. Reviews can be filtered by property or date and are specific to a business listing. Reviews are not to be published on third party sites without explicit written permission from N49.ca. Any violation of this can result in API access being revoked.


#References

[**Fields:**](https://github.com/n49/N49-Data-Api-Documentation/blob/master/FIELDS/FieldsJSON.md)
This is the list of the main listing fields that are associated with a Business listing on the site displayed in JSON. This includes formatting for how images should be handled to differentiate between logos, storefronts, and gallery images.

[**Categories:**](https://github.com/n49ryan/N49-Data-Api-Documentation/blob/master/CATEGORIES/listingcategories.csv)
This is list of Categories that can be attached to a business listing. Every Business listing needs at least one category.


