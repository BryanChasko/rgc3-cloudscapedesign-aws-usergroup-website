# rgc3-cloudscapedesign-aws-usergroup-website

this is the public facing code for bryanchasko.com

Deploying a cloudscape design system website using aws s3 static website hosting, cdn by cloudfront, route53 hosting and dns tables, .

I have configured my aws cli with proper access and am using wsl2 linux with zsh as my bash, vim as my windows terminal editor, and vscode on windows 10 with github copilot as my instructor / primary coder. 

From my prior experience deploying bryanchasko.com, I learned a few things:
1. DNS propagation through the cdn can take a long time, so its worth launching a basic index.html and getting all the routing setup prior to focusing on design, build process, etc.
1.1 in the case of s3, you need to name the bucket you want serving to the public web to match the domain you own. I.e., for bryanchasko.com I needed my “primary” bucket to be named bryanchasko.com

2. Since I’m working with github copilot, I will be utilizing readme files to provide the LLM with context about my project and keep the model updated as I go. In theory they should be able to view everything open in context, but in practice it hasn’t quite worked that way. I have created a local directory rgc3-cloudscapedesign-aws-usergroup-website and in there I intend to have most files stored in a public github repository I am labeling rgc3-cloudscapedesign-aws-usergroup-website. However on bryanchasko.com I probably shared too many things on the public web and then deleted the sensitive info in the effort of keeping it off the public web. The lesson learn is start with a private repo with files that are in the public .gitignore but regularly updated on a rgc3-cloudscapedesign-aws-usergroup-website-private repo so that the github copilot can act as a true pair programmer and provide working code .



