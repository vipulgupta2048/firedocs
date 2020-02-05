# Auth Type Selection

## Overview

Authentication is stating that you are who are you are and Authorization is asking if you have access to a certain resource. When working with REST APIs or building your own API, one must remember to consider security right from the start. Testing and debugging APIs helps in making sure that the HTTP methods passed correctly, the token/API keys are valid and has access to the associated resources. With Firecamp's dedicated `Auths` tab in the request panel, you can configure and easily test popular authentication types on your own API or 3rd Party API's.

> For example, if you have a RESTful API for an online store, it's not okay to allow anonymous users to DELETE products from the catalog entries, but it's fine for them to GET a product catalog entry. On the other hand, for the store owner, both of these are valid uses.

That's one scenario where authentication plays a major role and something you can easily replicate, test and troubleshoot in the Firecamp API app. Authentication types available in Firecamp in the `Quick auth type selection` are as follows:

- OAuth 2
- Digest
- Bearer
- Basic
- AWS
- OAuth 1
- No Auth
- NTLM (Under Development)

You can choose whichever authentication type you need by navigating to the `Auths` tab in the request panel and selecting from either the `Quick auth type selection` or the dropdown list.
