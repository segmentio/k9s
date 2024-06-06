<img src="assets/k9s.png" alt="k9s">

## K9s - Kubernetes CLI To Manage Your Clusters In Style!

K9s provides a terminal UI to interact with your Kubernetes clusters.
The aim of this project is to make it easier to navigate, observe and manage
your applications in the wild. K9s continually watches Kubernetes
for changes and offers subsequent commands to interact with your observed resources.

---

## Note...

This fork of k9s will contain some segment specific features. Feel free to suggest new features and contribute.

Original repo - https://github.com/derailed/k9s

## Features added to this fork


---

## Documentation

Please refer to the [K9s documentation](https://k9scli.io) site for usage, customization and tips.

## Building From Source

 K9s is currently using GO v1.21.X or above.
 In order to build K9s from source you must:

 1. Clone the repo
 2. Build and run the executable

      ```shell
      make build && ./execs/k9s
      ```
 3. Put the newly build executable on our PATH

---

## Contributions Guideline

* File an issue first prior to submitting a PR!
* Ensure all exported items are properly commented
* If applicable, submit a test suite against your PR
