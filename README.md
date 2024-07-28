# AE Club - Intro to AE Course

This is a template for Analytics Engineers Club!

## Contents

1. [GitHub Codespace](#github-codespace)

2. [Connecting dbt to GitHub Repo](#connecting-dbt-to-github-repo)

3. [dbt Deployment Architecture ](#dbt-deployment-architecture)

4. [dbt Semantic Layer](#dbt-semantic-layer)

## GitHub Codespace

The codespace that you're connecting to is a Linux virtual machine (VM) hosted by GitHub. Your codespace is actually just a computer that is managed by GitHub in a giant data center (i.e., "building full of computers"). It is a computer just like the one you're using to read this text, although it probably has a different operating system and isn't physically connected to a screen for viewing or a keyboard for typing.

## Connecting dbt to GitHub Repo

## dbt Deployment Architecture

### What is CI/CD?

CI/CD, which stands for **continuous integration** and **continuous delivery/deployment**, aims to streamline and accelerate the software or data model development lifecycle.

CI refers to the practice of automatically and frequently integrating code changes into a shared source code repository, e.g. merging feature branches with the main branch. 

CD is a two part process that refers to the integration, testing, and delivery of code changes. Continuous delivery stops short of automatic production deployment, while continuous deployment automatically releases the updates into the production environment:

![Alt text](https://www.redhat.com/rhdc/managed-files/styles/wysiwyg_full_width/private/ci-cd-flow-desktop.png?itok=NNRD1Zj0)

## dbt Semantic Layer

The dbt semantic layer is an abstraction (concept of hiding unnecessary details about an object from the user or client (app)) that sits on top of your data warehouse. From within this layer, you can centrally define and implement metric/business logic using dbt. 

This is why the word semantic (meaning and reference) is used, since the layer deals with the definitions and logic of our data and data models. It acts as the **centre** of the analytics stack from which everyone in the business gets the same answers, anywhere, anytime, i.e. **source of truth**.

### dbt and MetricFlow

In the dbt semantic layer you can define metrics alongside your dbt models, and access them from any integrated analytics tool.



### Semantic Models

Semantic models are used to capture and store data logic and metadata. They can contain many different object types, but typical ones are:

- Entities
- Dimensions
- Measures/Facts
















