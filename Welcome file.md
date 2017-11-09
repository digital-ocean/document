uranoxchangementsmur"&gt;Mur</h1>
<p>>Mur
Elements defined here are owned by the Exosite business and Exchange user:BIZID: aeqnqiymw87zxgvi
EMAIL: exchange@exosite.com
They populate the public storefront with baseline offerings, including internal services normally granted to all solutions.</p>
Open a PR against the master branch if updates are needed.

## Make a service type Exchange Element
### Files structureIn the elements folder, contain all of the elements that we have. You need to create a folder, name it service-slervice name>`. In the folder create  a service-&service name>>.md` file and a service-service name.json file and a detail image and a thumbnail imgae for this service.  like this,
- elements
	- service-mbed
mbed_detail.pngmbed_thumbnail.pngservice-mbed_serivce.jsonservice-mbed_serivce.mdDefinitionWhen updating the markdown (.md) file, please have a look at a couple of other existing services (e.g., SPMS, Twilio, etc.) for formatting and content guidance.
### *.json File
- #### type 
	Only can be application right now. When calling bizapi, it only allow application type. After exchange element created, you need change type to [exchange-element-tool] to update it.
- #### name

- #### image
	For the Thumbnail and Details page images, please create a ticket with the name/s of the elements to service from MongoDB or use be created and add the label uxd-required. Then every Monday morning Nick backlog groom and plan that weeks (one week long) sprint and as much of the following as we know.
Marking it as a blocker/major or giving it a due date will help expedite!!  
	Once you have images, adding the file name to the JSON.  The UI does the differentiating between thumbnail and main image for you.
	- thumbnail<img src="./readme_resources/thumbnail.png" width="213">
- #### markdown
	When using [exchange-element-tool], it will stringify the md file and attach string to here. See md file](#md-file#### source
	</a>.</p>
&lt;</Since this is a service, you can just copy/paste exactly what any of the other services have for actions. The URL property is ignored for this element type but the full actions shape is required.  Here is what youll use:
“"actions: [
ul": “&t;<a hsraw.githubuserge/…",
“<a href="http://content.com/exosite-garatype%22:%E2%80%9C%22service">...",
    "type":“"service</a>”,
“",
    "primary”"”: true
]
</>tiers</h4>
<p>***&gt;- #### tiers
	***>
 – You’ll need to populate the `tiers` array or the element will not appear on the Exchange.  Youll want to list all of the tiers that this service can be accessed at.  So if its available for everyone then tiers: [ "free", "developer", "professional", "enterprise"]. If just professional or higher tiers: ["professional", "enterprise"], and so on.
### *.md File


 [exchange-element-tool]:hs://github.com/exosite/dqa-env/tree/master/bin/exchange-element-tool
 <style type="text/css">
    .img{
        width: 50%;
    }
</style>
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MDEzNDE0NTJdfQ==
-->