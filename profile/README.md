# Fluency Partner Projects

This repository is for **Fluency partners** who want to get more value from the Fluency platform through companion tools, utilities, and example integrations.

The projects here are built to serve two purposes:

1. **Working tools** you can use in real environments.
2. **Code examples** that show how to build your own integrations and automations on top of Fluency.

---

## Who This Repository Is For

This repository is intended for:

* Managed Security Service Providers (MSSPs)
* Value Added Resellers (VARs)
* Integration and automation engineers
* Fluency administrators who want to script or extend the platform

If you are building services on Fluency, this repository is meant to shorten the time from idea to working solution.

---

## Example Projects

Below are examples of the types of projects you will find here.

### `yaml-to-rule`

A utility that converts YAML definitions into Fluency rule or signature formats.
This helps partners:

* Define rules in a simple, portable YAML format
* Version control rule definitions cleanly
* Automate conversion into Fluency compatible configurations

### YAML Resource Utility

A helper tool for working with YAML-based configuration and resource definitions used with Fluency.
Typical use cases:

* Normalizing YAML resources across multiple tenants or environments
* Validating structure before loading into Fluency
* Automating bulk updates

### Halo Middleware

Middleware that connects Fluency with Halo (HaloITSM or related platforms), allowing:

* Event or issue data from Fluency to create or update tickets
* Status or field updates in Halo to reflect back into Fluency workflows
* Example patterns for integrating Fluency with third party ITSM systems

---

## How to Use This Repository

1. **Browse the project directories** to find a tool or example that matches your use case.
2. Read each project’s local `README.md` for:

   * Purpose and design notes
   * Setup and configuration steps
   * Usage examples
3. Use the projects as:

   * **Direct tools** in your own environments, or
   * **Reference implementations** when building your own internal tooling.

---

## Contributing and Extending

Partners are encouraged to:

* Fork this repository
* Extend existing tools for new use cases
* Propose improvements through pull requests

If you have a repeatable integration pattern that other partners might benefit from, this repository is the place to share it.

---

## Support and Questions

For questions about how to use these projects or how to adapt them to your environment, please contact your Fluency partner representative or use your standard Fluency support channel.

If you need deeper architectural guidance or want to collaborate on a new integration, reach out through your Fluency account team.
