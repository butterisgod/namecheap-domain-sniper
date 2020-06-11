# namecheap-domain-sniper

## How to run
- Get a namecheap API key.
- Whitelist (on Namecheap API panel) the public IP of the machine running the script
- Prefund your namecheap account (at least as much as the domain costs to buy new, but recommend having a buffer) so the script can checkout fast without having to store billing details.
- Optional - get a Twilio API key if you wish to have an SMS sent to your phone when the domain is available for purchase.
- Copy `.env-sample` to `.env` and set your variables.
- Run it `node index`


Twilio API is optional and will text you when domain is available in case script fails to purchase.
