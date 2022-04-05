# HubSpot Essentials for Developers: Getting Started with Memberships
This is an example project created for the [HubSpot Essentials for developers event](https://events.hubspot.com/events/details/hubspot-hubspot-academy-presents-hubspot-essentials-for-developers-getting-started-with-memberships/) - illustrating a simple logged-in experience that can be built on HubSpot websites.


The theme is using the boilerplate and the main files that you should look at are:
* [Menu.module](/memberships-webinar-project/src/modules/menu.module/) (HTML+HubL and Fields.json)
* [Associations - Companies.module](/memberships-webinar-project/src/modules/Associations%20-%20Companies.module/) (HTML+HubL)

We've provided for your convenience 
* [membership-preferences-update.html](/memberships-webinar-project/src/templates/membership-preferences-update.html) - You will need to create your own form and assign it when you create a page with this template.
* [membership-preferences.html](/memberships-webinar-project/src/templates/membership-preferences.html) - example of using personalization tokens in a rich text module and modules that leverage CRM associations.

We created these files to make it easy to recreate the setup we had during the event. You don't need to create a new template to create membership type pages.

The rest of the files are part of the standard [HubSpot boilerplate](https://developers.hubspot.com/docs/cms/building-blocks/themes/hubspot-cms-boilerplate).

*This repository is not a replacement for the boilerplate, it's meant to demonstrate what you can do, building off of the boilerplate.*

Creators: AJ Laporte and Jon McLaren.