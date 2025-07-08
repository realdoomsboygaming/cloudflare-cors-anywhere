# cloudflare-cors-anywhere
Cloudflare CORS proxy in a worker.

CLOUDFLARE-CORS-ANYWHERE

Source:
https://github.com/Zibri/cloudflare-cors-anywhere

Post:
http://www.zibri.org/2019/07/your-own-cors-anywhere-proxy-on.html

## Deployment

This project is written in [Cloudfalre Workers](https://workers.cloudflare.com/), and can be easily deployed with [Wrangler CLI](https://developers.cloudflare.com/workers/wrangler/install-and-update/).

Note:

All received headers are also returned in "cors-received-headers" header.

To create your own is very easy, you just need to set up a cloudflare account and upload the worker code.  
