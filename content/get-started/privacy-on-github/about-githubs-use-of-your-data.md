---
title: About GitHub's use of your data
redirect_from:
  - /articles/about-github-s-use-of-your-data
  - /articles/about-githubs-use-of-your-data
  - /github/understanding-how-github-uses-and-protects-your-data/about-githubs-use-of-your-data
intro: '{% data variables.product.product_name %} uses your repository''s data to connect you to relevant tools, people, projects, and information.'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Policy
  - Legal
shortTitle: GitHub's use of your data
---

## About {% data variables.product.product_name %}'s use of your data

{% data variables.product.product_name %} aggregates metadata and parses content patterns for the purposes of delivering generalized insights within the product. It uses data from public repositories, and also uses metadata and aggregate data from private repositories when a repository's owner has chosen to share the data with {% data variables.product.product_name %} by enabling the dependency graph. If you enable the dependency graph for a private repository, then {% data variables.product.product_name %} will perform read-only analysis of that specific private repository.

If you enable data use for a private repository, we will continue to treat your private data, source code, or trade secrets as confidential and private consistent with our [Terms of Service](/free-pro-team@latest/site-policy/github-terms/github-terms-of-service). The information we learn only comes from aggregated data. For more information, see "[Managing data use settings for your private repository](/get-started/privacy-on-github/managing-data-use-settings-for-your-private-repository)."

{% data reusables.repositories.about-github-archive-program %} For more information, see "[About archiving content and data on {% data variables.product.prodname_dotcom %}](/repositories/archiving-a-github-repository/about-archiving-content-and-data-on-github#about-the-github-archive-program)."

{% data reusables.user-settings.export-data %} For more information, see "[Requesting an archive of your personal account's data](/get-started/privacy-on-github/requesting-an-archive-of-your-personal-accounts-data)."

We'll announce substantial new features that use metadata or aggregate data on the [{% data variables.product.prodname_dotcom %} blog](https://github.com/blog).

## How data improves security recommendations

As an example of how your data might be used, we can detect and alert you to a security vulnerability in your public repository's dependencies. For more information, see "[About {% data variables.product.prodname_dependabot_alerts %}](/code-security/dependabot/dependabot-alerts/about-dependabot-alerts)."

To detect potential security vulnerabilities, {% data variables.product.product_name %} scans the contents of your dependency manifest file to draw a list of your project's dependencies.

{% data variables.product.product_name %} also learns from changes you make to your dependency manifest. For example, if you upgrade a vulnerable dependency to a safe version after getting a security alert and others do the same, {% data variables.product.product_name %} learns how to patch the vulnerability and can recommend a similar patch to affected repos.

## Privacy and data sharing

Private repository data is scanned by machine and never read by {% data variables.product.product_name %} staff. Human eyes will never see the contents of your private repositories, except as described in our [Terms of Service](/free-pro-team@latest/site-policy/github-terms/github-terms-of-service#3-access).

Your individual personal or repository data will not be shared with third parties. We may share aggregate data learned from our analysis with our partners.
