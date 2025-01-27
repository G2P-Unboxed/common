# Authorization

### Overview

1. The scope of these end points is to standardise issuance of access tokens using existing OAuth2/OIDC standards.\\
2. Helps standardise end point access across g2p complaint api stack using x-access-token that is compliant with JWT specs.\\
3. DPGs & COTS products may also provide similar authz api end points with G2P Connect documented scopes as part of each country specific implementation (if any).\\
4. Additional security like IP white listing, private networks, etc are outside the scope of G2P Connect standards. Each country shall decide required operational models.\\

#### References

1. API specification [link](https://g2p-connect.github.io/specs/release/html/auth\_core\_api\_v1.0.0.html)
2. Discussion [thread](https://github.com/G2P-Connect/.github/discussions)

### Interface List

| Interface ID | End Point            | Description                                            |
| ------------ | -------------------- | ------------------------------------------------------ |
| AUTHZ-TOKN   | /oauth2/client/token | Provide access token to registered senders & receivers |

### Integration Schematics
