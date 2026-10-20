# Serverless Functions Benchmark

A benchmark of cloud platforms running a small HTTP function. The study compares response times, completed-request throughput, and the time required to process a fixed request workload.

[Read the benchmark on AIMultiple](https://aimultiple.com/serverless-functions).

The test function inspects a visitor's browser and operating-system information. A shared load generator sends repeated requests using multiple worker threads. Measurements describe both the range of observed response times and aggregate execution behavior.

The article covers services including AWS Lambda, Azure Functions, Google Cloud Functions, Cloudflare Workers, Huawei FunctionGraph, Heroku, and Vercel. Coverage varies between the published charts, so each comparison should be read with its own provider list.

These measurements reflect the tested function, request pattern, deployment settings, and network conditions. They do not independently isolate cold-start latency from other sources of delay. The published methodology describes the workload and the meaning of each response-time and throughput metric.

The benchmark implementation was developed for AIMultiple and belongs to AIMultiple. This repository is a documentation summary. Source code and benchmark datasets are not distributed here.
