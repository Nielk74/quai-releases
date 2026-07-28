# Quai Watch privacy policy

Effective: 29 July 2026

Quai Watch is a standalone Wear OS transit app for the Paris region. This
policy explains the data used by the app.

## Location

Quai asks only for approximate foreground location, and only after the wearer
chooses to find nearby stations. When permission is already granted, Quai
refreshes the location when the app returns to the foreground so it does not
keep presenting a previous place.

The approximate coordinates are sent over HTTPS to the Quai API solely to
calculate nearby stations. The service processes the coordinates in memory
against its transit-topology snapshot and does not retain them after responding.
Its application logs exclude URL query parameters. Location is never used in
the background, for advertising, for analytics, or to build a profile.

Location permission is optional. The complete line catalog and search remain
available when permission is denied.

## Data stored on the watch

Quai caches nearby-station results and departure boards in the app's private
storage so useful transit information remains visible during a temporary
network failure. It does not store the location fix itself. Clear Quai's app
data or uninstall the app to remove this cache.

## Accounts, advertising, and tracking

Quai has no user accounts, advertising, analytics, tracking, or crash-reporting
SDK. It does not sell personal data or share location with independent third
parties. The hosting provider may process ordinary connection metadata, such as
an IP address, to deliver and protect the service.

## Contact and changes

Privacy questions can be submitted through the public
[Quai Watch support tracker](https://github.com/Nielk74/quai-releases/issues).
Material changes to this policy will be dated here and reflected in the app and
Google Play disclosures.
