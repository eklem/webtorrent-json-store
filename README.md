# webtorrent-json-store
Webtorrent backend for storing and updating JSON. Data storage for website and search engine. Offline first, no real server, just other clients seeding and leaching.

Since Webtorrent only serves a static set of files, I will use some sort of incremental backup scheme, creating new webtorrent-files for updates and do a full new webtorrent file every on a regular basis.

Suggestions for tech stack: [[AskJS] technology stack for PWA, ServiceWorker and offline first web app?](https://www.reddit.com/r/javascript/comments/v9v65d/askjs_technology_stack_for_pwa_serviceworker_and/)
