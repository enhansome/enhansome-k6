<div align="center">
  <a href="https://k6.io/">
    <img src="assets/bert.png" alt="k6 mascot" width="300px">
  </a>

<!--lint disable awesome-heading-->

# Awesome k6 with stars

<!--lint enable awesome-heading-->

A collection of resources by the community, on (testing with) <a href="https://k6.io/">k6</a>.

<!-- lint disable double-link -->

Contributions are welcome! Read the [contribution guidelines](contributing.md) first.

<!-- lint enable double-link -->

</div>

## Contents

* [Articles](#articles)
* [Videos](#videos)
* [Examples/Templates](#examplestemplates)
* [Tools](#tools)
* [CI/CD](#cicd)
* [Extensions](#extensions)
* [Related](#related)

## Articles

* [k6 Learn](https://github.com/grafana/k6-learn) ⚠️ Archived - Explanation of the principles of load testing and practical examples for how to do it with k6.

* [CloudPosse's Load Testing Stack](https://github.com/cloudposse/load-testing) ⚠️ Archived - Load testing stack using k6, Grafana and InfluxDB.

* [k6 OSS workshop](https://github.com/grafana/k6-oss-workshop) ⚠️ Archived - A 2-3 hour k6 workshop with practical k6 examples using the QuickPizza demo app.

* [Beginner's guide to load testing with k6](https://link.medium.com/npI9sjDyyjb) - Introductory guide in several parts, helping you get started with k6.

* [Best practices organizing performance testing projects with k6](https://grafana.com/blog/2024/04/30/organizing-your-grafana-k6-performance-testing-suite-best-practices-to-get-started/) - Guidelines to scale your performance testing across multiple teams and projects.
  * [Part 2 - JavaScript tools, shared libraries, and TypeScript](https://grafana.com/blog/2024/05/02/setting-up-your-grafana-k6-performance-testing-suite-javascript-tools-shared-libraries-and-more/) - Stting up your k6 performance testing suite with JavaScript tools, shared libraries, and TypeScript.

* [Distributed load testing with k6](https://feryn.eu/presentations/distributed-load-testing-k6-confoo23) - Thijs Feryn presents in ConFoo Montreal 2023.

* [Load Testing with k6](https://medium.com/@dan.ryan.emmons/qa-load-testing-with-k6-io-c11c2afced04) - Brief overview of features and capabilities of k6.

* [Test and visualize with InfluxDB, Grafana and K6](https://medium.com/@naoko.reeves/load-test-with-k6-and-visualize-with-influxdb-and-grafana-c6097a6f6d0a) - Setting up load tests and visualizing them using grafana dashboards.

* [Open source load testing tool review 2020](https://grafana.com/blog/2020/03/03/open-source-load-testing-tool-review/) - Detailed comparison of the most popular open source load testing tools.

* [Load Testing Your API with Swagger/OpenAPI and k6](https://k6.io/blog/load-testing-your-api-with-swagger-openapi-and-k6) - Generate k6 load test scripts from OpenAPI specifications.

* [Load Testing Your API with Postman](https://grafana.com/blog/2020/04/19/load-testing-your-api-with-postman/) - How to use Postman collections to load test your API.

* [Load Testing & Black Friday capacity planning](https://medium.com/back-market-engineering/how-back-market-sres-prepared-for-black-friday-5f017f343408) - How Back Market prepared for Black Friday with k6 based load testing.

* [Load Testing SQL Databases with k6](https://grafana.com/blog/2021/07/14/load-testing-sql-databases/) - How to use the xk6-sql extension to test SQL databases directly.

* [Introducing TestRail in your K6 tests](https://dev.to/kwidera/introducing-testrail-in-you-k6-tests-eck) - Reporting k6 output to TestRail.

* [Beautiful Load Testing With K6 and Docker Compose](https://medium.com/swlh/beautiful-load-testing-with-k6-and-docker-compose-4454edb3a2e3) - How to run load tests using the awesome combination of Docker Compose, K6, InfluxDB and Grafana.

* [Load Testing with Azure DevOps and k6](https://medium.com/microsoftazure/load-testing-with-azure-devops-and-k6-839be039b68a) - How to setup Azure DevOps to perform automated load tests using k6, handleCallback, and JUnit.

* [K6 — Custom Slack Integration: Metrics are the Magic of Tests](https://medium.com/geekculture/k6-custom-slack-integration-metrics-are-the-magic-of-tests-527aaf613595) -  How to send k6 output results to Slack using the handleSummary callback.

* [Load testing with k6](https://levelup.gitconnected.com/load-testing-with-k6-48488c7946bb) - Using k6 for load, soak, stress, spike and smoke testing.

* [How to write three times fewer lines of code when doing load testing](https://dev.to/tarantool/how-to-write-three-times-fewer-lines-of-code-when-doing-load-testing-9lb) - Building a k6 extension in Go to test Tarantool.

* [Load Testing. k6 + TypeScript + Azure DevOps](https://alex-klaus.com/load-test-k6-typescript-azure/)

* [Performance testing with k6](https://blog.shanelee.name/2021/12/15/performance-testing-with-k6/) - On API performance testing, with Open API and TypeScript.

* [k6 introduces browser automation and Prometheus support in k6 OSS](https://grafana.com/blog/2021/11/24/k6-introduces-browser-automation-and-prometheus-support-in-k6-oss/) - From the Grafana blog: feature announcements at ObservabilityCON 2021.

* [Testing shift left observability with the Grafana Stack, OpenTelemetry, and k6](https://grafana.com/blog/2021/12/06/testing-shift-left-observability-with-the-grafana-stack-opentelemetry-and-k6/) - From the Grafana blog: a summary of Executive Director of Platform Engineering at JPMorgan Chase, Vinodh Ravi's talk at ObservabilityCON 2021.

* [Umbraco 9 - What a Performance!](https://moriyama.co.uk/about-us/news/blog-umbraco-9-what-a-performance/) - Test the performance of Umbraco v9 on Azure against Umbraco v8 and comparing Windows vs Linux.

* [On maintaining a k6 codebase, Part 1](https://filfreire.com/posts/k6_tricks_ep1) - Personal tips to maintain a challenging k6 load testing codebase.

* [Load testing with k6 and k8s](https://www.toucantoco.com/en/tech-blog/tech-blog/load-testing-with-k6-and-k8s) - The Toucan DevOps team explains why they chose k6 as their load testing tool and how they deploy it on k8s.

* [Real-time stress:
  AnyCable, k6, WebSockets, and Yabeda](https://evilmartians.com/chronicles/real-time-stress-anycable-k6-websockets-and-yabeda) - Evil Martians adding "real-time stress" with k6 and WebSockets.

* [Streamlining Performance Testing with K6 and ChatGPT](https://medium.com/@monish.correia/streamlining-performance-testing-with-k6-and-chatgpt-206c6c7db82b) - Monish Correia writes k6 tests using GitHub co-pilot.

## Videos

* [k6 YouTube Channel](https://www.youtube.com/c/k6test)
* [How to use k6 Cloud for load testing](https://www.youtube.com/watch?v=ncxCIuo5tUU\&list=PLJdv3RhAQXNGkRCp7Q0k77n5jif4qjz2o) - A series of quick videos for getting started with k6 Cloud.
* [Intro to load testing with k6 and Grafana (k6 data source plugin and Prometheus Remote Write)](https://www.youtube.com/watch?v=tFsIgbqXbxM)
* [From Grafana ObservabilityCON: Intro to using k6 load testing with the Grafana observability stack](https://grafana.com/go/observabilitycon/2021/k6-load-testing/)
* [From Grafana ObservabilityCON: Building performance tests into your CI pipeline with k6 and Grafana, w/ Matthew Churcher, QA Engineer at Vonage](https://grafana.com/go/observabilitycon/2021/performance-testing-vonage/)
* [EveryoneCanContribute cafe: Load Performance Testing with k6](https://youtu.be/_ty40gSaaw8)
* [Playlist - What others says about k6](https://www.youtube.com/playlist?list=PLJdv3RhAQXNExTjuYN9ukawFHB7ucuejp)
  * [What is K6 & How to get started with k6](https://www.youtube.com/watch?v=ZAq87eZ1w2U) - Tutorial using k6 Extensions for Observability by "Is it Observable?"
  * [Website Performance + Load Testing with K6 (k6.io) in 5 MINUTES!](https://www.youtube.com/watch?v=brasMBAezJY) - Introductory overview of k6, showing how to create a test from a HAR file, by the DevOps Directive.
  * [Performance Testing your web app with k6](https://www.youtube.com/watch?v=Hu1K2ZGJ_K4) - A walkthrough of the open-source load and performance regression testing tool, k6, and how to load test your APIs and websites, by Chris James.
  * [Application Load Testing with k6](https://www.youtube.com/watch?v=iQmItkazLOk) - Daniel Knittl-Frank @TechTalk Days 2021, Intro to k6.
  * [Performance Testing From Zero to Hero with K6 & Azure](https://youtu.be/71N4_2Fv3I4?si=4eoRcvQfXNJR4aaa) - Jose Luis Latorre Millas at NDC Oslo 2021.
  * [AI-Powered K6 Testing: No Code, No Hassle, Just ChatGPT! 🦾🚀](https://www.youtube.com/watch?v=RYyPduBqGM4) - In this video, Karthik K.K. demonstrates how ChatGPT can create k6 tests without writing a single line of code.

## Examples/Templates

* [k6-typescript-template](https://github.com/grafana/k6-template-typescript) ⚠️ Archived - Starter template using Webpack bundler to write k6 tests in TypeScript.
* [luketn/docker-k6-grafana-influxdb](https://github.com/luketn/docker-k6-grafana-influxdb) ⭐ 179 | 🐛 3 | 🌐 JavaScript | 📅 2025-04-02 - Demonstrates how to run load tests with containerised instances of K6, Grafana and InfluxDB.
* [k6 QuickPizza examples](https://github.com/grafana/quickpizza) ⭐ 163 | 🐛 33 | 🌐 Go | 📅 2026-08-15 - Web application used for demos and workshops with multiple k6 examples.
* [k6-template-es6](https://github.com/grafana/k6-template-es6) ⚠️ Archived - Starter template using Webpack and Babel to enable ES6 features in k6 tests.
* [SwissLife-OSS/k6-multiscenario-template](https://github.com/SwissLife-OSS/K6-MultiScenario-template) ⭐ 56 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-06 - Use K6 to implement a Multi Scenario template.
* [tom-miseur/k6-templates](https://github.com/tom-miseur/k6-templates/) ⭐ 37 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-29 - Opinionated starter templates for k6 projects.
* [lreimer/continuous-k6k8s](https://github.com/lreimer/continuous-k6k8s) ⭐ 18 | 🐛 0 | 🌐 TypeScript | 📅 2021-05-11 - Continuously run k6 tests in Kubernetes using cronjobs.
* [k6-rollup-example](https://github.com/grafana/k6-rollup-example) ⚠️ Archived - Example using Rollup to bundle k6 tests.
* [Jahmilli/k6-example](https://github.com/Jahmilli/k6-example) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2023-11-27 - Starter template using Vite (Rollup) bundler to write k6 tests in TypeScript.
* [mohsenny/k6-test-template](https://github.com/mohsenny/k6-test-template) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2023-12-25 - Load testing framework.
* [Im5tu/template-k6](https://github.com/Im5tu/template-k6) ⚠️ Archived - A K6 Performance Test Suite Template.
* [kwidera/k6\_framework](https://github.com/kwidera/k6_framework) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2024-05-22 - Another k6 framework example.
* [Sahanipe/pet\_store](https://github.com/Sahanipe/pet_store) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-10 - Modularized scripts for the Swagger PetStore APIs.
* [k6 examples](https://grafana.com/docs/k6/latest/examples/) - A list of common examples on the k6 documentation.
* [agilob/multiscenario-tests](https://b.agilob.net/programming/k6/multiscenario-tests/) - Running multiple scenarios at once.

## Tools

* [k6 generator](https://github.com/OpenAPITools/openapi-generator) ⭐ 26,673 | 🐛 5,707 | 🌐 Java | 📅 2026-08-15 - Tool for converting Swagger/OpenAPI specifications to k6 test scripts.
* [k6-reporter](https://github.com/benc-uk/k6-reporter) ⭐ 550 | 🐛 5 | 🌐 EJS | 📅 2026-03-01 - Tool for converting k6 output to HTML reports.
* [postman-to-k6](https://github.com/grafana/postman-to-k6) ⚠️ Archived - Tool for converting Postman collections to k6 test scripts.
* [har-to-k6](https://github.com/grafana/har-to-k6) ⭐ 163 | 🐛 21 | 🌐 JavaScript | 📅 2026-08-13 - Tool for converting HAR recordings to k6 test scripts.
* [jmeter-to-k6](https://github.com/grafana/jmeter-to-k6) ⚠️ Archived - Tool for converting JMeter test cases to k6 test scripts.
* [k6-html-reporter](https://github.com/szboynono/k6-html-reporter) ⭐ 25 | 🐛 2 | 🌐 HTML | 📅 2021-09-19 - Tool for generating k6 HTML reports.
* [k6-to-junit](https://github.com/Mattihew/k6-to-junit) ⭐ 20 | 🐛 9 | 🌐 TypeScript | 📅 2023-10-19 - Tool for converting k6 output to JUnit XML for easy use with CIs.
* [k6-junit](https://github.com/simbadltd/k6-junit) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2023-04-02 - k6 JUnit summary exporter libray.
* [k6-expect](https://github.com/simbadltd/k6-expect) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2023-04-06 - k6 library that simplifies writing tests in a functional way by providing a jest-like syntax for expectations.
* [jslib.k6.io](https://jslib.k6.io/) - Useful utility libs for k6 scripts.
* [k6 for visual studio code](https://marketplace.visualstudio.com/items?itemName=k6.k6\&ssr=false#overview) - Marketplace Extension for running k6 directly from your IDE.
* [k6 for IntelliJ](https://plugins.jetbrains.com/plugin/16141-k6) - IntelliJ-based Plugin to run and debug \[sic!] k6 tests locally or in the [k6 Cloud](https://app.k6.io/) from your IntelliJ IDE.
* [k6 Testkube executor](https://kubeshop.github.io/testkube/executor-k6/)

## CI/CD

* [k6 for Azure Pipelines](https://k6.io/blog/integrating-load-testing-with-azure-pipelines/)
* [k6 for Bamboo](https://k6.io/blog/integrating-k6-with-bamboo/)
* [k6 for Buddy](https://k6.io/blog/integrating-k6-with-buddy-devops/)
* [k6 for CircleCI](https://grafana.com/blog/2022/03/06/load-testing-with-circleci/)
* [k6 for Flagger](https://grafana.com/blog/2022/04/28/deployment-time-testing-with-grafana-k6-and-flagger/)
* [k6 for GitHub Actions](https://k6.io/blog/load-testing-using-github-actions/)
* [k6 for GitLab](https://grafana.com/blog/2020/09/27/load-testing-with-gitlab/)
* [k6 for Google Cloud Build](https://k6.io/blog/integrating-k6-with-google-cloud-build/)
* [k6 for Jenkins](https://k6.io/blog/integrating-load-testing-with-jenkins/)
* [k6 for Keptn](https://k6.io/blog/performance-testing-in-keptn-using-k6/)
* [k6 for TeamCity](https://k6.io/blog/load-testing-using-teamcity-and-k6/)

## Extensions

* [k6 Extensions](https://grafana.com/docs/k6/latest/extensions/)
* [GitHub Topic: xk6](https://github.com/topics/xk6) - Explore k6 extensions tagged with the xk6 label.
* [Extension Registry](https://grafana.com/docs/k6/latest/extensions/explanations/extensions-registry/) - Curated listing of k6 extensions.

### Official

* [xk6-sql](https://github.com/grafana/xk6-sql) ⭐ 190 | 🐛 22 | 🌐 Go | 📅 2026-08-14 - Load-test SQL Servers (PostgreSQL, MySQL and SQLite3 for now).
* [xk6-disruptor](https://github.com/grafana/xk6-disruptor) ⚠️ Archived - Inject faults to test 💣.
* [xk6-kubernetes](https://github.com/grafana/xk6-kubernetes) ⭐ 83 | 🐛 15 | 🌐 Go | 📅 2026-08-14 - Interact with Kubernetes clusters.
* [xk6-output-influxdb](https://github.com/grafana/xk6-output-influxdb) ⭐ 83 | 🐛 10 | 🌐 Go | 📅 2026-08-14 - Export results to InfluxDB v2.
* [xk6-client-tracing](https://github.com/grafana/xk6-client-tracing) ⭐ 60 | 🐛 23 | 🌐 Go | 📅 2026-08-14 - Client for load testing distributed tracing backends.
* [xk6-loki](https://github.com/grafana/xk6-loki) ⭐ 55 | 🐛 19 | 🌐 Go | 📅 2026-08-13 - Client for load testing Loki.
* [xk6-output-timescaledb](https://github.com/grafana/xk6-output-timescaledb) ⚠️ Archived - Export k6 results to TimescaleDB.
* [xk6-client-prometheus-remote](https://github.com/grafana/xk6-client-prometheus-remote) ⭐ 32 | 🐛 7 | 🌐 Go | 📅 2026-08-14 - Test Prometheus Remote Write performance.
* [xk6-exec](https://github.com/grafana/xk6-exec) ⚠️ Archived - Run external commands.
* [xk6-output-kafka](https://github.com/grafana/xk6-output-kafka) ⚠️ Archived - Export k6 results in real-time to Kafka.
* [xk6-notification](https://github.com/grafana/xk6-notification) ⚠️ Archived - Create notifications.
* [xk6-ssh](https://github.com/grafana/xk6-ssh) ⭐ 13 | 🐛 2 | 🌐 Go | 📅 2026-08-14 - SSH.

### Community

* [xk6-kafka](https://github.com/mostafa/xk6-kafka) ⭐ 216 | 🐛 9 | 🌐 Go | 📅 2026-07-18 - Load-test Apache Kafka. Includes support for Avro messages.
* [xk6-faker](https://github.com/szkiba/xk6-faker) ⭐ 118 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-14 - Generate random fake data.
* [xk6-mqtt](https://github.com/pmalhaire/xk6-mqtt) ⭐ 58 | 🐛 4 | 🌐 Go | 📅 2025-10-15 - MQTT extension.
* [xk6-playwright](https://github.com/nicholasvuono/xk6-playwright) ⚠️ Archived - Browser automation and end-to-end web testing using Playwright.
* [xk6-prometheus](https://github.com/szkiba/xk6-prometheus) ⭐ 54 | 🐛 8 | 🌐 Go | 📅 2026-03-01 - Prometheus HTTP exporter for k6.
* [xk6-sse](https://github.com/phymbert/xk6-sse) ⭐ 51 | 🐛 14 | 🌐 Go | 📅 2026-04-24 - A k6 extension for Server-Sent Events (SSE).
* [xk6-g0](https://github.com/szkiba/xk6-g0) ⭐ 47 | 🐛 8 | 🌐 Go | 📅 2026-03-01 - Write k6 tests in golang.
* [xk6-file](https://github.com/avitalique/xk6-file) ⭐ 35 | 🐛 0 | 🌐 Go | 📅 2026-08-03 - Write files.
* [xk6-output-statsd](https://github.com/LeonAdato/xk6-output-statsd) ⭐ 35 | 🐛 9 | 🌐 Go | 📅 2026-08-13 - Enables real-time output of test metrics to a StatsD service.
* [xk6-opentelemetry](https://github.com/thmshmm/xk6-opentelemetry) ⭐ 34 | 🐛 0 | 🌐 Go | 📅 2024-06-26 - Generate OpenTelemetry signals from within your test scripts.
* [xk6-dotenv](https://github.com/szkiba/xk6-dotenv) ⭐ 33 | 🐛 4 | 🌐 Go | 📅 2026-03-02 - Load env vars from a .env file.
* [xk6-cable](https://github.com/anycable/xk6-cable) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2024-06-24 - Test Action Cable and AnyCable functionality.
* [xk6-top](https://github.com/szkiba/xk6-top) ⭐ 31 | 🐛 10 | 🌐 Go | 📅 2026-03-09 - Updating the current k6 metrics summaries on the terminal during the test run.
* [xk6-kv](https://github.com/oleiade/xk6-kv) ⭐ 26 | 🐛 1 | 🌐 Go | 📅 2026-07-27 - Share key-value data between VUs.
* [xk6-output-elasticsearch](https://github.com/elastic/xk6-output-elasticsearch) ⭐ 25 | 🐛 18 | 🌐 Go | 📅 2026-08-04 - Export results to Elasticsearch 8.x.
* [xk6-tcp](https://github.com/NAlexandrov/xk6-tcp) ⭐ 20 | 🐛 1 | 🌐 Go | 📅 2025-11-27 - Send data to TCP port.
* [xk6-coap](https://github.com/golioth/xk6-coap) ⭐ 17 | 🐛 6 | 🌐 Go | 📅 2024-06-10 - Interact with Constrained Application Protocol endpoints.
* [xk6-prompt](https://github.com/Juandavi1/xk6-prompt) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2024-06-10 - Support for input arguments via UI.
* [xk6-output-prometheus-pushgateway](https://github.com/martymarron/xk6-output-prometheus-pushgateway) ⭐ 16 | 🐛 5 | 🌐 Go | 📅 2024-07-29 - Export results to Prometheus pushgateway.
* [xk6-output-timestream](https://github.com/leonyork/xk6-output-timestream) ⭐ 16 | 🐛 5 | 🌐 Go | 📅 2026-08-15 - Export results to AWS Timestream.
* [xk6-nats](https://github.com/ydarias/xk6-nats) ⭐ 15 | 🐛 5 | 🌐 Go | 📅 2024-06-10 - Provides NATS support for k6 tests.
* [xk6-mock](https://github.com/szkiba/xk6-mock) ⚠️ Archived - Mock HTTP(S) servers.
* [xk6-ethereum](https://github.com/distribworks/xk6-ethereum) ⭐ 13 | 🐛 4 | 🌐 Go | 📅 2024-09-29 - K6 extension for ethereum protocols.

## Related

* [awesome-http-benchmark](https://github.com/denji/awesome-http-benchmark) ⭐ 3,763 | 🐛 22 | 📅 2026-05-05 - A collection of HTTP benchmark tools, testing/debugging, & restAPI (RESTful).
* [Load Testing Toolkit](https://github.com/aliesbelik/load-testing-toolkit) ⭐ 251 | 🐛 1 | 📅 2026-07-01 - A collection of open-source tools for debugging, benchmarking, load and stress testing your code or services.
* [How They Load Test](https://github.com/aliesbelik/how-they-load) ⭐ 167 | 🐛 1 | 📅 2026-08-11 - A collection of resources on how companies around the world perform load testing.

## Contributing

<!-- lint disable double-link -->

Want to help in making this list better? Yay, that's awesome! Before you get started though, please have a look at our [code of conduct](code_of_conduct.md) and [contribution guidelines](contributing.md).

<!-- lint enable double-link -->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
