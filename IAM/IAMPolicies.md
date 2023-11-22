#### IAM Policies inheritance

![img.png](../images/iam/img2.png)

#### IAM Policies structure

Consists of
- Version: policy language version, always include “2012-10-
17”
- Id: an identifier for the policy (optional)
- Statement: one or more individual statements (required)


Statements consists of
- Sid: an identifier for the statement (optional)
- Effect: whether the statement allows or denies access
(Allow, Deny)
- Principal: account/user/role to which this policy applied to
- Action: list of actions this policy allows or denies
- Resource: list of resources to which the actions applied to
- Condition: conditions for when this policy is in effect
(optional)

![img.png](../images/iam/img3.png)
