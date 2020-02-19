- need http-server npm package
https://www.npmjs.com/package/http-server


- need /public folder by default
- update hosts file to include entry:
	127.0.0.1 thirdpartysite.com
- May need cert (see: https://www.npmjs.com/package/http-server)
- need to load 'script.js' onto a 'http' server for demo


Run commands:
http-server -p 8080
http-server -p 8081 -s


- 2 servers - one for 'http' and one for 'https'
- fire up osd.htm on both servers
- run inject button on both pages - onclick will provide status message stating successful load of the attack script.

- after script load, demo attack by entering in creds and submit.
-- On submit (on http site): Alert prompt will yield username/pw details
-- On submit (on https site): No problem, and will proceed to submission page
