# Antora Extension for Checking Links

This extension stops the Antora site generator from building the site after checking internal links (xrefs).
As a result, the output is a list of broken links rather than a documentation site.

This extension is published as an npm module: [@jcahills/antora-link-checker](https://www.npmjs.com/package/@jcahills/antora-link-checker).

## Example

`antora --fetch --to-dir test --log-level=error --log-failure-level=error --extension=@jcahills/antora-link-checker check-links-playbook.yml`

## Using the Extension

For details about how to use extensions in Antora, see the [Antora documentation](https://docs.antora.org/antora/latest/extend/register-extension/).
