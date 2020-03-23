# domain-driven-design

- Domain Driven Design Entity is not a DB entity.

# Event Storming

## Bounded Context

- Take a Book Store as an example:

| Store Context | WareHouse Context |
| --- | --- |
| Things that happens in the store does not impact the warehouse | Things that happens in the warehouse does not impact the warehouse |
| Store has its own set of entities(DDD entities are different from DB entity) to support the context| WareHouse has its own set of entities(DDD entities are different from DB entity) to support the context|

- Take a Book Store as an example:
  - Store Context
    - Things that happens in the store does not impact the warehouse
    - Store has its own set of entities
  - WareHouse Context
    - Things that happens in the warehouse does not impact the warehouse
    - WareHouse has its own set of entities

-   The software programs needs to be designed in such a way that change in one context does not overlap/impact each other. With this the changes in one does not impact the other.    
