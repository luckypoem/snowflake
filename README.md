# snowflake-pt

A Pluggable Transport using WebRTC

### Usage

Open up four terminals:

1. tor -f torrc SOCKSPort auto
2. tail -F webrtc-client.log
3. cat > signal
4. open proxy/snowflake.html

Look for the offer in terminal 2; copy and paste it into the browswer window
opened from terminal 4. Copy and paste the answer from terminal 4 to terminal 3.
At this point you should see some TLS garbage in the chat window.

### More

More documentation on the way.