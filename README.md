client code <br>
let ws = new WebSocket("ws://localhost:8080"); <br>
ws.onmessage = message => console.log(`Received: ${message.data}`);<br>
ws.send("Hello! I'm client")<br>
