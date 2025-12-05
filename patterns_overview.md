# Patterns Overview

This document lists all **23 classic Design Patterns** from the *Gang of Four (GoF)*.
Patterns are grouped by category and include:

* Link to implementation (with folder structure)
* Description
* Modern Alternatives

**Note:** Popularity shown below each pattern reflects its **2025 relevance rating** (0–3 stars).

# Creational Patterns

| Pattern                                                     | Description                                        | Modern Alternatives                  |
| ----------------------------------------------------------- | -------------------------------------------------- | ------------------------------------ |
| **[factory.py](creational/factory.py)**★★★                  | Creates objects without specifying concrete class. | Dependency Injection (DI) containers |
| **[abstract_factory.py](creational/abstract_factory.py)**★★ | Produces families of related objects.              | DI frameworks, feature flags         |
| **[builder.py](creational/builder.py)**★★★                  | Builds objects step-by-step.                       | Fluent interfaces, pydantic models   |
| **[prototype.py](creational/prototype.py)**★                | Clones objects for fast creation.                  | Serialization frameworks, caching    |
| **[singleton.py](creational/singleton.py)**                 | One instance shared globally.                      | DI containers, global state managers |

---

# Structural Patterns

| Pattern                                        | Description                                  | Modern Alternatives                       |
| ---------------------------------------------- | -------------------------------------------- | ----------------------------------------- |
| **[adapter.py](structural/adapter.py)**★★★     | Makes incompatible interfaces work together. | Wrapper classes, API gateways             |
| **[bridge.py](structural/bridge.py)**★         | Separates abstraction from implementation.   | Composition-first architectures           |
| **[composite.py](structural/composite.py)**★★  | Part-whole hierarchies.                      | Component trees (React/Vue-like)          |
| **[decorator.py](structural/decorator.py)**★★★ | Adds behavior dynamically.                   | Middleware frameworks, AOP                |
| **[facade.py](structural/facade.py)**★★        | Simplifies complex systems.                  | API gateway, SDK wrappers                 |
| **[flyweight.py](structural/flyweight.py)**★   | Shares intrinsic state to reduce memory.     | Memory pooling, batching strategies       |
| **[proxy.py](structural/proxy.py)**★★★         | Controls access and may add behavior.        | Reverse proxies, decorators, service mesh |

---

# Behavioral Patterns

| Pattern                                                                    | Description                                | Modern Alternatives                   |
| -------------------------------------------------------------------------- | ------------------------------------------ | ------------------------------------- |
| **[chain_of_responsibility.py](behavioral/chain_of_responsibility.py)**★★★ | Passes request through handlers.           | Middleware stacks                     |
| **[command.py](behavioral/command.py)**★★                                  | Encapsulates a request as an object.       | Event sourcing, CQRS                  |
| **[interpreter.py](behavioral/interpreter.py)**★                           | Grammar + interpreter for languages.       | ANTLR, LLM-assisted parsing           |
| **[iterator.py](behavioral/iterator.py)**★★                                | Sequential access to collections.          | Python generators, async iterators    |
| **[mediator.py](behavioral/mediator.py)**★★★                               | Central coordination of communication.     | Pub/sub, event buses                  |
| **[memento.py](behavioral/memento.py)**★★                                  | Saves and restores state.                  | Snapshots, versioning systems         |
| **[observer.py](behavioral/observer.py)**★★★                               | Reactive response to change.               | Reactive frameworks (signals, Rx)     |
| **[state.py](behavioral/state.py)**★★                                      | Behavior changes with internal state.      | FSM libraries, rule engines           |
| **[strategy.py](behavioral/strategy.py)**★★★                               | Interchangeable algorithms.                | Model registries, AI agent strategies |
| **[template_method.py](behavioral/template_method.py)**★★                  | Algorithm skeleton with overridable steps. | Hooks/callback systems                |
| **[visitor.py](behavioral/visitor.py)**★                                   | Add operations without modifying objects.  | Pattern matching, dataclass visitors  |

---
