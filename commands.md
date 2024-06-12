# create web hook in github repository to trigger bus-refresh

### goto configvalues github repo
### click settings
### click webhooks
### add webhook (button)
- payload url: http://localhost:8071/monitor
- goto www.hookdeck.com
- menu: developers -> hookdeck console
- add destination (button)
- on my mac: brew install hookdeck/hookdeck/hookdeck
- hookdeck login --cli-key 5g7mn67yey3dhmf5nzqxb2o0jd4x960n43t5jiyuj77q7tg0la
- hookdeck listen [port] Source

- enter hookdeck URL to github payload url