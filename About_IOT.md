# IOT
**Internet** - Connects **Humans** <br>
**IOT** - Connects **Smart Devices**
<br>
**Definition** - IOT is a **network of smart devices** that are connected together for the purpose of exchanging data such as **settings and telemetry** over the internet
<br>
<br>
# Communication Models

1. Request & Response Model –<br>
- it follows Client-Server Architecture
- Client request info from server
- the server categorizez the request and fetches the data from database
- data is converted in response and sent to client
2. Publisher-Subscriber Model –
- Publisher sends data to broker
- Publisher is unaware of consumers
- Broker accepts data from publisher and sends it to appropriate consumers  
3. Push-Pull Model – 
- Publisher pushes data in a buffer called Queue 
- Consumers pull data from Queue
4. Exclusive Pair –

- Full Duplex Communication i.e. bidirectional communication

# Charecteristics of IOT

- Unique Identity : To uniqely identify each other and communicate
- Dynamic Nature : Connected/Disconnected start/Stop On/Off continously
- Self Configuring : Intelligently change settings according to enviroments
- Hetroginity : Muliple protocols and wide compatability

# IOT Security Problems

- **DOS (Denial of Service)** : 1 attacker flooding server with garbage request
- **DDOS (Distributed Denial of Service)** : Attacker floods server with botnet army
- **Unauthorized Access** : Fraud user gets access to IOT system
- **Information Manipulation** : Fraud User starts manipulating data 
- **Information Manipulation** : Attcker gets access to location where data is stored by IOT devices

# REST vs Web Socket

## REST
- stateless
- each request involves settimng up a new TCP connection

## Web Socket
- statefull
- single TCP connection


 
