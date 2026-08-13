# StackLibrary
[![Source on GitHub](https://img.shields.io/badge/Source-GitHub-6e40c9?style=for-the-badge&logo=github&logoColor=white)](https://github.com/blackingsplash/StackLibrary)

**StackLibrary** is a simple library that implements the use of the Stack data structure in Roblox, focusing mainly on optimization and readable code that is easily modified by the developer. Its functionality 
works well as it has thread safety, a frozen state (for .freeze), enforces a node limit and byte size limit on each node that can be customised, and more! This module is **still** just being published, so it may
have some weird edgecases, however, all the methods were tested and optimized.

## Features

-   **Linked list implementation**: Stack objects in StackLibrary are simulated through a linked list data structure.
-   **User custom configuration**: This feature allows users to customise how their stacks treat and operate nodes under the hood.
-   **Thread safety**: StackLibrary comes with thread safety, which limits only one thread to work on your stack at a time. With this approach, strange collisions are completely avoided and data flow is free.
---

## Setup

Currently, StackLibrary is only available on the Roblox marketplace. Further updates will be pushed out to make it wally available as well as make the documentation better.
Steps to download (link is [here](https://create.roblox.com/store/asset/81799640024168)):
```
    1. Download the Roblox package/model via the Marketplace
    2. Place the folder "StackLibrary" in ReplicatedStorage
    3. If you ever need to test, you can go ahead and look at the Tests folder, otherwise, it is free to delete.
```

# License

<p align="center">
StackLibrary is released under the <a href="LICENSE.md">MIT License</a>.
</p>
