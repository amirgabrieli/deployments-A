# Product/Component centric structure  

This deployments repo structure is component centirc. The path guideline for the deployment tool/manifest is  **path::[Component]/[Platform]/[Method]**

Pros -
1. Supports both Aqua Enterprise and Aqua Cloud 
2. Lean repository - there are no duplicated directories 
3. Intuitive navigation when you need to deploy a specific component

Cons -
1. Requires some familiarity with Aqua's architecture to navigate and download relevant manifest
2. Users need to download the deployment artifacts from multiple folders 
