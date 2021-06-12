# Product/Component centric structure  

This deployments repo structure is component/product centirc. It uses the unified path -  ***path::[Component]/[Platform]/[Method]/<deployment manifest/tool>***

Pros -
1. Structure is agnostic to the Aqua delivery method - Aqua Enterprise or Aqua Cloud. The user picks the components he wants to deploy. 
2. Lean - there are no duplicate directories 
3. Intuitive navigation when you need to deploy a specific component

Cons -
1. Requires some familiarity with Aqua's architecture to navigate and download relevant components
2. Aqua Cloud customers have visibility to the server deployment manifests 
3. Users need to download the deployment artifacts from multiple folders 
