# Contributing

Guide for teams contributing docs to the Supply Chain component section.

## Top section

* Beneath the title, start with an `In this section` paragraph such as:
  ```
  The section introduces...
  The topics in this section explain...
  ```
* Try to use a product name where practical

This helps with SEO.

## Naming

The base product is called `Tanzu Supply Chain`. It's especially important not to
shorten this to `Supply Chain` as it becomes too easily confused with the resource kind.

Resource Kinds should be referred to by their CamelCase name:

* SupplyChain
* Component
* WorkloadRun

## Words and replacements

| Misused | Prefer | why?                                                                                                                                                       |
|---------|--------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Steps   | Stage  | The term is `stages` in a supply chain, so use "stages" when referring to supply chains. Obviously tekton has steps, and that's a good time to use `steps` |
|         |        |                                                                                                                                                            |
|         |        |                                                                                                                                                            |

## Headings and verbs

Each H1 heading in a topic and TOC heading should, where practical start with a verb.
For example,
`Supply Chain Authoring` should be `Author a supply chain`
`How to create Workload` should be `Create a workload`

## Diagrams

* [Miro Board](https://miro.com/app/board/uXjVNvc1o0E=/)