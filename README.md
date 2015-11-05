HOW TO USE:

1) Create an incoming webhook integration in your slack and note down the URL.

2) Put into /usr/(local/)share/check_mk/notifications (or ~/share/check_mk/notifications) directory and edit configuration variables in script.

3) Create a 'slack' user in WATO, use flexible custom notifications and select 'CMK-Slack Websocket integration

4) Wait for something to send an alert.
