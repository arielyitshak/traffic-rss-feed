# Public traffic RSS collector

Collects the official public CCISS traffic RSS, validates it, and stores the feed together with its retrieval time.

This repository contains no trip itinerary, hotel, reservations, passwords, or API keys. Source: https://www.cciss.it/rss

A scheduled GitHub Actions workflow attempts a refresh every ten minutes and can also be started manually. Scheduled runs can be delayed. Consumers must reject stale or invalid snapshots, preserve attribution to CCISS, and must not interpret missing reports as proof that roads are open.
