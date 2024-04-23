a. What is amqp?
amqp (Advanced Messaging Queing Protocol) adalah suatu <i>open standard application layer protocol for message-oriented middleware</i> yang memiliki fokus terhadap <i>message orientation, queuing, routing, reliability,</i> dan <i>security</i>.

b. What it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?
- guest:guest@localhost:5672 adalah string koneksi untuk suatu server AMQP.<br/>
- guest yang pertama merupakan username untuk server.<br/>
- guest yang kedua merupakan password untuk server.<br/>
- Pada localhost:5672, localhost merupakan hostname dari server, sedangkan 5672 merupakan port number dimana server sedang<i>listening</i>. 5672 juga merupakan port default untuk AMQP.

Screenshot 'simulation slow subscriber':
![simulation slow subscriber](img/img_4.png)
Banyak queue sekitar 40-an, karena saya run cargo run secara berkali-kali dan waktu yang berdekatan.