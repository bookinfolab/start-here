# Start Here

---
## Bookinfo Application
The application displays information about a book, similar to a single catalog entry of an online book store. Displayed on the page is a description of the book, book details (ISBN, number of pages, and so on), and a few book reviews.

The Bookinfo application is broken into four separate microservices:

`productpage` -> The `productpage` microservice calls the `details` and `reviews`` microservices to populate the page.
`details` -> The `details` microservice contains book information.
`reviews` -> The `reviews`` microservice contains book reviews. It also calls the `ratings` microservice.
`ratings`. The `ratings` microservice contains book ranking information that accompanies a book review.

> This journey is based on [istio example app](https://istio.io/latest/docs/examples/bookinfo/).

---
## Tasks
- [Task-000 - Instructions](./Task-000.md)
- [Task-001 - Setup Cloud/Local Development Environment for `ratings`](./Task-001.md)
- [Task-002 - Create and Run API Tests for `ratings`](./Task-002.md)
- [Task-003 - Build and Push container image for `ratings`](./Task-003.md)
- [Task-004 - Setup Cloud/Local Development Environment for `mongodb`](./Task-004.md)
- [Task-005 - Build and Push container image for `mongodb`](./Task-005.md)
- [[WIP] Task-006 - Integrate `ratings` with `mongodb`]()
- [[WIP] Task-007 - Create Compose file that integrates `ratings` with `mongodb` ]()
- [[WIP] Task-008 - Migrate to `mySql` from `mongodb` and support both DB engines]()
- [[WIP] Task-009 - Build and Push container image for `mysql`]()
- [[WIP] Task-010 - Include `mysql` on compose to integrating with `ratings`]()
- [[WIP] Task-011 - Add a `Load Balancer` for `ratings`]()
