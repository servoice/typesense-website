# Typesense Documentation

👋 Welcome! If you want to dive right in, the <RouterLink :to="`${$site.themeConfig.typesenseLatestVersion}/guide/`"><strong>Guide</strong></RouterLink> is a good place to get started.

## How the docs are organized

The documentation is divided into the following sections, that you'll find links for on the **top navigation bar**.

| Section| Purpose |
| --- | --- |
| [**Overview**](./overview/what-is-typesense.md) |  This section gives you a birds-eye view of Typesense, why you'd want to use it and comparison with alternatives. |
| <RouterLink :to="`/guide/`"><strong>Guide</strong></RouterLink> | This section walks you step-by-step through how you can use Typesense in different scenarios. |
| <RouterLink :to="`${$site.themeConfig.typesenseLatestVersion}/api/`"><strong>API Reference</strong></RouterLink> | This section gives you detailed information about all the API endpoints and parameters in Typesense. |

:::tip
Use the version dropdown in the top navigation bar to switch between different versions of Typesense.
:::

## Help us improve the docs

This documentation site itself is [open source](https://github.com/typesense/typesense-website/tree/master/docs-site). If you notice an issue on any page, just click on the Edit button at the bottom of the page, make changes and submit it as a PR. 

We also welcome contributions to the documentation, especially to the Guide section. If you've integrated Typesense with a framework that's not covered, we'd love to have you share that with the world. 
Please reach out to us to collaborate on this.

:::tip
Use the "Edit page" link at the bottom of any page to edit it and submit a PR. We appreciate your contributions.
:::

## Typesense Versions

Typesense is versioned software and each version has documentation specifically tied to it. You can use the dropdown on the top navigation bar to switch between versions.

But here are direct clickable links as well:

<ul>
  <li v-for="version in $site.themeConfig.typesenseVersions">
    <RouterLink :to="`${version}/`"> {{version}} </RouterLink>
  </li>
</ul>
