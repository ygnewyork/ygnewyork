## Hi there 👋

I'm a Computer Science and Statistics & Data Science double major at UT Austin, graduating May 2028. I love to work on backend, pipeline, and data infrastructure — the systems that move large volumes of data and have to stay accurate while they do it.

This past summer I was an SDE intern on the Aurora database team at AWS, where I built an event-driven telemetry pipeline giving on-call engineers end-to-end visibility into migration health, latency, and errors across 60,000+ distributed database instances. Transition events were captured through EventBridge Pipes and streamed via Firehose into a partitioned S3/Athena store, processing 250,000+ data movements. I deployed it with TypeScript CDK on a multi-region pipeline with canary tests, health checks, and CloudWatch-triggered rollbacks across regional waves.

Before that I spent a semester at Longhorn Life Sciences designing the Firestore schema and role-based access control behind a pre-launch clinical wound-monitoring platform — security rules and per-patient storage scoping so clinicians only reach their own records. This fall I'm joining PwC as a software engineering intern.

**A few things I've built**

- **[Wampus Prices](https://wampus.duckdns.org/)** — a Flask and D3.js app on EC2 that maps West Campus housing for UT students, with price filtering, walking-distance overlays, and live data polled from the Austin Open Data Portal API.
- **[HerdUp](https://github.com/AnishK05/HerdUp/tree/main)** — an Expo iOS app for 55,000+ UT students, where I built a hybrid search combining vector embeddings with lexical scoring (+30% relevance) over a Supabase Postgres backend with row-level security.
- **[JobSense](https://github.com/texasluminescence/job-trend-analyzer/)** — a job-market analytics tool over 10,000+ STEM postings, where I built the ARIMA forecasting, the skill classification, and the Python/SQL validation that flagged pipeline anomalies at 92% accuracy.

I'm also a senior data designer at The Daily Texan, UT's student paper, where I scrape and clean datasets in R and Python and build the [graphics](https://ygnewyork.github.io/dataviz.html) that run with the stories, for an audience of 11,500.

More of my work — software, experiences, projects, and visualization — is on my [website](https://ygnewyork.github.io).
