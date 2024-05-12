# rtc-tunnel-cleaned-signaling-server-azzoppata (signaling 8 ultima versione, con la gestione del topic)


## da aggiungere -st 9.0.0.1

python3 server.py -w -u http://127.0.0.1:8080 -r ws://127.0.0.1:8080 --topic topic1

python3 client.py -s 5000 -d 5000 -w -u http://127.0.0.1:8080 -r ws://127.0.0.1:8080 --topic topic1
