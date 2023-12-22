FROM ngrok/ngrok:3

ENTRYPOINT ngrok http "$NAME:$PORT" --log stdout --response-header-add "Access-Control-Allow-Origin: *"
