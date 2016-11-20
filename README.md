node-photoflow - Personal Photo Workflow
========================================

**WIP**

Abstract
--------

Photo-Flow manages flows of personal media items (photos and videos) from
mutiple devices. Some devices are content producers (mobile devices but also
desktop/laptop with SD-Card readers. Some store content (home server, home desktop/laptop). Some organize & publish content (home desktop-/laptop), storing
draft content until they are copied to the hubs) and others being consumers
(storing 1-month - 1-year of published content).

Photoflow does not need an application installed on your mobile device(s) to
capture content drafts, but it used you usual Cloud Service Providers (Google,
iCloud... etc).

Usage
-----

XXX

References
----------

[![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

Terminology
-----------

Entity | Description
------ | -----------
Item-Producer | Creates items & makes them available to the Items-Organizer (as Draft)
Item-Consumer | Fetch published items from Items-Organizer
Items-Organizer | Edit & Publish items
Items-Hub | Stores every photos (both Draft & Published)
PhotoFlow Home Application (pfha) | Item-Consumer
PhotoFlow Home Application (pfhs) | Items-Organizer (\& possibly Item-Consumer)
PhotoFlow Mobile Application (pfma) | both an Item-Producer \& an Item-Consumer
