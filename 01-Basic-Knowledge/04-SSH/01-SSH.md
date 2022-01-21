# SSH

<p>for mor info go to: <strong><a href="https://www.ssh.com/academy/ssh">SSH</a></strong></p>

## What is SSH

SSH (Secure Socket Shell) is a web protocol for remote administration that allow control and modification of yours web servers, it ensures that all communications take place in a cryptography way, providing tools to authenticate the remote user, transferring the client input to the host server and relaying the output back to the client

Secure Shell (SSH) is a protocol for secure remote login and other secure network services over an insecure network.  It consists of
three major components:

- The Transport Layer Protocol [SSH-TRANS] provides server authentication, confidentiality, and integrity.  It may optionally also provide compression. The transport layer will typically be run over a TCP/IP connection, but might also be used on top of any other reliable data stream.

- The User Authentication Protocol [SSH-USERAUTH] authenticates the client-side user to the server.  It runs over the transport layer protocol.

- The Connection Protocol [SSH-CONNECT] multiplexes the encrypted tunnel into several logical channels.  It runs over the user authentication protocol.

## Types of cryptography

### Symmetrical cryptography

Use the same key to encode and decode the client message and de server message.

The process of creating a symmetric key is formed by changing an algorithm key, the key is never disclosed between client and host, in this way the public sharing of data chunks and the manipulation of this data happen independently, and compute this secret key. Even if a third party compute this key the algorithm is not going to be accept.

### Asymmetrical cryptography

Unlike the symmetrical cryptography, the asymmetrical cryptography use two different keys one for cryptography (public-key) and other for decryption (private-key)  

The relationship between the two types of keys is somewhat complex. The information or message is encrypted by the machine's public key, which can only be decrypted by the machine's private key.

This means that the public key cannot decode its own messages. Nor decode something already encrypted by the private-key. So anyone who wants to decrypt public data must first have the corresponding private key.

### Hashing

The Hashing encryption method involves the process of encoding data and messages, but never decoding this information. Hence, it is also called One-Way Hashing.

What happens is that the hashing generates a single, fixed-length value for each input that shows no propensity that it can be exploited. This makes reversing (decoding) virtually impossible.

SSH uses hashes to authenticate the validity of messages. This is done through Hash-Based Authentication Codes (HMCA), which only the interested user has access to. This ensures that the received command cannot be manipulated in any way.

## SSH CLients Tools

1. KiTTY
2. Solar PuTTY and other PuTTY versions. SuperPuTTY, PuTTY Tray, ExtraPuTTY
3. MobaXterm
4. WinSCP
5. SmarTTY
6. Bitvise SSH Client
7. Terminals
8. Chrome SSH extension
9. mRemoteNG
10. ZOC
11. FileZilla
12. Xshell
