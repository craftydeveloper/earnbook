# Architecture

The runnable interface is the existing index.html. README.md explains how to open or serve it. The added docs, examples, tests, and scripts describe and verify the current browser boundary.

The existing page is a browser prototype; inspect its source before relying on state after refresh.

Keep the page static unless a feature needs a separately designed service. Before adding one, document authentication, data ownership, failure behavior, and migration.