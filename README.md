# firefox_block_habit
Extension to block a list of website, default redirection to Google.com

List hardcoded in `background-script.js`

Next step: use WebExtensions API Storage to store list of website


# Firefox Policies
Instead of the extension, use Firefox Policies.json:

in `firefox/distribution/policies.json`

```
{
        "policies": {
                "WebsiteFilter": {
                        "Block": ["*://*.pinterest.com/*","*://*.facebook.com/*","*://*.IHATETHESEGUYS.net/*"]
                }
        }
}

```
