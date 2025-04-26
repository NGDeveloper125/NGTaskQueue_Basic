# NGTask_Queue_Basic

`ngtask_queue_basic` is a concrete implementation of the NGTQ trait.
 This crate provides a basic, in-memory task queue system that adheres to the NGTQ interface.

## Overview

This crate serves as:

1. A functional, basic implementation of the NGTQ trait
2. An example of how to implement the NGTQ trait for custom task queue systems
3. A ready-to-use task queue for simple applications or prototyping

## Relationship to NGTQ

`ngtask_queue_basic` depends on and implements the `NGTQ` trait from the `ngtq` crate. It provides concrete implementations for all methods defined in the NGTQ trait.

## Usage

To use this implementation in your project, add both `ngtq` and `ngtask_queue_basic` to your `Cargo.toml`:

```toml
[dependencies]
ngtq = "0.1.0"
ngtask_queue_basic = "0.1.0"
```
### For More Information Please visit NGTQ docs at:
1. NGTQ github-pages: coming soon 
2. github repo: https://github.com/NGDeveloper125/NGTQ
3. ngtq docs: file:///home/ngdeveloper/NGTQ/ngtq/target/doc/ngtq/index.html
