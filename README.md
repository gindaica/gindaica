ok- 👋 Hi, I’m @gindaica
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
gindaica/gindaica is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
Starting with wireless adb...


javax.net.ssl.SSLProtocolException: Read error: ssl=0xb400007a9f9020d8: Failure in SSL library, usually a protocol error
error:10000416:SSL routines:OPENSSL_internal:SSLV3_ALERT_CERTIFICATE_UNKNOWN (external/boringssl/src/ssl/tls_record.cc:572 0xb400007a3f945370:0x00000003)
	at com.android.org.conscrypt.NativeCrypto.ENGINE_SSL_read_direct(Native Method)
	at com.android.org.conscrypt.NativeSsl.readDirectByteBuffer(NativeSsl.java:566)
	at com.android.org.conscrypt.ConscryptEngine.readPlaintextDataDirect(ConscryptEngine.java:1092)
	at com.android.org.conscrypt.ConscryptEngine.readPlaintextData(ConscryptEngine.java:1076)
	at com.android.org.conscrypt.ConscryptEngine.unwrap(ConscryptEngine.java:873)
	at com.android.org.conscrypt.ConscryptEngine.unwrap(ConscryptEngine.java:744)
	at com.android.org.conscrypt.ConscryptEngine.unwrap(ConscryptEngine.java:709)
	at com.android.org.conscrypt.ConscryptEngineSocket$SSLInputStream.processDataFromSocket(ConscryptEngineSocket.java:902)
	at com.android.org.conscrypt.ConscryptEngineSocket$SSLInputStream.readUntilDataAvailable(ConscryptEngineSocket.java:868)
	at com.android.org.conscrypt.ConscryptEngineSocket$SSLInputStream.read(ConscryptEngineSocket.java:841)
	at java.io.DataInputStream.readFully(DataInputStream.java:203)
	at rikka.shizuku.z2.e(SourceFile:22)
	at rikka.shizuku.z2.a(SourceFile:195)
	at moe.shizuku.manager.starter.b$a.l(SourceFile:42)
	at rikka.shizuku.t9.n(SourceFile:12)
	at rikka.shizuku.kk.run(SourceFile:119)
	at rikka.shizuku.hz.run(SourceFile:13)
	at rikka.shizuku.om0.run(SourceFile:3)
	at rikka.shizuku.kg.l(SourceFile:1)
	at rikka.shizuku.kg$c.d(SourceFile:15)
	at rikka.shizuku.kg$c.n(SourceFile:29)
	at rikka.shizuku.kg$c.run(Unknown Source:0)--->
