# wormhole-url-shortner

A distributed URL shortener built with .NET, Cassandra, and Redis.

The goal is a horizontally scalable service that turns long URLs into short, shareable links, stores mappings in Cassandra, and uses Redis for hot-path lookups and rate limiting so redirects stay fast as traffic grows.

**Status:** in design
