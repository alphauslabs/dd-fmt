## Introduction

A design document (**DD**) is our way of defining a software system. It is an informal document that the primary author (or authors) of a software system create(s) before starting the actual coding. It is a high level implementation strategy that emphasizes the design decisions, and the trade-offs considered when making those decisions.

## Format

A DD is an informal document and thus, doesn’t follow a strict guideline for its content. However, it must be written, by default, in narrative (descriptive) form using the English language.

For consistency though, try using the suggested format below:

```
start
```

### Title

Sample title

Author(s): Name1[, Name2, ...]
Created: yyyy-mm-dd

### Introduction

Background, overview, context, goals, non-goals, etc.

### Design

The main design contents. Start with higher level design then go into details. You may include details about system diagrams, APIs (if an API is exposed), storage, etc.

### Alternatives considered

This section lists alternative designs that would have reasonably achieved similar outcomes. The focus should be on the trade-offs that each respective design makes and how those trade-offs led to the decision to select the design that is the primary topic of the document.

### Trade-offs and concerns

Mention the trade-offs considered during the design. Include concerns regarding security, privacy, observability, etc. Also include how the design impacts these concerns and how they are being addressed.

```
end
```

## Length

A DD should be sufficiently detailed but short enough to actually be read by busy people. The sweet spot for a larger project might be around 10-20ish pages. If you get way beyond that, it might make sense to split up the problem into more manageable sub problems. It should also be noted that it is absolutely possible to write a 1-3 page DD, even a single-pager.
