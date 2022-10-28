# Awesome Developer-First [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


A curated list of awesome developer-first products.  
I'm sure that you'd like [unzip.dev](https://unzip.dev?ref=github-adf) (developer trends newsletter I created).  
You can follow me on [Twitter](https://twitter.com/agammore) for more dev related content :) 

The definition of developer-first for this repo is:
* Developers are the target audience.
* "Headless", "API-first", "SaaS" are frequently used keywords.
* Usually, this means that the front page has some code examples.
* Products - tools/services that people pay for.

```diff
+ 👀 Watch this repo to get notifications about new products we find
```

## Contents
* [Analytics](#analytics)
* [Authentication & Identity](#authentication--identity)
* [CI/CD](#cicd)
* [CMS (headless)](#cms-headless)
* [Code Quality](#code-quality)
* [Computer Vision](#computer-vision)
* [Databases & Spreadsheets](#databases--spreadsheets)
* [Deployment Hosting](#deployment-hosting)
* [Discussions](#discussions)
* [Documentation](#documentation)
* [Environment & Secret Management](#environment--secret-management)
* [Feature Flags](#feature-flags)
* [GEO](#geo)
* [IDE](#ide)
* [Infrastructure as Code](#infrastructure-as-code)
* [Integrations](#integrations)
* [Localization](#localization)
* [Mail](#mail)
* [Media](#media)
* [Messaging](#messaging)
* [Misc](#misc)
* [Monitoring](#monitoring)
* [Natural Language Processing](#natural-language-processing)
* [Orchestration](#orchestration)
* [Payments](#payments)
* [Repo](#repo)
* [Reports Generation](#reports-generation)
* [Scraping](#scraping)
* [Search](#search)
* [Shipping](#shipping)
* [Testing](#testing)

    
---
## Analytics
*Track web/app visitors.*
* [Mixpanel](https://mixpanel.com/) - Product analytics and dashboards.
* [Baremetrics](https://baremetrics.com/) - Subscription analytics for Stripe.
* [Segment](https://segment.com/) - Collect user data and send it to your other tools.
* [Heap](https://heap.io/) - Product analytics API for web and mobile, captures all events. 
* [Pirsch](https://pirsch.io/) - Privacy-friendly web analytics with a backend integration and API.

## Authentication & Identity
*Products that handle authentication and user identity for you.*
* [Auth0](https://auth0.com/) - Authentication & authorization as a service.
* [AWS cognito](https://aws.amazon.com/cognito/) - AWS's authentication as a service.
* [Okta](https://developer.okta.com/) - Embeddable authentication with SSO.
* [LoginRadius](https://www.loginradius.com/) - Managed user authentication service with SSO.
* [Firebase Auth](https://firebase.google.com/products/auth) - Google Firebase's take on authentication.
* [Magic.link](https://magic.link) - Passwordless (email-based) log in as a service.
* [Oso](https://www.osohq.com/) - Authorization framework (RBAC).
* [Hanko](https://www.hanko.io/) - Passwordless (WebAuthn API) PSD2, eIDAS, and GDPR compliant.
* [SuperTokens](https://supertokens.io/) - Opensource and hosted email & Oauth authentication with prebuilt UI.
* [Permit.io](https://www.permit.io/) - Permissions and access-control as a service.
* [FusionAuth](https://fusionauth.io/) - Security-centric authentication as a Service, including self-hosting.
* [userfront](https://userfront.com/) - Simplistic user authentication with pre-built back-office dashboard.

## CI/CD
*Continious Integration/Delivery.*
* [CircleCI](https://circleci.com/) - YML to configure your builds, parallel jobs, jobs marketplace.
* [Gitlab](https://gitlab.com/) - Open source CI and hosted solution with Github-like abilities.
* [Gitpod](https://www.gitpod.io/) - Automated cloud dev environments. 

## CMS (headless)
*Backend only Content Management System, you decide on frontend and consume content via API.*
* [Contentful](http://contentful.com/) - CMS as an API.
* [ElegantCMS](https://www.elegantcms.io/) - Headless CMS builder.
* [Ghost](https://ghost.org/) - Blog platform, can be used as headless CMS (ex. [with Hexo](https://ghost.org/docs/api/v3/hexo/)).
* [Sanity](https://sanity.io/) - Headless CMS, treat content as data.

## Code Quality
*Check your code quality.*
* [sonarsource](https://www.sonarsource.com/) - Lint and code quality checks.
* [Codacy](https://www.codacy.com/) - Automatic code quality checks.

## Computer Vision
*Manipulate and detect visual data.*
* [clarifai](https://www.clarifai.com/) - Set of computer vision APIs.
* [CloudSight](https://cloudsight.ai/) - Digital media brand recognition.
* [Google Vision AI](https://cloud.google.com/vision) - Google's AI vision APIs.
* [roboflow](https://roboflow.com/) - Simplified computer vision model creation for developers.
* [Scanbot SDK](https://scanbot.io/) - Structured data extraction from images for applications.

## Databases & Spreadsheets
*Storing data and processing it.*
* [Airtable](https://airtable.com/) - Database and spreadsheet hybrid with an API.
* [Supabase](https://supabase.io/) - Hosted and open source managed postgres DB like firebase.
* [PlanetScale](https://planetscale.com/) - Hosted managed MySQL database, CI integration & auto scaling.

## Debugging 
*Tools that help in tracking bugs.*
* [Google Cloud's operations suite](https://cloud.google.com/products/operations) -  Set of debug primitives (capture, log injection, etc) for Google cloud.
* [Lightrun](https://www.lightrun.com) - Debug production servers using a plugin in the IDE (on-prem or SaaS) that supports Java, Node.js, and Python.
* [Rookout](https://www.rookout.com) - Debug production servers via a cloud-based debugger. Supporting Java, .Net, Node.js, Python, and Ruby.

## Deployment Hosting
*Products that help you deploy your app/website.*
* [Render](https://render.com/) - Deploy from git to a CDN with SSL.
* [Vercel](https://vercel.com/) - Deploy JAMStack (mainly Next.js) via CLI.
* [Netlify](https://www.netlify.com/) - Deploy JAMStack (mainly Gatsby) via CLI.
* [Heroku](https://www.heroku.com/) - Deploy via CLI to scalable servers.
* [Digital Ocean App Platform](https://www.digitalocean.com/products/app-platform/) - Deploy and don't care about infrastructure, works with all major frameworks.
* [Platform.sh](https://platform.sh/) - Continuously deploy full-stack apps.
* [Fly.io](https://fly.io/) - Deploy dockerized full stack apps via a location-aware service (latency reduction).
* [Railway](https://railway.app/) - Out of the box git to deployment with auto scaling, DBs, secrets and rollbacks.

## Discussions
*Comments and forums.*
* [Commento](https://commento.io/) - Privacy centric embeddable comment system.
* [MuutIo](https://muut.io/) - Tools to create a community-driven app.
* [Bazaarvoice](https://www.bazaarvoice.com/ratings-and-reviews/) - Ratings, reviews as a service.
* [Yotpo](https://www.yotpo.com/platform/reviews/) - Reviews ratings and Q&A as a service.

## Documentation
*Documentation solutions.*
* [readme](https://readme.com/) - Personalized and dynamic developer docs.
* [DeveloperHub](https://developerhub.io/) - Collaborative developer documentation platform.
* [swimm](https://swimm.io/) - Docs that are coupled with your code, auto-synced, works with your IDE.
* [Mintlify](https://www.mintlify.com/) - AI powered code documentation, IDE extension (open source).

## Environment & Secret Management
*Manage environment variables and secrets for multiple apps or projects.*
* [Vault](https://www.vaultproject.io/) - API driven secret key management.
* [Doppler](https://doppler.com/) - Environment variable management across projects, in one place.
* [1Password Secrets Automation](https://1password.com/secrets/) - Secrets management with integration to 1Password.
* [Envkey](https://www.envkey.com/) - Environment management with syncing mechanism for all apps.
* [Ubiq](https://www.ubiqsecurity.com/) - Encryption APIs wiht secret management

## Feature Flags
*Control production features with conditional flags in your code.*
* [LaunchDarkly](https://launchdarkly.com/) - Feature flags-as-a-service platform.
* [split](https://www.split.io/) - Feature flags platform with data analytics.
* [Flagsmith](https://flagsmith.com/) - Feature flags-as-a-service platform simplified.
* [GrowthBook](https://www.growthbook.io/) - Open-source feature flag and experimentation platform.

## GEO
*Location services.*
* [Radar](https://radar.io/) - Geofencing and geo APIs.
* [mapbox](https://www.mapbox.com/) - Maps and locations products for devs.
* [SmartyStreets](https://www.smartystreets.com/) - US Reverse Geocoding and Address Verification APIs.

## IDE
*Products that extend your IDE and help development.*
* [Codota](https://www.codota.com/) - AI code completions for your IDE.
    * [TabNine](https://www.tabnine.com/) - Deep learning completion (part of codota).
* [Kite](https://www.kite.com/) - AI assistant in your IDE (Python or JS).

## Infrastructure as Code
*Declare your infrastructure and reproducibly provision cloud infrastrucure from it.*
* [Terraform](https://www.hashicorp.com/products/terraform) - DSL, open-source and free (paid solution adds team management, policy-as-code...).
* [Pulumi](https://www.pulumi.com/) -  Developer-first IaC with Python, TypeScript, Go and more languages...

## Integrations
*Integration management systems or products that ease integration development*
* [Apideck](https://www.apideck.com) - Integration marketplace builder, one-API with 3rd parties for quick development.

## Localization
*Translating your product (also denoted i18n).*
* [Localazy](https://localazy.com/) - App translation built for developers.
* [Tolgee](https://tolgee.io) - Developer & translator friendly web-based localization platform.

## Mail
*Sending emails as a service.*
* [Mailgun](https://www.mailgun.com/) - Send, track, and receive emails.
* [Sendgrid](https://sendgrid.com/) - Email API.
* [Lob](https://www.lob.com/) - Email and address verification.
* [FormSpree](https://formspree.io/) - Receive form submissions by email.
* [Hunter.io](https://hunter.io/) - Email lead and validation APIs.
* [Anymail finder](https://anymailfinder.com) - Verify and find email APIs.

## Media
*Media APIs (optimization, CDN).*
* [Cloudinary](https://cloudinary.com/) - Optimize, create, manage, and deliver images and videos.
* [imgix](https://www.imgix.com/) - Transforms, optimizes, and cache images.
* [ImageKit](https://imagekit.io/) - Automate image optimization, transformation, and delivery.
* [Mux](https://mux.com/) - APIs to upload, manage, and stream video.
* [Pintura](https://pqina.nl/pintura) - A fully configurable JavaScript image editor SDK.
* [APITemplate.io](https://apitemplate.io/) - APIs to generate images and PDFs from reusable templates.

## Messaging
*Messaging APIs - SMS, notifications, chats, and VoIP.*
* [Twilio](https://www.twilio.com/) - SMS, push notifications, and VoIP APIs.
* [Vonage](https://www.vonage.com) - Video, SMS, chat, and voice APIs.
* [stream](https://getstream.io/) - Feed and chat as a service.
* [Applozic](https://www.applozic.com/) - Chat SDKs, real-time messaging.

## Misc
*Different products that probably don't have a category.*
* [Actyx](https://www.actyx.com/) - Developer-first factory building.
* [ngrok](https://ngrok.com/) - Generate public URLs for internal servers (behind NAT/firewall).
* [zigi](https://www.zigi.ai/) - Developer’s assistant for mundane non-coding tasks via Slack.
* [Nylas](https://www.nylas.com/) - APIs for productivity workflows (email, calendar, contacts...) - like plaid for productivity.
* [Interval](https://interval.com/) - SDK to build internal tools and scripts for your product.

## Monitoring
*Monitoring your production application.*
* [Sentry](https://sentry.io/) - Application monitoring for bugs and performance.
* [KeenIO](https://keen.io/) - Event streaming platform.
* [Rollbar](https://rollbar.com/) - Reports errors in production.
* [LogRocket](https://logrocket.com/) - Replay bugs users had.
* [Dashbird](https://dashbird.io/) - Serverless realtime monitoring.
* [Statuspal](https://statuspal.io) - Public/Private status pages for services with integrations.
* [instatus](https://instatus.com) - Minimalist Jamstack status page.

## Natural Language Processing
*Interactions with natural language.*
* [DialogFlow](https://cloud.google.com/dialogflow) - Voice/text chatbot framework by Google.

## Orchestration
*Orchestration tools for (micro) services.*
* [Camunda- Platform](https://camunda.com/) - Workflow engine that delivers scalable, on-demand process automation.
* [AWS Step Functions](https://aws.amazon.com/step-functions/) - visual workflow service to build distributed applications and automate processes


## Payments
*Handling payments, credit card processing, and invoices.*
* [Stripe Payments](https://stripe.com/payments) - Accept payments and move money globally with APIs.
* [Braintree](https://www.braintreepayments.com/) - Paypal's take on API-first payments.
* [Plaid](https://plaid.com/) - Accept, send ACH (bank transfers) and get bank information.
* [Paddle](https://paddle.com/) - Revenue delivery platform for SaaS with broad geographical support (unlike stripe at the moment).

## Repo
*Repository and artifacts management.*
* [Artifactory](https://jfrog.com/artifactory/) - Create your own package repository.
* [cloudsmith](https://cloudsmith.com/) - Cloud-native private package management.

## Reports Generation
*Generating reports, mainly PDFs*
* [PDFBlade](https://pdfblade.com/) - HTML to PDF API usage based pricing.
* [Carbone](https://carbone.io/) - JSON into PDF, DOCX, XLSX, PPTX, ODS... API.
* [Export SDK](https://exportsdk.com) - PDF generator API with visual template editor.
* [DocRaptor](https://docraptor.com) - HTML to PDF API built specifically for Paged Media using the [Prince](https://www.princexml.com/) PDF library.

## Scraping
*Fetching data from websites not via an intended API.*
* [Apify](https://apify.com/) - Turn websites to an API.
* [proxycrawl](https://proxycrawl.com/) - Scrape hard-to-scrape websites with proxies.
* [ScrapingBee](https://www.scrapingbee.com/) - Using headless browsers and proxies to scrape without being blocked.
* [ScrapingANT](https://scrapingant.com/) - Scrape with headless chrome.
* [SerpApi](https://serpapi.com/) - Real-time search engine scraping API.

## Search
*Index and search your content as a service API.*
* [Algolia](https://www.algolia.com/) - Search as a service and full suite of search APIs.
* [Swiftype](https://swiftype.com/) - Search as a service (crawlers and React ready).
* [Websolr](https://www.websolr.com/) - Open-source and hosted search with Solr.
* [typesense cloud](https://cloud.typesense.org/) - Open-source and hosted search as a Service.

## Shipping
*Creating and handling the shipment of goods.*
* [easypost](https://www.easypost.com/) - Shipping APIs for e-commerce. 

## Testing
*Testing tools.*
* [Testim](https://www.testim.io/) - Frontend testing.
* [Applitools](https://applitools.com/) - Automated visual testing.
* [Percy](https://percy.io/) - Continuous visual testing.
* [Blackfire.io](https://blackfire.io/) - Performance testing.
* [Chromatic](https://www.chromatic.com/) - Visual UI testing for storybook.
* [Beeceptor](https://beeceptor.com/) - REST API mocking.
* [Loadmill](https://www.loadmill.com/) - Generate tests from user behavior.

---

## Contributing

See here: [CONTRIBUTING.md](https://github.com/agamm/awesome-developer-first/blob/main/CONTRIBUTING.md)
