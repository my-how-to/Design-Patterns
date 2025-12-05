# Patterns Overview

This document lists all **23 classic Design Patterns** from the *Gang of Four (GoF)*.
Patterns are grouped by category and include:

* Description
* Link to implementation (with folder structure)
* **2025 Popularity Index (1–5 stars)** shown **below the pattern name**
* **Modern Alternatives**

**Note:** Popularity shown below each pattern reflects its **2025 relevance rating** (0–3 stars).

# Creational Patterns

| Pattern                                                                          | Description                                        | Modern Alternatives                  |
| -------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------ |
| **[factory.py](creational/factory/factory.py)**<br>★★★                           | Creates objects without specifying concrete class. | Dependency Injection (DI) containers |
| **[abstract_factory.py](creational/abstract_factory/abstract_factory.py)**<br>★★ | Produces families of related objects.              | DI frameworks, feature flags         |
| **[builder.py](creational/builder/builder.py)**<br>★★★                           | Builds objects step-by-step.                       | Fluent interfaces, pydantic models   |
| **[prototype.py](creational/prototype/prototype.py)**<br>★                       | Clones objects for fast creation.                  | Serialization frameworks, caching    |
| **[singleton.py](creational/singleton/singleton.py)**<br>                        | One instance shared globally.                      | DI containers, global state managers |

---

# Structural Patterns

| Pattern                                                      | Description                                  | Modern Alternatives                       |
| ------------------------------------------------------------ | -------------------------------------------- | ----------------------------------------- |
| **[adapter.py](structural/adapter/adapter.py)**<br>★★★       | Makes incompatible interfaces work together. | Wrapper classes, API gateways             |
| **[bridge.py](structural/bridge/bridge.py)**<br>★            | Separates abstraction from implementation.   | Composition-first architectures           |
| **[composite.py](structural/composite/composite.py)**<br>★★  | Part-whole hierarchies.                      | Component trees (React/Vue-like)          |
| **[decorator.py](structural/decorator/decorator.py)**<br>★★★ | Adds behavior dynamically.                   | Middleware frameworks, AOP                |
| **[facade.py](structural/facade/facade.py)**<br>★★           | Simplifies complex systems.                  | API gateway, SDK wrappers                 |
| **[flyweight.py](structural/flyweight/flyweight.py)**<br>★   | Shares intrinsic state to reduce memory.     | Memory pooling, batching strategies       |
| **[proxy.py](structural/proxy/proxy.py)**<br>★★★             | Controls access and may add behavior.        | Reverse proxies, decorators, service mesh |

---

# Behavioral Patterns

| Pattern                                                                                                | Description                                | Modern Alternatives                   |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------ | ------------------------------------- |
| **[chain_of_responsibility.py](behavioral/chain_of_responsibility/chain_of_responsibility.py)**<br>★★★ | Passes request through handlers.           | Middleware stacks                     |
| **[command.py](behavioral/command/command.py)**<br>★★                                                  | Encapsulates a request as an object.       | Event sourcing, CQRS                  |
| **[interpreter.py](behavioral/interpreter/interpreter.py)**<br>★                                       | Grammar + interpreter for languages.       | ANTLR, LLM-assisted parsing           |
| **[iterator.py](behavioral/iterator/iterator.py)**<br>★★                                               | Sequential access to collections.          | Python generators, async iterators    |
| **[mediator.py](behavioral/mediator/mediator.py)**<br>★★★                                              | Central coordination of communication.     | Pub/sub, event buses                  |
| **[memento.py](behavioral/memento/memento.py)**<br>★★                                                  | Saves and restores state.                  | Snapshots, versioning systems         |
| **[observer.py](behavioral/observer/observer.py)**<br>★★★                                              | Reactive response to change.               | Reactive frameworks (signals, Rx)     |
| **[state.py](behavioral/state/state.py)**<br>★★                                                        | Behavior changes with internal state.      | FSM libraries, rule engines           |
| **[strategy.py](behavioral/strategy/strategy.py)**<br>★★★                                              | Interchangeable algorithms.                | Model registries, AI agent strategies |
| **[template_method.py](behavioral/template_method/template_method.py)**<br>★★                          | Algorithm skeleton with overridable steps. | Hooks/callback systems                |
| **[visitor.py](behavioral/visitor/visitor.py)**<br>★                                                   | Add operations without modifying objects.  | Pattern matching, dataclass visitors  |

---
